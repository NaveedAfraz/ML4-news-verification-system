# ML4 News Verification System

A machine learning model that detects fake news using NLP and classification. Processes text data to identify misleading content with scikit-learn and NLTK.

## 📊 Features
- Text preprocessing with NLTK
- TF-IDF vectorization
- Logistic Regression classifier
- Performance metrics

## 🚀 Getting Started

### Prerequisites
- Python 3.8+
- Required packages: `pandas`, `numpy`, `scikit-learn`, `nltk`

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/NaveedAfraz/ML4-news-verification-system.git
   cd ML4-news-verification-system
   ```
2. Set up a virtual environment:
   ```bash
   python -m venv venv
   .\venv\Scripts\activate  # On Windows
   source venv/bin/activate  # On macOS/Linux
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the Jupyter notebook:
   ```bash
   jupyter notebook Project_4_Fake_News/fakenews.ipynb
   ```

## 📁 Project Structure
```
├── Project_4_Fake_News/
│   ├── fakenews.ipynb    # Main Jupyter notebook
│   └── train.csv         # Training dataset
├── README.md            # This file
└── requirements.txt     # Project dependencies
```

## 🤝 Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License
This project is licensed under the MIT License - see the LICENSE file for details.
