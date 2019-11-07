# A text classification problem

Given a (non public) dataset with real social media comments from the page of an online store, the goal was to create a model to detect harmful comments, while applying some NLP techniques (using nltk and Gensim packages; emoji too 😛💥).

The data had the comments' text, detected language of the comment, its translation to English, the indication of the comment being harmful or not and the type of harmful comment.

Due to ⏳ issues, I decided to approach the problem in the most practical way I could, like choosing to work on the English translation of the comments only or limiting it to the harmful/not-harmful binary label.

It's an old exercise, but eventually I'll pick it up again to improve results and try different approaches.
For now, two different ones: Random Forest and a Bidirectional LSTM approach⬅️➡️.

