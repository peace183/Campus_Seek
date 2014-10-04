#4. System Architecture

##4.1. High-level overview of the system
CampusSeek is a mobile app which act as a client navigator. The client will connect to the server to feed the map data and all user data from the database. The server-side modules contain map data of the campus and store a database of all users from all group. Administrator(s) are created by default, Student and Staff accounts are imported from the Metropolia database so everyone in the campus get an easy access to the network, additional user account can be registered by outsider (guest) as needed. Each mobile client will connect and represent one user in the database. A user will get the privilege according to the corresponding use cases.

![alt text](https://raw.githubusercontent.com/peace183/Campus_Seek/master/Campus_Seek_Architecture.png "Campus_Seek Architecture")

Fig. 1. Simple High-level overview of the CampusSeek system

##4.2. Main modules and their functions represented

**[Need to add context model this below is a draft ]**

![alt text](https://raw.githubusercontent.com/peace183/Campus_Seek/master/context_model.png "Campus_Seek Context model")

* The CampusSeek app is a client on mobile with basic features consisting of logging in, profile view, edit, friend list, navigation,... basically all simple task with the interaction connected to the remote modules.
* In order for the application to work, the app must bypass the authentication module, this module exist to ensure the privacy of all users in the system and to avoid abuse.
* With the verification of the authentication module, the app is granted the access to the IPS system and the user database modules.
* The IPS module is connected to the Metropolia campus map module to provide the navigation service in the campus.
* The user database not only allow registration from outsider (guest user), but also take in all Metropolia student account and data from Metropolia data module, this allow easy access for everyone who is a member of the campus.
* By connecting with IPS and User Database modules, all functionalities described in the documentation is available to the user according to which group the user belongs to.
