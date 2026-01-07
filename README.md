# AI Model Testing Framework

Automated testing suite for machine learning models, following ISTQB AI Testing principles and best practices.

## 🚀 Overview

This project demonstrates comprehensive quality assurance for AI/ML models, including:

- **Performance testing** (accuracy, precision, recall, F1)
- **Bias & fairness evaluation** (demographic parity across protected groups)
- **Robustness testing** (noise injection, typos, adversarial examples)
- **Data quality validation**
- **Prediction consistency checks**

Perfect for showcasing AI testing skills in QA/QE/SDET roles.

## 🛠️ Technologies

- Python 3.11+
- pytest
- pandas, numpy
- scikit-learn
- Hugging Face Transformers
- matplotlib/seaborn (for reports)

## 📊 Example Model Under Test

Sentiment analysis model:  
`distilbert-base-uncased-finetuned-sst-2-english` (Hugging Face)

## 🚀 Quick Start

```bash
git clone https://github.com/MarcinMikula/ai-model-testing-framework.git
cd ai-model-testing-framework
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
pip install -r requirements.txt
pytest -v

