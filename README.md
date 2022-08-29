# **Stock market prediction using PySpark📈**
Stock market prediction is the act of trying to determine the future value of a company stock or other financial instrument traded on an exchange. The successful prediction of a stock's future price could yield significant profit.

Using machine learning techniques I will try to 

* predict the stock value of more than 700 companies over a period of 20 years
* predict the stock value of more than 1200 companies over a period of 5 years, also using financial indicators

After having trained the models (linear regression, random forest regression), I will test them during the COVID crisis period, a major financial crisis in which even the best stock lost value, and see how they perform in comparison to a normal period. 
Finally I will try to train a neural network, and see how it compares with more linear methods.  

This notebook is divided in the following way:


1.   Configuring the environment: in this paragraph dependencies and pyspark are installed, also the configuration of how the rest of the notebook will be run is set, so make sure to check it in order to personalise your experience using this notebook.
2.   Building the datasets: here the datasets that will be later used for the training of the model are created
3.  Exploring the datasets: using Colab's tools you can visualize the datasets, and see useful insight
4. Features engineering: we can't feed the model the dataset as it is. We must create features that are useful for our prediction task.
5. Learning pipeline: in this step the actual training is done, several models are available, so that we can see which performs better
6. Hyperparameters tuning: using the appropriate hyperparameters can significally improve the performance of our models, so we try many of them and choose the best one
7. Testing the models: we choose a period and test how the model would have predicted that period
8. Plotting results: here we visualize the results of the predictions 
9. Conclusion: the project is over, what have we learned?


In order to correctly execute the notebook, follow each step sequentially, because each step depends on the previous one.
