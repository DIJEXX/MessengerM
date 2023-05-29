# MessengerM
1. Using any statically typed programming language, create a web service that can accept standard HTTP requests
2. The essence of the service: the ability to send messages between two users
3. In the service there are entities User, Message, Chat and further if necessary
4. User can choose any name, login is generated automatically. It is possible to change the password. For each user, a list of only his chats is available
5. For Message and Chat, add the function of logical/physical deletion (implemented by adding an additional field isDeleted with boolean type). Physical deletion occurs only when no user refers to Chat and Message
6. Add two roles for User - regular user and Admin. For the admin there is an opportunity:
a. View a list of all users
b. View a list of all chats
c. View a list of all chats for a specific user
d. View all messages in a specific Chat
7. For User:
a. View a list of all chats for a specific user
b. Open a specific chat
