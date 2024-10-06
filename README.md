# AI Text Summarizer
<br>![Website](https://img.shields.io/website?url=https%3A%2F%2Fremiel.fyi%2Fai-summarizer) ![GitHub License](https://img.shields.io/github/license/jaswanthremiel/AI-text-summarizer) ![Maintenance](https://img.shields.io/maintenance/no/2024)

AI Text Summarizer is a Node.js-based server-side rendering application designed to provide users with concise summaries of lengthy texts. Leveraging the advanced capabilities of Hugging Face's Facebook BART model, this project efficiently processes input text and generates meaningful summaries. The application features a user-friendly interface that allows users to easily enter text and receive summaries with just a click. Built using Express for web framework support, it ensures fast and secure data handling. This project not only aims to enhance productivity by distilling information but also prioritizes user privacy, making it an ideal tool for anyone needing quick insights from larger documents
## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [API Endpoints](#api-endpoints)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This project is a Node.js-based server-side rendering application that utilizes Hugging Face's Facebook BART model to summarize text efficiently. It aims to provide users with concise and meaningful summaries of longer texts.

## Features

- Summarizes text using advanced AI algorithms.
- Fast and efficient processing.
- User-friendly interface for easy interaction.
- Private and secure data handling.

## Technologies Used

- **Node.js**: Server-side JavaScript runtime.
- **Express**: Web framework for Node.js.
- **Hugging Face Transformers**: For implementing the BART model.
- **HTML/CSS**: For front-end rendering.

## Installation

To set up the project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/JaswanthRemiel/AI-text-Summarizer.git
2. Navigate to the project directory:
   ```bash
    cd AI-text-Summarizer
3. Install the required dependencies:
   ```bash
   npm install
4. Start the server:
   ```bash
   npm start
The application should now be running on ````http://localhost:3000````

## Usage
1. Open your web browser and navigate to http://localhost:3000.
2. Enter the text you want to summarize in the input field.
3. Click on the "Summarize" button to receive the summarized text.

## API Endpoints
POST /summarize
<br>Description: Summarizes the provided text.
<br>Request Body:
```json
{
  "text": "Your long text here."
}
```
<br>Response:
```json
{
  "summary": "The summarized text here."
}
```
## Contributing
Contributions are welcome! If you have suggestions for improvements or features, feel free to fork the repository and submit a pull request.
## License
This project is licensed under the MIT License. See the LICENSE file for more details.
