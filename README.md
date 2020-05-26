# Reddi2Listen
### Empowering a data-driven approach to student mental wellness initiatives
Reddi2Listen highlights student mental health issues by listening to what they have to say - directly from the source. One of the most popular social media platforms for posts related to mental health issues is reddit, due to the anonymity and specificity of the community.
Using a reddit bot and PRAW, posts were scraped from /r/uwaterloo, the Canadian university subreddit with the largest number of subscribers. Sentiment analysis was performed on the data using Microsoft Azure Cognitive Services API to in order to collects posts written in a negative tone. Using keyword extraction, the most commonly used phrases were identified.

### Getting Started
From the command prompt, navigate to a new directory and clone the Reddi2Listen repository.

`cd <your/path/here>`

`git clone https://github.com/Klting/Reddi2Listen.git`

### Built With
- pandas - Python Data Analysis Library
- Text Analytics - Microsoft Azure AI service
- PRAW - Python Reddit API Wrapper
