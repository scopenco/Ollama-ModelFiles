# Ollama Model Files Documentation

## Table of Contents
- [Overview](#overview)
- [Usage](#usage)
- [Features](#features)
- [Custom Model Setup](#custom-model-setup)

## Overview

The `cogito-coder` model is an advanced AI coding assistant designed for deep task research, modular code generation, and robust error handling. It is based on the `cogito:latest` image with custom parameters for temperature and context size.

## Usage

To create the model, use the following command:

```bash
ollama create cogito-coder -f ./ModelFile.cogito-coder
```

## Features

The `cogito-coder` model boasts several key features:

- Modular architecture for task handling
- Emphasis on clean, simple, and reliable code
- Structured reasoning and error handling

For full configuration details, refer to the `ModelFile.cogito-coder`.

---

## Custom Model Setup

You can use your custom Ollama model (e.g., `cogito-coder`) directly in VS Code with the Cline plugin for enhanced AI coding assistance.

### Steps:

1. **Install the Cline plugin** in VS Code from the Extensions Marketplace.
2. **Start your custom model** with Ollama:

	```bash
	ollama run cogito-coder
	```

3. **Configure Cline**:

	- Open the Cline plugin settings in VS Code.
	- Set the model endpoint to your local Ollama server (default: `http://localhost:11434`).
	- Enter your custom model name (e.g., `cogito-coder`).

4. **Use Cline**:

	- Interact with your model directly from the VS Code command palette or editor.

### Notes

- Ensure Ollama is running and your model is available before using Cline.
- Switch models by changing the model name in the Cline settings.
