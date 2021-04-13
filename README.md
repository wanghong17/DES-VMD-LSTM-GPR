# DES-VMD-LSTM-GPR
# Guizhou university- Hong Wang 
# hwang23@gzu.edu.cn
# The all code are run in Python version 3.7, and the main application packages inlcude Scikit-learn 0.22.1, Keras 2.2.4, Minepy 1.2.4 and Statsmodels 0.11.1
# Instructions
1、Using double exponential smoothing (DES) method to predict the landslide trend displacement based on Excel；
2、The VMD module is used to decompose the residual periodic displacement into k components，then, based on SPSS 21.0 software, the correlation between each component and the original periodic displacement is analyzed, and the optimal component number k is determined according to p value；
3、The MIC technique is used to select the optimal combination of input features for the periodic displacement prediction model (LSTM/SVR/BP/GRU);
4、The LSTM/SVR/BP/GRU methods are used to predict K components, and then the periodic displacement prediction results can be obtained by summation;
5、The trend displacement and periodic displacement prediction results are summed to obtain the first cumulative displacement prediction results;
6、The GPR module is used to perform the second landslide displacement prediction to obtain the point prediction, interval prediction and probability prediction results.
