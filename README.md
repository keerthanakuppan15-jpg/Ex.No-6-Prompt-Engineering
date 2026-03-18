Ex.No.6 Development of Python Code Compatible with Multiple AI Tools

Aim: 

Write and implement Python code that integrates with multiple AI tools to automate the task of interacting with APIs, comparing outputs, and generating actionable insights with Multiple AI Tools.

Explanation:

Develop a python code that integrates multiple AI tool by interacting with their APIs.
Compare outputs from different APIs.
Analyze the response and the Output.

The aim is to understand how to request help from AI tools for tasks like writing Python code, integrating with APIs, comparing outputs, and generating actionable insights.
```
from nltk.sentiment import SentimentIntensityAnalyzer
import nltk

nltk.download('vader_lexicon')

# Simulated AI-generated text
generated_text = input("  ")
print("Generated Review:\n")
print(generated_text)

# Sentiment analysis
sia = SentimentIntensityAnalyzer()
sentiment = sia.polarity_scores(generated_text)

print("\nSentiment Analysis:")
print(sentiment)
```
Output:

<img width="582" height="408" alt="Screenshot 2026-03-18 092638" src="https://github.com/user-attachments/assets/7b77b5fb-67ad-4d60-9c92-7bf174e98a2d" />

<img width="731" height="422" alt="Screenshot 2026-03-18 092713" src="https://github.com/user-attachments/assets/f368b59a-0a91-4c1a-a9a5-c69dcec9a60c" />

Result:

The code executed succcessfully.
