This project aims to predict the stock market based on the sentiment of the people . The project is divided into several steps 
Web scraping here i scraped the chats on telegram and it code are web_scraping-checkpoint and through this we obtained stock_news_market_stock_messages (3).csv
The scraped data obtained is then preprocessed which includes handling emoji, stop words ,handling short forms handling missing values and we get data2_cleaned and code is in preprocessing_text.ipynb
Now we use vaderSentiment module to find the overall sentiment of each message . I have given different weightage to different words certain words are really positive for stocks while others moderately postive and few and negative and few are extremely negative others are neutral.The code is in sentiment.ipynb and finally we get stock_data6 
In NLP_updated_checkpoint i created a vectors of these messages for prediction using count vectorizer and used random forest algorithm for the sentiment analysis . Though the accuracy is 85 percent i will try to improve it 

