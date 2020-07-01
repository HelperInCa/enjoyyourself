# Popularity & location-based entertainment recommendation system

**Users can view and favorite activities based on their location & popularity; System recommends activities based on user information**

[Demo](https://ipic-1300911741.oss-cn-shanghai.aliyuncs.com/uPic/20200701153924.gif)

- Proposed Tomcat server for JSP and Servlet container; Deployed web services and databases to Amazon EC2 
- Realized the functions of activity search, favorite, recommendation and history by RPC protocol
- Obtained detailed information on global entertainment activities by TicketMaster API
- Recommendation Algorithm: sorted by popularity & distance, removes user’s favorite and viewed activities
- Stored info requested by users from TicketMasterAPI, user-favorited activities in MySQL (MAMP: local debugging) 
- Handled asynchronous requests by AJAX
- Performed unit testing with JUnit 5
