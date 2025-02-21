# Cartesi VS Code Extension
![Blue Sky Photo Rainbow Facebook Cover (1)](https://github.com/user-attachments/assets/4d58f355-ee8e-446a-8a8a-9bdfed24e73b)

## Overview
The **Cartesi VS Code Extension** is designed to enhance the developer experience by providing seamless integration with the Cartesi ecosystem. This extension offers essential tools to build, test, and deploy Cartesi Rollups and Machines directly within Visual Studio Code.

## Features

### 1. Code Editor Enhancements
🧑‍💻 **Syntax Highlighting**: Supports Cartesi-specific formats like `.yaml`, `.json`, and `.lua`.

📄 **Code Snippets**: Provides reusable code templates for Cartesi Rollups and Machines.

### 2. Debugging and Testing
🐞 **Debug Adapter Protocol (DAP) Integration**: Step through Cartesi Machine execution.

🧪 **Cartesi Emulator Support**: Run and debug applications directly within VS Code.

### 3. Build and Deployment
⚙️ **Task Automation**: Automate Cartesi CLI commands using VS Code tasks.

🖥️ **Custom Terminal**: Pre-configured terminal for Cartesi development workflows.

### 4. Documentation Access
📚 **Inline Documentation**: Access Cartesi SDK and library documentation without leaving the editor.

📖 **In-Editor Tutorials**: Step-by-step guides for onboarding new developers.

### 5. Blockchain State Tools
🔍 **State Explorer**: Visualize Cartesi Rollups data (inputs, outputs, and disputes).

🔗 **API Query Tools**: Query and inspect Rollups state using Cartesi APIs.

### 6. AI Integration
🤖 **AI-Assisted Coding**: Cartesi-specific code suggestions powered by GitHub Copilot.

🔒 **Security Analysis**: AI-driven contract optimization and security checks.

## Installation

### Prerequisites
🧰 **Visual Studio Code**: Install from [VS Code official site](https://code.visualstudio.com/).

📦 **Node.js**: Download from [Node.js official site](https://nodejs.org/).

📊 **Cartesi CLI**: Set up using the [Cartesi documentation](https://cartesi.io/docs).

### Installation Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/BUIDLwithCartesi/cartesi-vscode-extension.git
   cd cartesi-vscode-extension
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Package the extension:
   ```bash
   vsce package
   ```
4. Install the `.vsix` file in VS Code:
   - Open VS Code.
   - Press `Ctrl+Shift+P` (or `Cmd+Shift+P` on macOS).
   - Select `Extensions: Install from VSIX...` and choose the packaged file.

## Usage

### Commands
🚀 **Run Emulator**: `Cartesi: Run Emulator` - Launch the Cartesi emulator.

📘 **Show Documentation**: `Cartesi: Show Documentation` - Open Cartesi documentation.

### Configuration
Set the Cartesi Emulator path using the `CARTESI_EMULATOR_PATH` environment variable:
```bash
export CARTESI_EMULATOR_PATH=/path/to/cartesi/emulator
```

## Development

### Project Structure
- 📂 `extension.js`: Main entry point.
- 📜 `package.json`: Metadata and configuration.
- 📋 `snippets/`: Cartesi-specific code snippets.
- 🧪 `test/`: Unit tests for the extension.

### Debugging
- Open the project in VS Code.
- Press `F5` to run the extension in a new Extension Development Host.

## Contributing
We welcome contributions to improve the Cartesi VS Code Extension. Follow these steps:
1. Fork the repository.
2. Create a feature branch.
3. Commit your changes and push the branch.
4. Open a pull request for review.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Support
For issues or feature requests, open an issue in the [GitHub repository](https://github.com/BUIDLwithCartesi/cartesi-vscode-extension/issues).

## Acknowledgments
Special thanks to the Cartesi team for their support and for providing the tools that made this extension possible.
