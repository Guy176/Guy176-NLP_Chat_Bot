# Project Overview

## Intents
- **book_flight**
- **change_flight**
- **cancel_flight**

If the user's intent doesn't match any of these three, it's classified as **'unknown'**.

## States
- **0 : start**
- **1 : book_flight**
- **2 : change_flight**
- **3 : cancel_flight**
- **4 : flight_destination**
- **5 : change_destination**
- **6 : reason for cancellation**
- **7 : flight dates**

# Methodology

- **Feature Extraction:** Utilized TF-IDF for feature extraction.
- **Classification Model:** Employed Random Forest Classifier for intent classification.
- **Language Processing:** Leveraged the `en_core_Ib_sm` spaCy model.
- **Sentiment Analysis:** Integrated the `SpacyTextBlob` pipeline for sentiment analysis, which includes polarity scores from user input.
