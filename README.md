# MNIST-CNN-99.75

![hist](http://playagricola.com/Kaggle/histBoth2.png)  
  
The code here achieves 99.78% classification accuracy on the famous [MNIST](http://yann.lecun.com/exdb/mnist/) handwritten digits dataset. Currently (as of Sept 2018), this code achieves the best accuracy in Kaggle's MNIST competition [here](https://www.kaggle.com/cdeotte/25-million-images-0-99757-mnist). And this code's single CNN accuracy of 99.77% exceeds the best reported accuracy on Wikipedia [here](https://en.wikipedia.org/wiki/MNIST_database) (which is only 99.74%).  
  
To assess performance, the Python code in this repository was executed 100 times using TensorFlow (version 1.7.0-rc1) on Nvidia Tesla K80 GPUs. (Average time per run was 4 hours.) During each execution, 15 individual CNNs were trained (35 epochs each), and 1 ensemble of fifteen CNNs was assembled. Therefore in total, 1500 individual CNNs were trained and 100 ensembles of fifteen CNNs were trained.  
  
The maximum accuracy of an individual CNN was 99.77% with average accuracy 99.65% and standard deviation 0.045. The maximum accuracy of an ensemble of fifteen CNNs was 99.78% with average accuracy 99.74% and standard deviation 0.02. Above are histograms of accuracy.
