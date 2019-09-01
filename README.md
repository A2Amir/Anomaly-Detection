# Anomaly-Detection
How to detect anomalies in a dataset
Anomaly detection has shown to be a valuable tool in a variety of application domains, e.g. detecting credit card fraud, network intrusion and sensor malfunction.

Anomalies are deﬁned as patterns in data that donot conform to expected or normal behaviour. The problem of ﬁnding such patterns is referred to as anomaly detection. Anomaly detection can be applied to any type of data,binary,discrete or continuous, univariate or multivariate.

 ## Types of anomalies
 
 
 There are mainly three types of anomalies,  
 
 
* point anomalies (global anomaly ):Point Anomalies If a single point deviates from the considered normal pattern it is referred to as a point anomaly. This is the simplest form of an anomaly and is the most researched form. An example of a point anomaly is if a process value suddenly is very low or high. An illustration of this is given below Figure, where the anomaly is marked in red.


<p align="center">
<img src="./img/1.jpg" alt="point anomalies (global anomaly )" />
<p align="center">

* sequential anomalies:If a sequence or collection of points is anomalous with respect to the rest of the data, in the following figure, the data points marked in green have collectively formed a region which substantially deviates from the rest of the data points.
<p align="center">
<img src="./img/2.jpg" alt="sequential anomalies" />
<p align="center">


* contextual anomalies:If a point or a sequence of points are considered as an anomaly with respect to its local neighbourhood, but not otherwise, it is referred to as a contextual anomaly.
Consider today’s temperature to be +20 degrees centigrade and we are in Alaska. Is the temperature normal today? This is a highly relative question and demands for more information to be concluded with an answer. Information about the season, location

 <p align="center">
<img src="./img/3.jpg" alt="sequential anomalies" />
<p align="center">
 Notice:The values have not fallen outside the normal global bounds, but there are indeed abnormal points (highlighted 
in orange) when compared to the seasonality.

 ## Anomaly detection Methods:
 
The anomaly detection problem has been investigated in many diﬀerent ﬁelds of mathematics and with diﬀerent application areas. Anomaly detection was ﬁrst research in the ﬁeld of statistics as outlier detection. Lately the statistical approaches have been expanded by machine learning methods. Hodge and Austin [1] gives an extensive survey of these anomaly detection techniques. Recently other approaches have been explored such as neural networks presented by Markou [2]  and methods for cyber-intrusion detection.

 [1]: Victoria J. Hodge and Jim Austin. “A Survey of Outlier Detection Methodologies”. English. In: Artiﬁcial Intelligence Review 22.2 (2004), pp. 85–126.
 [2]: M. Markou. “Novelty detection: a review—part 2: neural network based approaches”. English. In: Signal Processing 83.12 (2003), pp. 2499–2521.
