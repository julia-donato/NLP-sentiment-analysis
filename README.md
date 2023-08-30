# NLP Mini Project: Sentiment Analysis on Amazon Fashion Reviews 🛍️

Perform sentiment analysis on a set of Amazon fashion product reviews using this script. Dive into product sentiments, analyze feedback, and get clear insights on user experiences.

## Dataset 📊

The data used for this project is sourced from [UCSD datasets](https://cseweb.ucsd.edu/~jmcauley/datasets.html#amazon_reviews) and is presented in JSON format.

## How It Works ⚙️

1. **Initialization:** I start by importing the essential packages and libraries. I've integrated spaCy for lemmatization, aiming to reduce words to their base form, streamlining the analysis.
2. **Function Mapping:** I then create a function to map the parts of speech for compatibility with SentiWordNet.
3. **Data Processing:** After opening the dataset, I process 100 reviews, encompassing:
    - Tokenization
    - POS Tagging
    - Sentiment Score Analysis
    - Determination of Overall Sentiment for each review.
4. **Results:** The findings are not just displayed, but also saved meticulously in a `.csv` file for future reference.

## Example 🌟
_Place your example here._

## Citation 📝

```
Jianmo Ni, Jiacheng Li, Julian McAuley
Empirical Methods in Natural Language Processing (EMNLP), 2019
```

Give your feedback analysis a new edge with the integration of NLP! Feel free to contribute or raise any issues.

---

_Note: This README is optimized for GitHub and aims to provide clarity and attractiveness to potential users or contributors to the repository._
