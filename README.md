# MLOps_task_for_MLDevSecOps
This project helps us to block someone from triggering our webpages again and again in a suspicious manner.
Here, we have implemented the concepts of ML, DevOps and little bit security.
We have firstly made a webpage and then triggered it with different systems to generate logs.
Then we have created ML code using KMeans clustering algorithm to form clusters of the dataset so that we can come to know that which IP is lying in which cluster and which IPs we are required to block.
Then we have created a jenkins job.
In this job, we have launched a docker conatiner having python and some of ML libraries installed in it.
After that we will run the ML code and we will get all those IPs which we are required to block as our program output.
Finally, we will run a command to block those IPs.
This project is explained properly in the document in this repo "MLOps_task_for_MLDevSecOps".
