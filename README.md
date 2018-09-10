# MNIST-CNN-99.75

![hist](http://playagricola.com/Kaggle/histBoth.png)  
  
The Python code in this repository was executed 100 times using TensorFlow (version 1.7.0-rc1) on an Nvidia Tesla K80 GPU. Average time per run was 4 hours. During each execution, 15 individual CNNs were trained 35 epochs each, and 1 ensemble of fifteen CNNs was assembled. Therefore in total, 1500 individual CNNs were trained and 100 ensembles of fifteen CNNs were trained.  
  
The average accuracy of an individual CNN was 99.65% with standard deviation 0.045. The average accuracy of an ensemble of fifteen CNNs was 99.74% with standard deviation 0.02. The maximum accuracy of an individual CNN was 99.77%, and the maximum accuracy of an ensemble was 99.78%. Above are histograms of accuracy.
