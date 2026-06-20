# Grammar Correction System using NLP and Transformers

An AI-powered Grammar Correction System built using Natural Language Processing (NLP), Transformer Models, and HappyTransformer. The application automatically detects and corrects grammatical mistakes in user-provided text through an interactive web interface.

---

## ⭐ Features

✔️ Detects and corrects grammatical errors in English text

✔️ Uses a pre-trained T5 Transformer model for grammar correction

✔️ Supports sentence and paragraph-level correction

✔️ Interactive web interface built with Gradio

✔️ Easy-to-use and beginner-friendly implementation

✔️ Can be extended for spell checking and writing assistance

---

## 🧠 About the Project

Grammar correction is an important NLP task that improves the quality, readability, and professionalism of written text. This project leverages the **vennify/t5-base-grammar-correction** model through HappyTransformer to automatically identify and correct grammatical mistakes.

The system accepts user input, processes it using a Transformer-based sequence-to-sequence model, and generates grammatically corrected text as output.

---

## 📦 Tech Stack

| Component               | Technology                             |
| ----------------------- | -------------------------------------- |
| Programming Language    | Python                                 |
| NLP Framework           | HappyTransformer                       |
| Transformer Model       | T5 (Text-to-Text Transfer Transformer) |
| Deep Learning Backend   | PyTorch                                |
| Interface               | Gradio                                 |
| Development Environment | Google Colab / Jupyter Notebook        |

---

## 🚀 Installation

### Clone the Repository

```bash
git clone https://github.com/yourusername/Grammar-Correction-System.git
cd Grammar-Correction-System
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Running the Application

### Run the Gradio Web Application

```bash
python app.py
```

After running the application, Gradio will generate a local URL where you can access the Grammar Correction System through your browser.

---

## 📖 Usage

1. Enter a sentence or paragraph containing grammatical errors.
2. Click the submit button.
3. The system processes the text using the T5 model.
4. View the corrected output instantly.

---

## 🔍 Example

### Input

```text
This sentences has has bads grammar.
```

### Output

```text
This sentence has bad grammar.
```

---

## 📂 Project Structure

```text
Grammar-Correction-System/
│
├── app.py
├── grammar_correction.ipynb
├── requirements.txt
├── README.md
├── screenshots/
│   └── demo.png
│
└── .gitignore
```

---

## 🔮 Future Enhancements

* Multi-language grammar correction
* Spell checking integration
* Writing style suggestions
* Grammar error highlighting
* Fine-tuning on custom datasets
* Deployment on cloud platforms

---

## 📊 Applications

* Educational platforms
* Writing assistants
* Content creation tools
* Student learning systems
* Automated document proofreading

---

## 🙌 Contributing

Contributions are welcome.

1. Fork the repository
2. Create a feature branch

```bash
git checkout -b feature-name
```

3. Commit your changes

```bash
git commit -m "Add new feature"
```

4. Push to GitHub

```bash
git push origin feature-name
```

5. Open a Pull Request

---

## 📝 License

This project is available under the MIT License.

---

## 🤝 Acknowledgements

* HappyTransformer
* Hugging Face Transformers
* PyTorch
* Gradio
* T5 Research Team

---

## 👨‍💻 Author

**Greeshma Garikina**

B.Tech – Artificial Intelligence & Machine Learning

Passionate about NLP, Generative AI, LLMS, System Design , and Intelligent Systems.

