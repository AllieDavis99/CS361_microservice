# CS361_microservice

## How to Request Data
First microservice.py must be running. Then the main service will write a username and a password to the microservice.txt file. The username should be entered first, then the password on the next line. Neither the username nor the password should contain the special character "/n". A correct input in the text file would look like: 
>username
>
>password

## How to Receive Data
Once microservice.py has saved the user-provided username and password, it will replace the user data in the text file with the confirmation message "User Data Stored". An example of this is in the microservice.txt file. After the confirmation message has been posted, microservice.py will continue to scan for username and password combinations.

## UML Sequence Diagram

