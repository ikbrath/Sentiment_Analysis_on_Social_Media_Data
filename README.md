# Sentiment Analysis on Social Media Data

This project performs sentiment analysis on social media data, specifically Twitter, to analyze public opinion on various topics. The project uses **Tweepy** to collect tweets and **VADER Sentiment Analysis** to classify the sentiment of each tweet as positive, negative, or neutral.

## Libraries and Tools Used:
- **Tweepy**: To collect data from Twitter's API.
- **VADER (Valence Aware Dictionary and sEntiment Reasoner)**: For sentiment analysis of text data.
- **Matplotlib**: To visualize sentiment distribution.
- **Pandas**: For data manipulation.
- **JSON**: For storing raw data from Twitter.

## Steps to Run:
1. **Install Dependencies**: 
   - Run `pip install tweepy pandas matplotlib vaderSentiment`
   
2. **Set Up Twitter API Access**:
   - Create a Twitter Developer Account at [Twitter Developer](https://developer.twitter.com/).
   - Generate API keys and access tokens.
   - Replace the placeholders in the script with your own keys.

3. **Run the Script**:
   - After setting up your API keys, you can run the script to start collecting tweets and perform sentiment analysis.

## How It Works:
1. The script collects tweets using **Tweepy** based on a specified hashtag or keyword.
2. It then performs sentiment analysis on each tweet using **VADER**.
3. The results are visualized in a bar chart, showing the distribution of sentiment (positive, neutral, negative).

## Example Output:
The analysis will output a pie chart showing the distribution of tweet sentiment and a bar chart displaying the sentiment count.

### Requirements:
- Python 3.x
- Twitter Developer API Keys

## License:
This project is open source and available under the MIT License.

## Author:
Ikbar 

