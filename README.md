# sarcasm-detection

This project uses the dataset "News Headlines Dataset for Sarcasm Detection", originally found on <a src="https://www.kaggle.com/datasets/rmisra/news-headlines-dataset-for-sarcasm-detection/code">Kaggle</a>

As you can observe on the script file, I used Google Colab, which is why I did not upload the dataset itself to github and instead, downloaded it to a temp folder.

The dataset is in Json format, which I had to transform into a dictionary and then split it into train and test sets

In this project I used **Tensorflow** and **Keras** to create a Neural Network and used our data to train and test it.

Once the model was done, I took the time to create some of my own short phrases and used the model to try and detect if they were sarcastic or not.

The result is interesting as some phrases were rightly appointed as sarcastic, but others were not, which might mean that the model needs training, or I am bad at sarcasm.

Anyway, feel free to look at the code, write your own phrases and check what the model says.
