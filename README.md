# Customer-Support-Prompt-Tester
A Streamlit-based prompt-engineering project for drafting customer-support prompts and comparing tone variations.


Features


Categorize customer messages

Select response tone and length

Add approved company policy

Generate two prompt variants for comparison

Manual response-quality checklist

Guardrails against invented promises and unnecessary sensitive-data requests


Tech Stack

Python, Streamlit, prompt engineering.


Setup

pip install -r requirements.txt
streamlit run app.py

Limitations

This app creates prompts only; it does not send messages or call an AI API. The quality checklist is manually scored and cannot guarantee that a response is correct. Review customer-facing responses before sending.


Future Improvements


Optional LLM API integration

Save test cases and compare outputs

Export evaluations to CSV

Automated prompt regression tests
