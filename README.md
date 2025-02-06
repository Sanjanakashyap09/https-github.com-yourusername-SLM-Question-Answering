# 📚 Small Language Model for Question Answering

## 🔹 Overview
This project involves building a **Small Language Model (SLM)** that can take a book as context and accurately answer questions based on its content. The model extracts relevant information and provides responses by analyzing textual data.

## 🔹 Features
- Parses and processes book text from **HTML/Wikipedia pages**
- Splits large text into manageable **chunks**
- Utilizes a **pre-trained DistilBERT model** for question answering
- Implements a **custom answer retrieval function** for accuracy
- Interactive **CLI-based Q&A system**

## 🔹 Installation
```bash
pip install transformers beautifulsoup4 requests
```

## 🔹 Usage
1. **Upload a book file** (HTML format) in Google Colab
2. **Extract and clean text** using BeautifulSoup
3. **Split text into smaller chunks** for processing
4. **Run the Q&A model** to get responses
5. **Ask questions interactively** via CLI

## 🔹 Running the Model
Run the following in a Colab or Python environment:
```python
from google.colab import files
uploaded = files.upload()
```
Then execute the scripts to process data and answer questions.

## 🔹 Example Output
```bash
Ask a question: Who is Romeo?
Answer: Romeo is the male protagonist in Shakespeare’s "Romeo and Juliet."
```

## 🔹 Repository Structure
```
📂 SLM_Question_Answering
 ├── 📄 README.md  # Project documentation
 ├── 📂 data       # Contains book files (HTML/text)
 ├── 📂 src        # Main scripts for text processing and model execution
 ├── 📂 models     # Pre-trained DistilBERT model
 ├── 📄 requirements.txt  # Dependencies
```

## 🔹 Contributing
Feel free to fork this repository and enhance the project. Contributions are welcome!

## 🔹 License
This project is open-source and available under the **MIT License**.
