# Interactive Code Assistant for VS Code

- A powerful, real-time AI-driven code assistant designed to enhance your coding experience.


---

### Features

- 🔧 Inline Code Correction

- Automatically detects syntax and logical errors in your code.

- Provides suggestions or applies corrections directly in VS Code.


- 📊 Real-Time Code Analysis

- Analyzes code for syntax, logic, and performance issues as you type.

- Highlights problematic areas with actionable insights.


###💡 Code Explanation and Optimization

- Explains why a piece of code might fail and offers alternatives.

- Recommends improvements for better performance and readability.


### 🌐 Multi-Language Support

- Currently supports:

- JavaScript

- Python


- Modular design allows for easy addition of other languages.



---

### Getting Started

#### Prerequisites

- Ensure you have the following installed:

- Visual Studio Code (latest version recommended)

- Node.js (v14 or higher)

- Python (v3.7 or higher)

- Flask (for the AI backend)


- You also need an OpenAI API Key to enable AI functionality.


---

### Installation

- 1. Clone the Repository
```
git clone https://github.com/your-username/interactive-code-assistant.git
cd interactive-code-assistant
```

- 2. Install Dependencies

- For the VS Code Extension:
```
cd vscode-extension
npm install
```
- For the Backend:
```
cd backend
pip install -r requirements.txt
```


- 3. Set Up Environment Variables
Create a .env file in the backend directory:
```
OPENAI_API_KEY=your-openai-api-key
```

- 4. Start the Backend Server
```
cd backend
python app.py
```

- 5. Start the VS Code Extension
```
cd vscode-extension
npm run start
```

- 6. Test the Extension in VS Code




---

### How It Works

- 1. Code Analysis

- The extension sends your code to the backend AI for analysis.



- 2. AI-Powered Suggestions

- The backend returns suggestions or corrections, which appear inline in your editor.



- 3. Interactive Corrections

- Choose to apply corrections manually or let the assistant auto-correct common errors.





---

### Usage

- 1. Write your code in VS Code as usual.


- 2. Look for:

- Highlights: Errors or areas of improvement.

- Hover Messages: Explanations and suggestions from the AI.



- 3. Accept or reject suggestions with a single click.




---

### Contributing

- We welcome contributions!

#### Steps to Contribute:

- 1. Fork the Repository
```
git fork https://github.com/your-username/interactive-code-assistant.git
```

- 2. Create a New Branch
```
git checkout -b feature-name
```

- 3. Commit Your Changes
```
git commit -m "Add feature-name"
```

- 4. Push to Your Branch
```
git push origin feature-name
```

- 5. Open a Pull Request



#### Please check our CONTRIBUTING.md for detailed guidelines.


---

### Roadmap

- Current Development

- Adding support for TypeScript and Java.

- Optimizing performance for large codebases.


### Upcoming Features

- Refactoring suggestions.

- Test case generation.

- CI/CD pipeline integration.



---

### Issues and Feedback

- If you encounter any issues or have suggestions:

- Check the Issues page.

- Or open a new issue directly.



---

### License

- This project is licensed under the MIT License.
See the LICENSE file for details.


---

### Acknowledgments

- Built using the VS Code API.

- AI-powered analysis by OpenAI.

