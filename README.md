# fake-news-ai-fact-checker-pro
Hybrid AI Fact-Checker: A real-time news verification system combining Machine Learning (NLTK + Scikit-Learn) with live web searching (DuckDuckGo API). Built with Streamlit.
This project is a Hybrid Intelligence tool designed to detect misinformation. Unlike traditional detectors that only analyze text patterns, this system performs a dual-layer verification:

Linguistic Analysis: Uses a Random Forest model trained on the WELFake dataset to identify "fake news" writing styles.

Live Fact-Checking: Leverages the DuckDuckGo API to scan the live web for official news reports matching the claim.

Built with: Python, Streamlit, Scikit-Learn, NLTK, and Pandas.
