# PDF QnA

## Overview

Welcome to **PDF QnA**! This project harnesses the power of Generative AI and Natural Language Processing (NLP) to enable users to upload any PDF document and ask questions related to its content. The tool provides precise and instant answers, revolutionizing the way we interact with and extract information from documents.

## Features

- **Seamless PDF Upload:** Effortlessly upload your PDFs for analysis.
- **AI-Driven Q&A:** Advanced NLP algorithms understand and respond to your queries accurately.
- **Time-Efficient:** Retrieve information in seconds without manual searching.
- **User-Friendly Interface:** Designed for simplicity and ease-of-use.

## How It Works

1. **Upload PDF:** Users can upload any PDF document to the platform.
2. **Ask Questions:** After the upload, users can type in their questions related to the content of the PDF.
3. **Get Answers:** The AI processes the query and provides accurate answers based on the document's content.

## Getting Started

### Prerequisites

Ensure you have the following installed:
- Python 3.8 or higher
- pip (Python package installer)
- Git

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/kotharimahesh9/PDF_Document_QnA.git
   cd PDF_Document_QnA
   ```

2. **Create a virtual environment:**
   ```bash
   python -m venv venv
   source venv/bin/activate   # On Windows use `venv\Scripts\activate`
   ```

3. **Install the required packages:**
   ```bash
   pip install -r requirements.txt
   ```

### Usage

1. **Add the API Keys:**
   ```
   GROQ_API_KEY=XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
   GOOGLE_API_KEY=XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
   ```

2. **Run the application:**
   ```bash
   streamlit run app.py
   ```

3. **Upload a PDF and start asking questions!**

## Contributing

We welcome contributions! Follow these steps to contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a Pull Request.

## Roadmap

- [ ] Improve NLP model accuracy.
- [ ] Add support for more document formats.
- [ ] Enhance UI/UX for better user experience.
- [ ] Implement user authentication and profiles.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- Special thanks to @krishnaik06.

## Contact

Feel free to reach out with any questions or feedback:

- **Author:** Mahesh Kothari
- **LinkedIn:** [Mahesh Kothari](https://www.linkedin.com/in/mahesh-kothari)
