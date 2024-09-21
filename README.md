# Custom Image Generator

Custom Image Generator is a web-based application that allows users to generate images from textual descriptions using OpenAI's DALL-E model. The app is built using Flask for the backend and Bootstrap for the frontend. It leverages OpenAI's API to create AI-generated images based on user input and displays the generated image directly on the page.

## Features

- Generate images based on textual prompts.
- Simple and responsive UI built with Bootstrap.
- Displays generated images directly on the web page.
- Ability to copy the image URL to the clipboard.

## How to Use

### Prerequisites

Before you begin, ensure you have the following installed on your local machine:

- Python 3.x
- Flask
- OpenAI API Key
- boltiotai module for OpenAI integration.

### Installation

1. *Clone the repository:*

   bash
   git clone https://github.com/yourusername/Custom-Image-Generator.git
   cd Custom-Image-Generator
   

2. *Install the required dependencies:*

   Install the dependencies specified in requirements.txt:

   bash
   pip install flask openai boltiotai
   

3. *Set up your OpenAI API Key:*

   Export your OpenAI API key as an environment variable. On Linux/macOS, run:

   bash
   export OPENAI_API_KEY='your-openai-api-key'
   

   On Windows:

   cmd
   set OPENAI_API_KEY='your-openai-api-key'
   

### Configuration

1. *Configure the OpenAI API*:  
   In the Python script, make sure that the OpenAI API key is correctly imported from your environment variables:

   python
   openai.api_key = os.environ['OPENAI_API_KEY']
   

2. *Running the Application:*

   Run the Flask application with the following command:

   bash
   python app.py
   

   By default, the app will run on localhost:8080. You can access it by navigating to:

   
   http://localhost:8080
   

### Usage

1. Once the app is running, open the URL in your browser.
2. Enter a textual description (e.g., "A lion in a cage") in the input field.
3. Click the "Share with the Image" button to generate an image.
4. The image will be displayed on the page, and you can copy the image URL to your clipboard using the "Copy" button.

## Contribution

If you'd like to contribute to the project, follow these steps:

1. Fork the repository.
2. Create a new feature branch (git checkout -b feature/AmazingFeature).
3. Commit your changes (git commit -m 'Add some AmazingFeature').
4. Push to the branch (git push origin feature/AmazingFeature).
5. Open a Pull Request.

## Conclusion

This project demonstrates how to use OpenAI's DALL-E model with Flask to build a simple and interactive image generator. The app is extendable, and you can modify it to add more features or enhance the user interface. Feel free to contribute and make this project better!

---

This README.md provides all the essential details and instructions for users to set up, run, and contribute to your Custom Image Generator project.
