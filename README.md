# ORADS
The two classifier has been given, one for detecting anomalies in driving state and other in stationary state. 
To use the classifier, new features must be added to the test data (feature extraction) as given in the paper.
These new features are: P_CAN_ID (previous CAN ID), N_CAN_ID (next CAN ID), TimeInterval and TimePeriod.
After finally preprocessed the test data, both the classifier can be used directly to detect anomalies.
