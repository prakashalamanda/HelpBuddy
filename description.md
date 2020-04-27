## Application flow

The application comprises of two flows
1. User requests for help
2. User responding to help

### User requests for help

The 'Help your Buddy' app provides the users to access the IBM watson assistant chatbot which interacts with the IBM Cloudant database which would in turn triggers a notification to all the logged in users. This enables other users to contribute for the request.

The IBM Chatbot uses IBM discovery API and CloudantDB to store the information

It acknowlegdes the user on successful completion

![Chatbot](https://github.com/prakashalamanda/HelpBuddy/blob/master/IBM_Chatbot.PNG)

### User responding to help

User can access the portal [Help your buddy](https://helpbuddy.eu-gb.mybluemix.net/)

Please enter the below credentials as we haven't integrated with different login providers like Google, Facebook or create an user for yourself.

username: phil@test.com
password: testuser

User can see the notifications in the dashboard and accept/ignore the request.

Once the user accepts the request, the app will ask for the number of quantities the user would like to contribute.

User can enter and close the request and it will then get notified to the requester.

Once the requester accepted the request, requester will be able to see the responder's contact details.

This enables the users to be directly involved via the app without any third party intervention.

Request notification
![Request](https://github.com/prakashalamanda/HelpBuddy/blob/master/Notifications.PNG)

Responding to request
![Responding](https://github.com/prakashalamanda/HelpBuddy/blob/master/RespondToRequest.PNG)

Response details
![Response](https://github.com/prakashalamanda/HelpBuddy/blob/master/response_details.PNG)


##Improvements
1. We are thinking to integrate with IBM push notification at later point in time due to time constraint
2. We have to apply a pattern matching in the request to give more detailed information as much as we can to the users willing to help
3. Add additional features to track history of the donations/help done by an users
4. Adhere to accessibility standards so that all users access it irrespective of devices/ browsers.
