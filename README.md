📄 Abstract Summarizer

Abstract Summarizer is a powerful NLP-based tool that condenses long pieces of text into shorter, meaningful summaries while preserving key information and overall context.
It leverages modern deep learning models to generate high-quality extractive and abstractive summaries.

📌 Table of Contents

Features

Installation

Usage

Model Architecture

Dataset

Results

Contributing

🚀 Features

✅ Extractive Summarization
Selects the most important sentences directly from the original text.

✅ Abstractive Summarization
Generates new, human-like summary sentences capturing the main ideas.

✅ Multiple Input Formats

Plain text files

PDF documents

Web pages

✅ User-Friendly Interface

Command-line interface (CLI)

Web-based UI

⚙️ Installation
1️⃣ Clone the repository
git clone https://github.com/sandynaukar/Abstract-Summarizer.git

2️⃣ Navigate to project directory
cd Abstract-Summarizer

3️⃣ Create virtual environment
python -m venv venv

4️⃣ Activate environment

Windows

venv\Scripts\activate


macOS/Linux

source venv/bin/activate

5️⃣ Install dependencies
pip install -r requirements.txt

🧠 Usage
▶ Command Line Interface

Summarize a text file:

python summarize.py --input path/to/your/textfile.txt --output summary.txt

🌐 Web Interface

Run:

python app.py


Open browser:

http://localhost:5000

🏗 Model Architecture

This project uses BART (Bidirectional and Auto-Regressive Transformers) from the Hugging Face Transformers library.

Why BART?

Designed for sequence-to-sequence tasks

Excellent for text generation & summarization

Combines encoder-decoder transformer architecture

📚 Dataset

The model was fine-tuned on the CNN/Daily Mail Dataset, containing:

📰 300,000+ news articles

✍ Human-written summaries

Widely used benchmark for summarization research.

📊 Results

Performance evaluated using ROUGE metrics:

Metric	Score
ROUGE-1	44.16
ROUGE-2	21.28
ROUGE-L	40.90

👉 Indicates strong content retention and fluent summaries.

🤝 Contributing

Contributions are welcome!

Fork the repository

Create a feature branch

Submit a pull request

Feel free to improve models, UI, datasets, or performance.
