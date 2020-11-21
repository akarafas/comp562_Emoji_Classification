# COMP 562 Emoji Classification

Group Members: Angel Karafas, Dana Rubin, and Emily Stahle

In a world where people are using emojis more and more in order to express themselves, it is important that our Natural Language Processing methods adapt to this increased emoji use. Our final project for COMP 562: Machine Learning is to run logistic regression and Naive Bayes on a dataset of tweets that contain emojis.

<strong>Our project writeup is linked in this repository under Emoji_Sentiment_Analysis.pdf</strong>

#### Before Running the Code...

Note that we are using data sourced from Twitter, so some tweets may contain explicit content. <br>
In order to run the code, you will need to download the emoji tweets dataset (https://www.kaggle.com/rexhaif/emojifydata-en?select=emojitweets-01-04-2018.txt) and place it in the project directory. <br>
You may also have to pip install the project dependencies linked in the first cell in order to run the code. To do so, open a command prompt terminal and run 'python -m pip install -U matplotlib', 'python -m pip install -U numpy', 'python -m pip install --user -U nltk', 'python -m pip install -U tweet-preprocessor'. You may not need to run all of the commands for the code to run-- once the first cell runs, all of the imports should be sorted out. <br>
The gradient descent function tends to run slowly depending on the processing speed of your computer. If the function is running slowly, lowering the number of iterations from 1500 should speed up the process. This should not significantly change the accuracy of the model. <br>
