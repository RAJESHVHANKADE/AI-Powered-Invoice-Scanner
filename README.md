# AI-Powered Invoice Scanner

AI-Powered Invoice Scanner is a web application that utilizes Google's Gemini Pro Vision model to analyze invoice images and extract relevant information. This tool is designed to simplify the invoice processing workflow by providing users with insights based on the uploaded invoice.

## Features

- Upload an invoice image in JPG, PNG, or JPEG format.
- Get detailed analysis and insights from the invoice content.
- Leverage Google's Gemini Pro Vision model for powerful generative AI capabilities.
- Simple and intuitive web interface built with Streamlit.

## Installation

 1. **Clone the repository:**
  ```bash
     git clone https://github.com/yourusername/invoice-scanner.git
     cd invoice-scanner
  ```

 2. **Create and activate a virtual environment:**
 ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
 ```

 3. **Install the required packages:**
 ```bash
    pip install -r requirements.txt
 ```

 4. **Set up environment variables:**
 Create a .env file in the root directory.

 Add your Google API key:
 ```bash
    GOOGLE_API_KEY=your_api_key_here
 ```

## Usage

1. **Run the Streamlit application:**
```bash
   streamlit run sentiment_analysis.py
```

2. **Upload an invoice image.**

3. **Enter your query in the input prompt.**

4. **Click the "Tell me about invoice" button to get insights.**

## Example
Upload an image of an invoice and ask questions like:

**"What is the total amount?"**

**"Who is the vendor?"**

## Dependencies
`streamlit`
`PIL`
`google-generativeai`
`python-dotenv` 

## License

**This project is licensed under the MIT License.**

## Contributing

Feel free to open issues or submit pull requests if you would like to contribute to this project.


## Happy coding!


### Instructions

1. **Replace** `yourusername` and `your_api_key_here` with your GitHub username and your actual Google API key.

2. **Add a `requirements.txt` file** with the necessary packages:

   ```plaintext
   streamlit
   Pillow
   google-generativeai
   python-dotenv
   ```

3. **Ensure your .env file is correctly set up with your Google API key.**

This README.md provides an overview, installation instructions, usage details, and examples to help users get started with your project.



