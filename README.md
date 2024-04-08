# NLP

In order to run our code you can either run the Jupyter Notebook or download the Python code.
The Notebook can be run on your local device, however, it will need to be run using your GPU. If you run the code on your CPU, it will notify you that you don't have the correct accelerator installed, even though this is done at the beginning of the code. Be aware that when used locally, it will take a very long time to complete.
The Python code can also be run locally, but it's recommended to use a device such as Hábrók, as running the code will take a very long time.
Hábrók may experience difficulties in computing the metric scores. If this is the case, you can download the saved model after training is done and produce the metric scores by loading the saved model in your code.\
There is still room for improvement. It might be worth it to perform a hyperparamter search to see if it's possible to produce a better result.
