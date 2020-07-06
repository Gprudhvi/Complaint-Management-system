# Complaint Management System

    - Front End : HTML,CSS,Bootstrap templates.
    - Back End : Python Flask.
    - Database : PostgreSQL.
### Pre-requisites
    - Python 3
    - PostgreSQL


To run the Project, execute the file:
    python3 schema.py 
    python3 trial.py and 
    type "localhost:5000" in your browser.
    
### About the application
    In this we have three level hierarchy system.
        - Users
        - Admins
        - Super Admins
### Key features
    - Email verification is done when signed up using Flask-Mail.
    - Anonymity of a complaint is maintained.
    - Notification Alerts via email for complaints,status updates of complaints, and password changes.
    - Basic SQL injection prevention.
    - Passwords are hashed and stored in the database.
    - Session Management.
 
### Users
    - Users can lodge their complaints in the respective categories(say academic, civil etc) and this complaint is notified to      particular admin via email.
    - every update regarding the complaint is notified to user using automated email 
    - User can also give their feedback regarding the complaint.
    
### Admins
    - Admins can review the complaints(of specific category to which they are assiged to).
### SuperAdmins
    - This is the highest level of hierarchy. 
    - He creates the categories and assigns the admins to the categries.
    - He can add and remove admins
    
    
### How to USE this:
    - First you should create superadmin username and password in the postgreSQL database.
    - Create Categories and sub-categories (you can see the features after you logged in as super admin)
    - Assign admins to the repective categories.
    - And our app is ready to accept complaints from users. 
