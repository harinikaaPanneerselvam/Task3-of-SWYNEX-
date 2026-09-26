# Task 3 – Intelligent Feature

## Smart Support Ticket Classifier

This project adds an intelligent feature that automatically classifies a customer support message into one of four categories:

- Technical Issue
- Billing
- Account
- General

It also includes confidence scoring, input validation, error handling, evaluation examples, failure cases, and a simple Streamlit interface.

## Project Structure

```text
intelligent_feature_task3/
├── app.py
├── classifier.py
├── evaluate.py
├── requirements.txt
├── evaluation_examples.json
└── README.md
```

## How to Run

1. Install Python 3.9+.
2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Start the interface:

```bash
streamlit run app.py
```

## Intelligent Feature

The classifier uses TF-IDF text features and Logistic Regression to identify the intent of a support message.

Example:

Input:
> I was charged twice for my subscription.

Output:
> Billing

The application also displays a confidence score.

## Error Handling

The app handles:
- Empty input
- Very short input
- Model prediction errors
- Unexpected application errors

## Evaluation

The `evaluate.py` file evaluates the model on example test cases and prints accuracy and a classification report.

## Failure Cases

The model may struggle with:
- Very short messages such as "Help"
- Messages containing multiple unrelated issues
- Sarcasm or unclear language
- New topics that are not represented in the training examples

## Future Improvements

- Use a larger real-world dataset.
- Add more support categories.
- Use a transformer/LLM model.
- Add multilingual support.
- Store user feedback for continuous evaluation.
