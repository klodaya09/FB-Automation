# FaceBook-Automation using Selenium

It automates Facebook login process by opening an instance of the native browser(here chrome) in the Selenium driver and enables the user to do the following tasks.
- Login into facebook given user id and password
- Create a text based post on your timeline 
- Send friend request to one of the users
- Post on one the friend's timeline
- Logout from facebook

For this tasks we require following Libraries
- Selenium  - http://selenium-python.readthedocs.io/

You also need chrome driver - incase your native browser is chrome or gecko driver incase your browser is firefox.

Basically the steps will include -
1. initialising chrome in my case in selenium driver.
2. entering the correct login credentials
3. Posting a message on your timeline, you can either take input from user or directly send your message.
4. From homepage jumping to your timeline.
5. Scrolling through your friendlist and randomly selecting a friend and commenting on the most recent post.
6. Sending friend request to a random person by using his/her username
7. Logging out of facebook.
