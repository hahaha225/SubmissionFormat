Submission:
File structure

[SubmissionFormat.zip](https://internalapp.nptel.ac.in/contest/reference_docs/submissionFormat.zip) contains two python source files main.py and predictor.py.
(The lower the points, better is the prediction outcome).
predictor.py: In the sample format, predictor.py contains a definition predictRuns().
main.py: This is a test file. It is recommended to NOT edit this file. Once you implement the predictor.py, you can test the functionality of your implementation.

How to implement:

You can customize the implementation of predictRuns() in predictor.py. A list of recommended python based ML packages can be found below. If you are making a model, then create your training script separately and train it against the training data given on the contest page. At the end of the training, save your model as an appropriate file. In predictRun, load your model and do the necessary computation by feeding the input. You can customize your implementation by adding more classes and definitions to support predictRuns. The expected return value is an integer
Let model.xyz be the saved ML model, then save it as a sibling document to predictor.py. Whenever the model is loaded, use the relative path to read the file. 