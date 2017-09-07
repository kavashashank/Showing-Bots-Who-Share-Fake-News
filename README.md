# Methodology and Code - Showing Bots Who Share Fake News
## A twitter bot that shows how big is the role of automated bots in spreading fake news.
The bot analyzes the 'Fake News' text and finds all tweets containing this headline. It then distinguishes between users who shared and classifies them as bots or humans using the BotorNot API. Next, it determines the reach of the fake news by both bots and humans based on the number of followers each user has. The output is a tweet that contains two graphs illustrating each count.

# Methodology

1.	Pick a fake news story that has been trending on social media.

2.	Tweet to the bot @fakeNewsViral with the text "Analyze news with text |", followed by relevant text from the fake news article.

3.	Wait for the bot to respond to the tweet.

4.	Find out the number of bots participating in spreading the fake news along with the reach of the bot.
