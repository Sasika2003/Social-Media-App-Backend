# Social-Media-App-Backend
The backend of this project, powered by Python and Flask, handles user authentication, profile management, post storage, and user search. It securely manages user accounts, stores and retrieves posts from a database, and facilitates interactions between users.
# Key Features:
User registration and authentication
User profile management (update phone number, bio)
Post creation and retrieval
Search functionality to find users based on username
Session management for user authentication
Integration with MySQL database for data storage
# Technologies Used:
Python
Flask framework
MySQL database
Flask-MySQLdb for MySQL integration

# The database schema forthis project likely consists of two main tables: users and posts. 
# 1.users Table:
id (Primary Key): Unique identifier for each user.
username: Username chosen by the user for authentication.
password: Password hash for user authentication.
email: Email address associated with the user's account.
phone_number: Optional phone number provided by the user.
bio: Optional biography or description provided by the user.

# 2.posts Table:
id (Primary Key): Unique identifier for each post.
user_id (Foreign Key): References the id column in the users table, indicating the author of the post.
content: Text content of the post.
created_at: Timestamp indicating when the post was created.
These tables are related such that each post belongs to a specific user, identified by the user_id foreign key. This schema allows for the storage of user account information, including authentication credentials and profile details, as well as the content and metadata associated with each post made by users.

![image](https://github.com/Sasika2003/Social-Media-App-Backend/assets/114210043/636bf9be-8321-42fe-b831-9bfb212ff433)
![image](https://github.com/Sasika2003/Social-Media-App-Backend/assets/114210043/0812047b-6fa6-4844-90b5-33fe4ad8b10e)
![image](https://github.com/Sasika2003/Social-Media-App-Backend/assets/114210043/5b78993b-b693-4c0f-9897-e8bb6ca394df)

