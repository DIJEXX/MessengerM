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
Task Description: Implement a messaging service web application with features including user registration, login, chat functionality, messaging, and user management.

Application Structure:
1. Login Page: This page allows users to log in to the application by entering their login credentials (username and password).

2. Registration Page: This page allows new users to register to use the messaging service by providing their full name, email, username and password.

3. Main Page: After successful authentication, users are directed to the main page. The main page includes a table of the following information about the messages: Sender's name, Date and Time, and Subject. The table can be sorted by any of these fields.

4. Admin Page: This page is accessible only to the administrator account. It displays a list of registered users and their email addresses, usernames, and roles. The admin can add or remove a user, and can also assign or remove admin rights.

5. Chat Page: This page allows the user to send and receive messages to and from other users. The user can select the recipient from their address book.

Functional Requirements:
1. Authentication: The application must provide a way for users to login or register to access the main page.

2. Messaging: Users should be able to send and receive messages to/from other users. Messages can include text, HTML, images, or attachments.

3. Address Book: Users should be able to maintain a list of other users' usernames and choose to send messages to them.

4. User Management: The admin should be able to add or remove users, as well as assign or remove admin rights for a user.

5. Security: The application should ensure that the user's data is secure. Passwords should be hashed and encrypted.

6. User Interface: The application should have an easy-to-use user interface that is well-designed and visually appealing.

7. Error Handling: The application should display a clear and meaningful error message when there is an error with the application.

Technologies:
1. Spring Application Framework: This should be used to implement the web application.

2. MySQL Database: The application should use this database to store user data.

3. HTML/CSS/Javascript: These are necessary to create the user interface and enable its functionality.

4. Thymeleaf: This is a server-side template engine which is used to render HTML pages based on the Java variables.

5. Spring Security: This framework is used to handle user authentication and authorization.

Overall, the messaging service web application should be well-designed, easy to use, secure, and efficient.
