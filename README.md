# SyntaxSage
---
# Interactive Code Assistant for VS Code

- Enhance your coding experience with real-time AI-powered code analysis, correction, and suggestions directly within your VS Code editor.


---

### Features

- 1. Inline Code Correction

- Automatically detects syntax and logical errors in your code.

- Suggests or applies corrections directly in your VS Code editor.


- 2. Real-Time Code Analysis

- Analyzes your code as you type, ensuring best practices and efficient logic.

- Highlights problematic code with detailed explanations and potential fixes.


- 3. Code Explanation and Optimization

- Provides clear, actionable feedback on why certain code segments might fail.

- Suggests optimizations for performance and readability.


- 4. Multi-Language Support

- Supports popular programming languages such as JavaScript, Python, and more (with modular support for additional languages).



---

### Getting Started

- Prerequisites

- Before you begin, ensure you have the following installed:

- Visual Studio Code (latest version recommended)

- Node.js (v14 or higher)

- Python (v3.7 or higher)

- Flask (for the AI backend)


- You will also need an OpenAI API Key to enable the AI functionality.


---

### Installation

- 1. Clone the Repository:
```
git clone https://github.com/your-username/interactive-code-assistant.git
cd interactive-code-assistant
```

- 2. Install Dependencies:

- VS Code Extension:
```
cd vscode-extension
npm install
```
### Backend:
```
cd backend
pip install -r requirements.txt
```


- 3. Set Up Environment Variables:

- Create a .env file in the backend directory with the following:
```
OPENAI_API_KEY=your-openai-api-key
```


- 4. Start the Backend Server:
```
cd backend
python app.py
```

- 5. Start the VS Code Extension:
```
cd vscode-extension
npm run start
```

- 6. Open VS Code and test the extension!




---

### How It Works

- 1. Code Analysis:

- As you write code, the VS Code extension sends it to the backend AI for analysis.



- 2. AI-Powered Suggestions:

- The AI returns suggestions or corrections, which are displayed inline in your editor.



- 3. Interactive Corrections:

- Apply corrections manually or let the assistant auto-correct common mistakes.





---

### Usage

- 1. Write your code as usual in VS Code.


- 2. Look for:

- Highlights: Errors or areas of improvement in your code.

- Hover Messages: Explanations for the issues and suggestions.



- 3. Accept or reject AI suggestions with a single click.




---

### Contributing

- We welcome contributions! Here's how you can get involved:

- 1. Fork the repository.


- 2. Create a new branch:
```
git checkout -b feature-name

```
- 3. Commit your changes:
```
git commit -m "Add feature-name"
```

- 4. Push to your branch:
```
git push origin feature-name
```

- 5. Open a pull request.



- Check the CONTRIBUTING.md for detailed guidelines.


---

- Roadmap

- Current Development

- Multi-language support for TypeScript and Java.

- Improved performance for large codebases.


- Upcoming Features

- Refactoring suggestions.

- AI-assisted test generation.

- CI/CD pipeline integration.



---

- Issues and Feedback

- Encountered a problem? Have suggestions?
- Please check the Issues page or open a new issue.


---

### License

- This project is licensed under the MIT License. See the LICENSE file for details.


---

### Acknowledgments

- Built using VS Code API and OpenAI for AI-powered analysis.

- Inspired by the need for a seamless coding experience.



---

- Let me know if you'd like help customizing this further!

