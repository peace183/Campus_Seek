#4. System Architecture


In this chapter, try to describe the overall view of the system:
* Main components needed by the system to "serve" the end user
  * A diagram with boxes is a good way for representing these
* The idea here is to try to reason out the logical subcomponents of the system


##4.1. High-level overview of the system
CampusSeek is a mobile app which act as a client. The client will connect to the server to feed the map data and all user data from the database. The server-side module contain map data of the campus and store a database of all users from all group. Administrator(s) are created by default, Student and Staff accounts are imported from the Metropolia database so everyone in the campus get an easy access to the network, additional user account can be registered by outsider (guest) as needed. Each mobile client will connect and represent one user in the database. A user will get the privilege according to the detailed use cases.


##4.2. Main modules and their functions represented
[Awaiting reply from Olli on how to complete this section]



![alt text](https://raw.githubusercontent.com/peace183/Campus_Seek/master/Campus_Seek_Architecture.png "Campus_Seek Architecture")

Fig. 1. Architecture of the CampusSeek



**[Need to add context model this below is a draft ]**




![alt text](https://raw.githubusercontent.com/peace183/Campus_Seek/master/Context_model_Draft.png "Campus_Seek Contextmodel")


