# Spam Mail Detection

## Overview

This project aims to develop a spam mail detection system using machine learning techniques. The system classifies emails as "spam" or "ham" (non-spam) based on features extracted from the email content. We utilize the `mail_data.csv` dataset, which contains labeled email messages.

## Dataset

The dataset `mail_data.csv` includes the following columns:

- **v1**: Label (spam or ham)
- **v2**: Email content

### Example Data

| v1   | v2                                 |
|------|------------------------------------|
| ham  | Hey, how are you?                  |
| spam | Congratulations! You've won a prize! |

## Objectives

- Preprocess the email data for analysis.
- Extract features using techniques like TF-IDF or Count Vectorization.
- Train machine learning models to classify emails.
- Evaluate model performance using metrics such as accuracy, precision, recall, and F1-score.

## Technologies Used

- **Python**
- **Libraries**: Pandas, Scikit-learn, NLTK, Matplotlib, Seaborn

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/tusharkrishna27/spam-mail-detection.git
   cd spam-mail-detection
