# Large Language Model OS

## This project was originally built by [phidatahq](https://github.com/phidatahq/phidata)

# LLM OS Application

## Overview
LLM OS is a Streamlit-based application that leverages large language models (LLMs) to provide a versatile assistant with multiple tools. The application is built using the `phidata` library and offers various functionalities like calculator, file tools, web search, and specialized assistants for data analysis, Python coding, research, and investments.

## Features
- **LLM Selection**: Choose between different LLM models (`gpt-4o`, `gpt-4-turbo`).
- **Tool Enabling**: Enable or disable tools such as calculator, file tools, web search, and shell tools.
- **Team Member Assistants**: Enable assistants for data analysis, Python programming, research, and investments.
- **Knowledge Base Management**: Add URLs and PDFs to the assistant's knowledge base.
- **Chat History**: Maintains chat history and allows for dynamic interaction with the assistant.

## Prerequisites
- Docker
- Docker Compose

## Getting Started

### Clone the Repository
```bash
git clone https://github.com/brainzcode/llm_os.git
cd llm_os
```

### Build and Run the Application
1. **Build the Docker Image**:
    ```bash
    docker-compose up --build
    ```

### Access the Application
Once the application is running, open your web browser and navigate to:
```
http://localhost:8502
```

## Using the Application

### Main Page
- **Select LLM**: Choose between available language models.
- **Enable Tools**: Use the sidebar to enable or disable tools such as Calculator, File Tools, Web Search, Shell Tools.
- **Team Members**: Enable specialized assistants for different tasks.
- **Chat Interface**: Interact with the assistant, ask questions, and get responses.

### Knowledge Base Management
- **Add URLs**: Use the sidebar to input URLs and add them to the knowledge base.
- **Add PDFs**: Upload PDF documents to be included in the knowledge base.

## Contributing
Contributions are welcome! Please fork the repository and create a pull request with your changes.


## Acknowledgements
- [Streamlit](https://streamlit.io/)
- [phidata](https://github.com/phidatahq/phidata)

For more information, please visit the [phidatahq](https://github.com/phidatahq/phidata).

---
