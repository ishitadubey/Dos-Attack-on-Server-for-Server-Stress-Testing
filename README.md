# Dos-Attack-on-Server-for-Server-Stress-Testing

We have proposed a new system for the detection of Denial of Service(DoS) attacks. Initially, we carried out three successful attacks on a local server using 
Xerxes, Slowloris and PyLoris tools and captured the packets on Wireshark. These attack tools proved to be very powerful in flooding the server with requests due to which it stopped working. 

In the second phase, we implemented Decision Tree, Random forest and Naive Bayes algorithm on a dataset with an accuracy of 77.8%, 99.8% and 45% respectively.

Since Random Forest Regressor showed overfitting issues on the dataset used we implemented a hybrid model using the above-mentioned models. Through which we gained an accuracy of 99.82%. The attacks were successfully detected. 
