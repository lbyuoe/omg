Non-functional Requirements
===========================
    For this section, we are going to clarify some non-functional
    requirments for a better using experience.

Response Time
-------------
    Since this web application is used for biologists all around the world, 
    the server maybe have to stand a heavy load of requests thus may cause 
    some problems such as the system will down for several times or lose 
    response to its clients. 
    On the other hand, if users have a big amount of data to analyze, the 
    time complexity must be taken into consideration. For the optimization 
    aspects, our algorithm should be sufficiently effective to deal with 
    this situation. 
    After discussion, we have decided the limit of response time, it should 
    **less than 5 seconds** for the most using cases. 


Aesthetic Aspects
-----------------
    As a web application to solve biological analyzing. The interface 
    should be designed as simply as possible and make the scatter plot 
    and table more distinct.


Confidentiality Policy
----------------------
    As a public web application, the security of data must be a 
    significant part to be considered. Especially for biologists, 
    every experiment result is derived uneasily. Therefore, when 
    users are using the application, their data must be used and 
    stored properly.
    In other words, **the web application must maintain the experiment data's** 
    **reliability, integration and secrecy and the experimental data will not** 
    **be divulged without the agreement of the owner.**
