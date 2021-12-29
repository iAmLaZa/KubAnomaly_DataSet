**KubAnomaly_DataSet and model**

This project is used to detect some anomaly behavior in container.
We offer program and data set used in our paper

"KubAnomaly: Anomaly detection for the Docker
orchestration platform with neural network approaches"

[paper link](https://onlinelibrary.wiley.com/doi/pdf/10.1002/eng2.12080)


**Usage**

1. create a virtual environment 
2. pip install -r requirements.txt
3. python KubAnomaly_Paper.py

then you can reproduce the experiment result 

P.S the result may have a slight different compared to our paper. 
    We think maybe it is because of package versions problem
 
 **KubAnomaly_DataSet and model**    
 
 This agent is used to collect some container logs and send them back to center
 
 **Requirements**    
 
 gradle 5.6.4
 oracle java 1.8
 kotlin 1.3
 
 **Usage**    
 
 Using gradle build fatjar to get execuable jar
