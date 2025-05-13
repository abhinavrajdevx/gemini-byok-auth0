# 🌌 GEMINI BYOK | Next-Gen AI Interface

## ✨ Vision
Gemini BYOK (Bring Your Own Key) empowers users to harness Google's cutting-edge Gemini AI models using their own Google Cloud quota. No more sharing API keys or setting up complex authentication systems – simply authenticate with your Google account and start generating content instantly.

## 🚀 Features

- **Seamless Authentication** - One-click Google OAuth login
- **Model Selection** - Choose between Gemini 1.5 Pro and Gemini 1.5 Flash
- **Zero Configuration** - No API keys to manually manage
- **Persistent Sessions** - Stay logged in with secure token storage
- **Clean, Intuitive UI** - Distraction-free interface for AI interactions
- **Real-time Responses** - Get Gemini's answers immediately
- **User Profile Integration** - See your Google profile within the app

## 🔮 How It Works

Gemini BYOK utilizes OAuth authentication to access Google's Generative Language API on your behalf. When you authenticate, the application receives a token that allows it to make requests to Gemini using your Google Cloud quota. This means:

1. The developer doesn't pay for your API usage
2. You maintain control over your data and API access
3. Your existing Google Cloud rate limits and quotas apply

## 🛠️ Prerequisites

Before using Gemini BYOK, ensure you have:

- A Google account
- Gemini API enabled in your Google Cloud project
- Billing configured on your Google Cloud account (required for Gemini API)

## 🔧 Setup Instructions

### Quick Start

1. Clone the repository:
   ```
   git clone https://github.com/abhinavrajdevx/gemini-byok-auth0.git
   ```

2. Navigate to the project directory:
   ```
   cd gemini-byok-auth0
   ```

3. Open the `index.html` file in your browser, or serve it with a local web server:
   ```
   # Using Python's built-in server
   python -m http.server
   
   # Or with Node.js http-server
   npx http-server
   ```

### Cloud Deployment

For production deployment:

1. Upload the files to your preferred web hosting service
2. Ensure HTTPS is enabled (required for production OAuth flows)
3. Update the `redirect_uri` in the code to match your deployed URL

## 💫 Using the Application

1. **Sign In** - Click the "Sign in with Google" button and authorize the application
2. **Select Model** - Choose between Gemini 1.5 Pro (more powerful) or Flash (faster)
3. **Enter Prompt** - Type your query, instruction, or conversation starter
4. **Generate** - Click "Send to Gemini" and watch as AI-generated content appears

## ⚠️ Important Notes

- The application runs entirely in your browser – no server-side processing occurs
- Your prompts and the responses are never stored on our servers
- OAuth tokens are stored locally in your browser only
- Rate limits and quotas depend on your Google Cloud account settings

## 🔒 Privacy & Security

- Your Google authentication token is stored securely in your browser's localStorage
- No cookies are used for tracking purposes
- The application only requests the minimum scopes required for Gemini access

## 🛣️ Roadmap

- Multi-turn conversations
- Chat history saving
- Image prompt support
- Temperature and other parameter adjustments
- Theme customization
- Mobile optimization

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.

---

*Designed with ❤️ for the AI community*
