# LifetimeDeepLearning

This deep learning project is built to predict the lifetime of LED.

The DNN model is built with the following methods. In the feedforward process, ReLU is used as activation function and drop out as regularization method. In the backpropagation process, L1 norm is used as regularization method and RMSprop as optimization method. Hiding the names of LED is also a method being used in an early stage as a regularization method.

======================================================================

"LED_re_data_engineering.ipynb" - Data pre-processing

"Prediction.ipynb" - DNN model

"LED_try_optimizer_regularizer.ipynb" - compare the performance of SGD, Adam, Nadam and RMSprop for optimizer, L1 and L2 for regularizer

======================================================================

Results shown in "LEDLifetimePrediction.pdf" P.24-43.

Created by YEUNG Tung Yan
