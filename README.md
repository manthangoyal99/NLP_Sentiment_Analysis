EE626
Recommendation Engine

Krishn Kanhaiya Tikmani
Abhishek Bajpai
Mujahid Bari
Akshat Purohit


Files and their Content Summary

Fine Grained Sentiment Analysis Part

In FineGrainedSenti Folder

- classifier.py - It containes the classes that are defined for logistic regression and svm for training and testing purpose.

- plotter.py - It contains the code for plotting the confusion matrix.

- predictor.py - It consist of the code for getting results, accuracy, f1_score, confusion matrix for all the classifiers.

- lime_explainer.py - It consist of the classes of both classifiers which are used for deploying using the Flask app. It also contains the code for LIME explanation of text.

- app.py - The backend flask code for running the website

- static and template folder consist of the HTML and CSS file for the website 

- data folder contains the SST-5 training, testing and developing data used for the analysis

- requirements.txt - dependecies of the code for fine grained sentiment analysis

To run the web app on local network

First, set up virtual environment and install from ```requirements.txt```:

    python3 -m venv venv
    source venv/bin/activate
    pip3 install -r requirements.txt

Then simply,

Run the file `app.py` and then enter a sentence, choose a type of classifier and click on the button `Explain results!`. We can then observe the features (i.e. words or tokens) that contributed to the classifier predicting a particular class label. 

Now for running the file predictor.py to get the confusion matrix, f1_score and accuracy

In terminal write

python3 predictor.py --method logistic svm


Movie Recommender Part

In the recommendation folder in codes&results

- movie_recommender_system.ipynb and movie_recommender_system.py is the code file
- the result is stored as Results.pdf file with cells runned
- Data Folder consist of the used data for this part




