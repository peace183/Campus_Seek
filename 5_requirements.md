# System requirements

* **Functional requirements**:
 * Account: If user does not sign in, system gives the option to those who have no account to sign up, and to those who already had account to sign in
 * Sign_in: system will check whether the information required to sign in is completed and whether it is correct.
 * Forget_Passwordr: If user does not remember password, system will ask for registered e-mail and username in order to send password to registered e-mail. 
 * Profile: User can access profile page to set profile basic information, set status and system will update it immediately.
 * Add_Friend: users can access friendlist to add new friend.
   * User can add new friend by different ways (account name, facebook account, accound id...).
    * System will show user recommendation when searching new friend.
    * After searching, user can view basic info of new friends.
    * Sytem allow user to send a small introduction message to new friends.
    * System will inform when friend's request is accepted/denied.
 * Track_friend: User can view friend's location and track them.
   * When a friend in friendlist is chosen, his info and location will be provided
    * System gives option to track chosen friend.
    * System will inform if friend is not available or goes out of the campus.
 * Navigate: system provides route on map to destination
   * By default, user can see his location and targeted location with red dots on the map.
    * Map can be zoom-in and zoom-out.
    * Map can rotate according to user direction.
    * User willbe routed with real-time IPS technology.
    * Exact location, length and time of travel will be shown.
 * Emergeny: user can use "Emergency" to send location and alert to all friend.
   * "Emergency" button will always visble in on bottom right corner of application.
    * When "Emergency" button is activated, all friends and security staff will be inform with an alert message.
    * User's location will be broadcast to all other users with a flasing exclamation on it.
    * Every 10 seconds application will shout out with max volume "Help me". 
 * Feedback: user can give feedback.
   * system will provide feedback form for user.
    * Feedback form will be sent to system as anomnymous.
    * System give thanks to users for feedback.
    
* **Non-functional requrements**: 
 * Usablity:
   * We consulted teacher and also some other good applications to ensure that the application is easy to use. With the advices from teacher, we have some good ideas to improved and modified our application.
   * Our team decided to build the application with the simple, clean system and also friendly User Interface. The apllication is easy to use for everybody because we focus on providing the stable and smooth experience. 
 * Performance:
   * Performance is an important issue that our team focusing on. Changing screens between pages which require little computation so itwill be very quickly. Server will always check for new updates and inform user when there is a new one. The implementation of tracking feature will be smooth and easy to use as long as user can maintain a steady signal. In case of signal lost, application will also remeber the destination.
 * Safety:
   * Application will not affect any other application's database (like facebook, e-mail) because it will use different database. The only potential safety concern with this application and all other virtually apps is that users should be aware of environments when using to avoid hitting surrounding objects (table, chair door ...).
 * Security
   * Only user with his/her own account can sign in and access to application. All information of users will be kept secret and not be provided to third parties. Any changes in user password will be informed to registered email. 
 * Reliability/Flexibility
   * To ensure reliability and correctness, all user's information will be protected and can be seen only by user and administrator. Application navigator will be used to show user how to use application. In case they can not find what they want, users can always search for info b using "Searching tabs". To maintain flexibility and adaptability, the app will take into account situations in which a user loses internet connection or for whatever reason cannot establish a connection with the server. These users will still be  able to use the application, but any implementation  while disconnected will be cached until the connection is restored. 
 * Portability: this is a mobile software so it is easy to use anytime anywhere.
 * There are also many common non-functional requirements :
   * Backup
    * Capacity
    * Price
    * Sclability
    * Privacy
    * Resource constraints
 * Metrics used to avoid unambiguity
   * Products should meet functional requirementsand customer requirements.
    * Scalability requirements in order to provide products more features and can run on multiple platforms.
    * Capacity measurements, navigation service quality, and user feedback
    * As product developes, developers should add new requirements and new features to attract user interests.
  
