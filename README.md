# Gemini_Clone

Here’s a professional and well-structured `README.md` file for your GitHub repository. It provides an overview of your project, instructions for setup, and details about the code.

---

# Gemini Clone

A lightweight front-end clone of Gemini, a conversational AI, built with HTML, CSS, and JavaScript. This project simulates a chat interface where users can interact with an AI-powered chatbot. The chatbot uses the Gemini API to generate responses.

[Demo](https://gemini-clone-model.vercel.app/)  

---

## Features

- **Chat Interface**: A clean and responsive chat interface for user interactions.
- **AI-Powered Responses**: Integrates with the Gemini API to generate dynamic responses.
- **Light/Dark Mode**: Toggle between light and dark themes for better user experience.
- **Message History**: Saves chat history in the browser's `localStorage`.
- **Copy to Clipboard**: Allows users to copy chatbot responses with a single click.
- **Predefined Suggestions**: Quick suggestions for users to start conversations.

---

## Technologies Used

- **Front-End**:
  - HTML5
  - CSS3
  - JavaScript (ES6+)
- **API**:
  - [Gemini API](https://generativelanguage.googleapis.com) for generating responses.
- **Hosting**:
  - [Vercel](https://vercel.com) (or any other platform of your choice).

---

## Setup and Installation

### Prerequisites
- A Gemini API key. You can obtain one from the [Google Cloud Console](https://console.cloud.google.com/).
- A modern web browser (Chrome, Firefox, Edge, etc.).

### Steps to Run Locally

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Rohit-kr17/Gemini_Clone.git
   cd Gemini_Clone
   ```

2. **Add Your API Key**:
   - Open the `script.js` file.
   - Replace the `API_KEY` variable with your Gemini API key:
     ```javascript
     const API_KEY = "YOUR_GEMINI_API_KEY_HERE";
     ```

3. **Run the Project**:
   - Open the `index.html` file in your browser.
   - Alternatively, use a local server (e.g., VS Code Live Server or `http-server`).

4. **Deploy to Vercel**:
   - Install the Vercel CLI:
     ```bash
     npm install -g vercel
     ```
   - Deploy the project:
     ```bash
     vercel
     ```

---

## Code Structure

- **`index.html`**: The main HTML file for the chat interface.
- **`style.css`**: Contains all the styling for the project.
- **`script.js`**: Handles the logic for user interactions, API calls, and dynamic updates.
- **`images/`**: Contains assets like the Gemini logo and user avatar.

---

## How It Works

1. **User Input**:
   - The user types a message or selects a predefined suggestion.
   - The message is displayed in the chat interface.

2. **API Call**:
   - The message is sent to the Gemini API using a `POST` request.
   - The API processes the input and generates a response.

3. **Display Response**:
   - The chatbot's response is displayed with a typing effect.
   - The response is saved in `localStorage` for persistence.

4. **Additional Features**:
   - Users can toggle between light and dark themes.
   - Chat history can be deleted with a single click.

---

## Environment Variables

To securely use the Gemini API, ensure your API key is stored in an environment variable. For local development, you can use a `.env` file:

```plaintext
API_KEY=your_gemini_api_key_here
```

In your `script.js`, access the key like this:

```javascript
const API_KEY = process.env.API_KEY;
```

---

## Contributing

Contributions are welcome! If you'd like to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bugfix.
3. Commit your changes.
4. Submit a pull request.

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Acknowledgments

- [Google Gemini API](https://generativelanguage.googleapis.com) for providing the AI capabilities.
- [Vercel](https://vercel.com) for seamless deployment.

---

## Contact

For questions or feedback, feel free to reach out:

- **Name**: Rohit Kumar
- **GitHub**: [Rohit-kr17](https://github.com/Rohit-kr17)
- **Email**: Rohitkr.17@outlook.com

---
