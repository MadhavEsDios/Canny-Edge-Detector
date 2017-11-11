# Canny-Edge-Detector
An easy to understand implementation of the Canny Edge Detection Algorithm in python

Please refer to this excellent link to better understand the algorithm : "http://justin-liang.com/tutorials/canny/"



Important Points:
- I have used a relatively slow iterative approach to perform the function of Double Thresholding Hysterisis,
  a better and time-saving alternative is to use a recursive algorithm which tracks the edges.
- The value of Sigma to implement Gaussian Blur is image specific, different values can be tested to see which give the best estimate of edges.
- The ratio of the thresholds is again another variable, but the ones that I have used in the code give pretty good estimates for any particular image.
- Non Maxima Suppression with Interpolation although being computationally expensive, gives excellent estimates and is better tha NMS without interpolation
