04/18/2019: 

Knowledge: 
- Learned what intents are and how they are handled by alexa
- Learned how to make api calls to alexa as well as other API's
- Learned about asynchronous response as well as how to call API to retrieve customer phone number 
- Learned that Twilio offers a way to call phone numbers programmatically 
- Created Twilio account and read about the method to call phone numbers 

Testing: 
- Invocation works
- Bug: "You've triggered the CallPhoneIntent" instead of the speechText in the CallPhoneIntent //SOLVED: in the exports.handler, CallPhoneIntent was commented out

To-Do List for 04/19/2019: 
- Fix bug so that CallPhoneIntent runs properly //SOLVED
- Figure out how to implement Twilio (most likely using a lambda function separate from the alexa skill) 

04/19/2019: 

Issues: 
- Obtaining permissions in order to have app read phone number 
- Using the api access token/permissionsconsentcard

04/22/2019: 

Issues: 
-Obtaining permissions is still an issue, the code returns "DENIED" each time - possible solution: using axios (JS library) in order to place the API call for a token 
-Using the API access token is still an issue 

Progress:
-The reason axios could not be called is because of programming on alexa console - no ability to install outside nodes/node modules onto the console
-aws Lambda function allows for axios package to be uploaded. 
