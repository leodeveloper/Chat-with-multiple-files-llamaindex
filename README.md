# Chat-with-multiple-files-llamaindex
Creating a chat application that can handle multiple files using LlamaIndex, OpenAI, and Streamlit involves several steps

# Multi-File Chat Application

This repository contains a chat application that allows users to upload multiple files, processes these files to extract information, and then uses an AI model (OpenAI's GPT-4) to answer questions or provide insights based on the content of the files. The application is built using Streamlit for the front-end interface, LlamaIndex for indexing and searching through the content, and OpenAI for the natural language processing capabilities.

## Features

- Upload multiple text files.
- Index and search content from the uploaded files.
- Ask questions and get answers based on the content of the files using OpenAI's GPT-4.

## Requirements

- Python 3.8 or higher
- `streamlit` library
- `openai` library
- `llama-index` library

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/leodeveloper/Chat-with-multiple-files-llamaindex
    cd Chat-with-multiple-files-llamaindex
    ```

2. Install the required Python packages:

    ```bash
    pip install streamlit openai llama-index
    ```

3. Set up your OpenAI API key:

    Obtain your API key from OpenAI and set it as an environment variable or replace `'YOUR_OPENAI_API_KEY'` in the script with your actual API key.

    ```bash
    export OPENAI_API_KEY='your-api-key'
    ```



## Application Flow

1. **Upload Files**: Use the file uploader to upload multiple text files.
2. **Indexing**: The content of the uploaded files is read and indexed using LlamaIndex.
3. **Ask Questions**: Input your questions in the chat interface.
4. **Get Answers**: The application retrieves relevant content from the indexed files and uses OpenAI's GPT-4 to generate and display answers.

## Example

1. **Upload Files**: Select and upload multiple text files.
2. **Ask a Question**: Type a question related to the content of the uploaded files.
3. **Receive an Answer**: The application provides an answer based on the indexed content and AI processing.

## Contributing

Contributions are welcome! Please submit a pull request or open an issue to discuss any changes or improvements.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [Streamlit](https://streamlit.io/)
- [OpenAI](https://www.openai.com/)
- [LlamaIndex](https://github.com/leodeveloper/Chat-with-multiple-files-llamaindex)

## Contact

For any questions or suggestions, please feel free to reach out to [leodeveloper@gmail.com].

