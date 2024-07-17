
# Speech Text Reader

The Speech Text Reader is a web application that allows users to enter text, choose a voice, and have the text read aloud using the browser's Speech Synthesis API. It also provides a set of pre-defined phrases with images that users can click on to hear the phrase spoken.

## Table of Contents

- [Features](#features)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Technologies](#technologies)
- [Project Structure](#project-structure)
- [License](#license)

## Features

- Enter custom text to be read aloud.
- Choose from available voices.
- Pre-defined phrases with images that can be clicked to hear the phrase.
- Toggle visibility of the text input box.
- Responsive design using CSS Grid.

## Getting Started

### Prerequisites

To run this project, you need a web browser that supports the Speech Synthesis API.

### Installation

1. Clone the repository:

   \`\`\`bash
   git clone https://github.com/Harishvinayagam/Speech-Text-Reader.git
   \`\`\`

2. Navigate to the project directory:

   \`\`\`bash
   cd Speech-Text-Reader
   \`\`\`

3. Open the \`index.html\` file in your web browser.

## Usage

1. Open the \`index.html\` file in your web browser.
2. Click the "Toggle Text Box" button to display the text input area.
3. Choose a voice from the dropdown menu.
4. Enter text in the textarea and click "Read Text" to hear it spoken.
5. Click on any of the pre-defined phrases to hear them spoken.

## Technologies

- HTML
- CSS
- JavaScript
- Speech Synthesis API

## Project Structure

\`\`\`
Speech-Text-Reader/
│
├── img/
│   ├── angry.jpg
│   ├── drink.jpg
│   ├── food.jpg
│   ├── grandma.jpg
│   ├── happy.jpg
│   ├── home.jpg
│   ├── hurt.jpg
│   ├── outside.jpg
│   ├── sad.jpg
│   ├── scared.jpg
│   ├── school.jpg
│   └── tired.jpg
│
├── style.css
├── script.js
└── index.html
\`\`\`

### \`index.html\`

The main HTML file containing the structure of the application.

### \`style.css\`

The CSS file containing styles for the application, including layout and animations.

### \`script.js\`

The JavaScript file containing the functionality for the application, including speech synthesis, event handling, and dynamic content creation.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
