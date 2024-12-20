# QuantumBot

QuantumBot is an intelligent chatbot application that allows users to ask any question and receive real-time answers. It leverages Google’s Gemini API for natural language processing and the Web Speech API for speech recognition, providing a seamless and interactive user experience.

## Features

- **Real-Time Q&A:** Users can ask any question, and QuantumBot will respond in real time with accurate answers.
- **Speech Recognition:** Users can speak their questions, and the bot will convert speech to text using the Web Speech API.
- **File Attachment Support:** Users can attach files during the conversation, which the bot can process and respond to accordingly.
- **Interactive Chat Interface:** A user-friendly interface for smooth communication with the bot.

## Technologies Used

- **Google’s Gemini API:** Powers the bot’s natural language understanding and intelligent responses.
- **Web Speech API:** Enables voice input by converting speech to text.
- **Node.js & Express.js:** Backend server for handling user queries and communication with the Gemini API.
- **HTML, CSS, JavaScript:** Frontend technologies for building the interactive chat interface.

## How It Works

1. Users can type their questions in the input box or click the microphone button to ask questions via speech.
2. The bot processes the input (text or speech) and sends it to Google’s Gemini API for analysis.
3. The API returns the response, which is displayed in the chat interface in real time.
4. Users can also attach files to their messages, which the bot can process as needed.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/quantumbot.git
   cd quantumbot
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Set up environment variables:
   - Create a `.env` file in the root directory.
   - Add your Google Gemini API key:
     ```
     GEMINI_API_KEY=your_api_key_here
     ```

4. Start the server:
   ```bash
   npm start
   ```

5. Open your browser and navigate to:
   ```
   http://localhost:3000
   ```

## Usage

1. **Ask Questions:** Type your question in the input box and press Enter, or click the send button.
2. **Use Voice Input:** Click the microphone button to start speech recognition, then speak your question.
3. **Attach Files:** Click the upload button to attach a file, and the bot will process it if necessary.

## Example Interaction

- **User:** "What is the capital of France?"
- **Bot:** "The capital of France is Paris."

- **User (via speech):** "Who won the FIFA World Cup in 2022?"
- **Bot:** "Argentina won the FIFA World Cup in 2022."

## Contributing

We welcome contributions! To contribute:

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-name
   ```
3. Make your changes and commit them:
   ```bash
   git commit -m "Add new feature"
   ```
4. Push to your branch:
   ```bash
   git push origin feature-name
   ```
5. Create a pull request.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgments

- **Google’s Gemini API:** For providing robust natural language processing capabilities.
- **Web Speech API:** For enabling voice input functionality.
- **Open Source Community:** For tools and libraries that made this project possible.
