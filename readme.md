In this [experiment](Sentence_Emoji_Generator_with_LSTM.ipynb), I built and trained a classifier using an LSTM, which would read a short sentence and determines the best emoji to go with that sentence, based on the starting code, instructions, and utility functions from the [Convolutional Neural Networks](https://coursera.org/learn/convolutional-neural-networks) course (by DeepLearning.AI on Coursera).

Please input sentences in this cell and run the prediction to see the results:
```
x_test = np.array(['I cannot play baseball today', 
                   'My homework is just too hard',
                   'Joey is just hilarious',
                   'I am sorry baby! I will arrive on time!',
                   'Thanks for writing to me',
                   'Love your dishes - best cake ever!',
                   'I miss you. When are you coming back?'])
```

The emojis returned seem to fit the sentences quite well!

+ I cannot play baseball today ⚾
+ My homework is just too hard 😞
+ Joey is just hilarious 😄
+ I am sorry baby! I will arrive on time! 😞
+ Thanks for writing to me 😄
+ Love your dishes - best cake ever! 🍴
+ I miss you. When are you coming back? ❤️

The LSTM architecture is as follows (image from the Coursera assignment):

![emojifier-v2.png](images%2Femojifier-v2.png)