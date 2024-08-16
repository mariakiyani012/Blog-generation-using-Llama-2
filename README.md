# Blog Generation Using LLaMA 2

## Description

This project provides a web application for generating blog content using the LLaMA 2 model. Built with Streamlit, the application allows users to specify a blog topic, the number of words, and the target audience. The backend uses the `CTransformers` library to interact with the LLaMA 2 model, generating blog content based on the user inputs.

## Features

- **Blog Topic Input**: Enter the topic for the blog you want to generate.
- **Word Count Specification**: Specify the desired length of the blog in words.
- **Target Audience Selection**: Choose the intended audience for the blog (e.g., Researchers, Data Scientists, Common People).
- **Blog Generation**: Generate a blog based on the input specifications.

## Requirements

- `sentence-transformers`
- `uvicorn`
- `ctransformers`
- `langchain`
- `python-box`
- `streamlit`

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/blog-generation-llama2.git
   ```

2. Navigate to the project directory:
   ```bash
   cd blog-generation-llama2
   ```

3. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Run the Streamlit application:
   ```bash
   streamlit run app.py
   ```

2. Open your web browser and go to `http://localhost:8501` to access the app.

3. Enter the blog topic, specify the number of words, and select the target audience. Click "Generate" to create the blog.

## Contributing

Feel free to submit issues, fork the repository, or send pull requests. Contributions are welcome!

## License

This project is licensed under the MIT License.
