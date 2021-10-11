# indoor localization

Indoor Positioning Systems aims to detect the position of user or device by using Access Points’ signal also called “Wi-Fi fingerprint”.

Indoor Positioning Systems aims to detect the position of user or device by using Access Points’ signal also called “Wi-Fi fingerprint”. Each WiFi fingerprint can be characterized by the detected Wireless Access Points (WAPs) and the corresponding Received Signal Strength Intensity (RSSI). Then the coordinates (latitude, longitude, building number & floor) and Building ID are provided as the attributes to be predicted.

The UJIIndoorLoc database covers three buildings of Universitat Jaume I with 4 or more floors and almost 110.000m2. It can be used for classification, e.g. actual building and floor identification, or regression, e.g. actual longitude and latitude estimation. The database consists of 19937 training/reference records (trainingData.csv file) and 1111 validation/test records (validationData.csv file).

This notebook focuses on setup of "position esitmation algorithm" illustrated in diagram below, by performing regressioon tasks and classifcation tasks.

![image](image.png "image")
