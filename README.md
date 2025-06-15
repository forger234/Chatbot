💬 Chat with GPT-4

A sleek, responsive, and theme-toggleable chat interface powered by GPT-4, built with HTML, CSS, and JavaScript. This UI allows users to chat with an AI assistant through an interactive and user-friendly interface, featuring dark/light mode, typing indicators, and smooth animations.

<!-- Replace with actual screenshot URL if available -->
🚀 Features

    🌗 Dark/Light Mode Toggle – Switch between themes with a single click.

    💬 AI Chat Interface – Seamless message exchange between user and GPT-4 powered backend.

    ⌨️ Keyboard Shortcuts – Press Enter to send and Shift + Enter for a newline.

    🔄 Typing Indicator – Shows when the AI is "typing".

    📱 Fully Responsive – Works beautifully on mobile, tablet, and desktop.

    🔐 (Optional) Login Redirect Logic (commented out).

📂 Project Structure

.
├── index.html          # Main HTML file
├── style (inline)      # All styling within <style> tag
├── script (inline)     # Client-side logic, theme toggle, message handling
└── (Optional API)      # Backend API to connect with GPT-4 (AWS Lambda used here)

📦 Tech Stack

    Frontend: HTML5, CSS3, JavaScript (Vanilla)

    Icons: Font Awesome

    Backend: REST API (e.g., AWS Lambda + API Gateway)

🧠 How It Works

    User types a message in the chat input.

    On send (Enter or button), the message is posted to a backend API.

    While waiting, a typing animation appears.

    The AI's response is rendered dynamically with a styled message bubble.

⚙️ Setup Instructions
🔧 Requirements

    A running backend API that accepts POST requests at /ChatApp and returns { reply: "Your message here" }.

🖥️ To Use

    Clone the repository:

git clone https://github.com/your-username/chat-with-gpt4.git
cd chat-with-gpt4

Open index.html in your browser.

Modify the backend URL in the script if necessary:

    const response = await fetch("https://your-api-url/ChatApp", { ... });

🎨 Customization Tips

    💡 Modify --primary-color in :root to change theme accent.

    🔄 Replace the fa-robot and fa-user icons as needed.

    🔐 Uncomment the redirect logic to enforce login-based access.

🖼️ Screenshots
Light Mode	Dark Mode
	
📌 TODO / Improvements

Add persistent chat history using localStorage

Support image/file uploads

Add loading/error animations for network failures

    OAuth or Token-based Authentication

🤝 Contributing

Contributions, issues, and feature requests are welcome!
Feel free to open a pull request or issue.
📄 License

MIT License © ANILA THOMAS
