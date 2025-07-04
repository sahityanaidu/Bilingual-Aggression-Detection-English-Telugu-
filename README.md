# Aggression-Identification-English-Telugu

This repository contains two Jupyter notebooks and accompanying data for a multilingual aggression identification model in English and Telugu.

## 📂 Project Structure

\`\`\`
.
├── agr_en_train.csv

├── telugu_val_separated_tab.csv

├── NLP_PROJECT_eng.ipynb       # English aggression model

├── nlp_project_tel.ipynb       # Telugu aggression model

└── NLP_REPORT.pdf              # Final project report
\`\`\`

## 🚀 Setup & Installation

1. **Clone the repo**  
   \`\`\`bash
   git clone https://github.com/<your-username>/<repo-name>.git
   cd <repo-name>
   \`\`\`

2. **Create a virtual environment** (optional, but recommended)  
   \`\`\`bash
   python3 -m venv venv
   source venv/bin/activate      # Linux / macOS
   venv\\Scripts\\activate       # Windows
   \`\`\`

3. **Install dependencies**  
   \`\`\`bash
   pip install --upgrade pip
   pip install -r requirements.txt
   \`\`\`

4. **Download NLTK & Stanza resources**  
   In a Python shell or at the top of each notebook, run:
   \`\`\`python
   import nltk
   nltk.download('punkt')
   nltk.download('stopwords')

   import stanza
   stanza.download('en')
   stanza.download('te')
   \`\`\`

## 🔍 Usage

- **English notebook**  
  Open and run \`NLP_PROJECT_eng.ipynb\` to preprocess English data, train your model on \`agr_en_train.csv\`, and evaluate performance.

- **Telugu notebook**  
  Open and run \`nlp_project_tel.ipynb\` to preprocess Telugu data, use transliteration and translation pipelines, train on \`telugu_val_separated_tab.csv\`, and evaluate.

- **Report**  
  See \`NLP_REPORT.pdf\` for detailed methodology, experiments, results, and conclusions.

## 🤝 Contributing

Feel free to open issues or submit pull requests for improvements, additional language support, or bug fixes.

