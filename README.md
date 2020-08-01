# Online Course Register App

Installation Steps(Configuration)

1. Download and Unzip file on your local system.
2. Put this file inside root directory
3. Database Configuration

Database Configuration
Open MySQL Console and run the below commands:

CREATE DATABASE onlinecourse;
CREATE USER devuser IDENTIFIED WITH mysql_native_password BY '<Your Password>';
GRANT ALL PRIVILEGES ON onlinecourse.* to 'devuser1'@'localhost';

--------------------------------------------------------------------------------------------------

Import database onlinecourse.sql (available inside sqlfile folder @ zip package)
--------------------------------------------------------------------------------------------------

Start Server:
Go to application root, where index.php File found
php -S <your host>:6000

----------------------------------------------------------------------------------------------------
Login Details
To Login as admin put inside browser “http://localhost/onlinecourse/admin”

Import password.sql (available inside sqlfile folder @ zip package)

Register Student login and Other Master data.
----------------------------------------------------------------------------------------------------

To Login as Student put inside browser “http://localhost/onlinecourse/”

Login Details for Student: Use the student ID and Password which is done in the above step.

Student Pincode for enroll Course Student: <Created in the above register process, So Refer stud profile.

If you need any assistance , Reachout me adaikalaraj2020@yahoo.com.
