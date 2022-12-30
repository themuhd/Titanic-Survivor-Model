

<h3>Change Output and Input Directories to match system</h3>

<h1>Overview</h1>
The data has been split into two groups:

training set (train.csv)</br>
test set (test.csv)</br>
<b>The training set</b> is used to build the machine learning models. For the training set, we provide the outcome (also known as the “ground truth”) for each passenger. The model is based on “features” like passengers’ gender and class. You can also use feature engineering to create new features.

<b>The test set</b> should be used to see how well your model performs on unseen data. For the test set, we do not provide the ground truth for each passenger. It is your job to predict these outcomes. For each passenger in the test set, use the model you trained to predict whether or not they survived the sinking of the Titanic.

Also included is the gender_submission.csv, a set of predictions that assume all and only female passengers survive, as an example of what a submission file should look like.<br/>
The <b>Submission</b> file that includes the model predictions is also included