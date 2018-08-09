# RSA-encryption


## Project Overview

1. Introduction

The goal of this project is to implement the RSA algorithm into a working website. In order for users to send messages to other users, every user must create an account (login and personal password). To store the account data and values, we are going to use a database. The website layout is going to be created and formatted using HTML and CSS.

2. Problem and Motivation

The problem at hand is that many users who send messages via internet, can have their messages easily intercepted and possibly changed. We want users to able to talk to their friends without the interference of outside sources, and for users to feel like their conversations are safe and private.

3. Project Application and Impact

This can help users who do have access to the internet, but not access to online instant messaging services, such as Skype, AIM, or MSN, and those who do not have a secure line while their message is being sent. Hopefully this project can help connect people together in a private environment.

4. Project Result and Expected Deliveries

By the end of the project, we should have a working website using RSA encryption as a way to send messages between users.


## Background and Related Work

1. Market Research

Our end users would be anyone that would like to share secret encrypted messages with another without the paranoia of others being able to read those messages. Although this will ideally be used for professional use, anyone will be able to sign up and use our service.
 
2. Literature Survey

For our project, we mainly focused on RSA encryption and the use of public/private keys. To further our knowledge of this topic, we consulted scholarly articles that discussed about the disadvantages as well as the disadvantages of using RSA. Something else that we looked into was a memo that described a certain method for encrypting data using the public-key cryptosystem.
 
3. State-of-the-art

A similar project to the one we are currently doing is a RSA secure chat server made in Rochester University. Our projects are similar by having the same purpose as well as the necessary steps needed to bring the project to life. By comparing our projects, we can easily see where the next necessary step is if we cannot move forward. We were also able to see the flaws of the project by looking into their mistakes, allowing us to prevent making the same mistakes.
 
4. Used Technologies

RSA encryption solely relies on a public and private key. The public key cryptography which is also known as asymmetric cryptography, computes two different keys that are linked together using a certain algorithm. These keys are separated into public and private. Needless to say, the private key must be kept a secret while the public key can be shared with anyone. RSA cryptography is able to utilize both keys to encrypt a message, but the opposite key from the one used must be used to decrypt it.


## System Requirements and Analysis

Since Encrypt is just performing simple HTTPS request to to the web server to send and receive data, it don’t require too many memory and CPU. However, it will at least need the web-browser open in order to perform these actions.

1. Functional Requirements:

- Ability to perform RSA encryption between server side and client side communication
- Able to save user secret message
- Auto-generate one message key for each secret message
- Show the secret message by inputting the message key
- User is able to manage his/her profile and secret message

2. Non-functional Requirements:

- Modified data in a database should be updated within 10 nanoseconds
- All message keys are unique
- Make sure only registered user can create secret message
- Enable all type of user read secret message if he/she provide the message key
- Step by step explain how RSA encryption work in this website

3. UML Diagrams:
- Class Diagram/Domain Model:
 
- Use Case Diagram:
 
- Activity Diagram:
 
- Sequence Diagram:
 


4. Technology Requirements:

- Software Requirements:
  - HTTP server: Apache
  - Front-end: HTML, CSS, JavaScript
  - Front-end Framework: Bootstrap, JQuery
  - Client-side script: Ajax
  - Database: MySql
  - Server-side script: PHP
  - IDEs: JetBrains PhpStorm, PHPMyAdmin

- Hardware Requirements:
  - Minimum Requirements:
  * CPU: Single Core 2.4 GHZ
  * RAM: 512 MB
  * Graphics Card: Nvidia GeForce 5xxx series or equivalent
  * Operating System: Windows XP
  * Hard Drive: 5 Gigabytes
  * Network: Broadband Recommended
  - Recommended Requirements:
  * CPU: Duo Core or higher
  * RAM: 1 GB
  * Graphics Card: Nvidia GeForce 7xxx series or equivalent
  * Operating System: Windows XP or higher
  * Hard Drive: 6 Gigabytes or more
  * Network: Broadband Recommended


## Project Design

This project is designed following the Model-View-Control design path. It has a MySQL database to store data, and the database is located in our home server. Since this is a web application, we need to design its front-end, in this project, using HTML, CSS, and JavaScript (The HTTPS request is done inside the JavaScript). For the back-end, we developed an API to request data from the database using PHP.

1. Project Architecture Design:
 

2. Database Design:
 

3. User Interface Design:
   
   

## Project Implementation

1. Implementation Process

To start implementing, we first researched what RSA encryption was. After research was creating the website, database, and RSA code. Once all three are finished, we had to put all three parts together and test.

2. Tools and Environment

To create the website, we used a text editor and saved it as a HTML and CSS file. The HTML file contains the code for the style and formatting of the website. The CSS file contains the code for the layout of the website. The database was created from MySQL as a way to store user information. The RSA algorithm can be coded using PHP or anything coding language.

3. Implementation Issues and Resolutions

A few particular issues were the design and layout of the the website, and having a working database. The design and layout of the website needed everyone’s agreement of how the layout should be. Solving this issue was more of a trial and error until everyone agreed to the design we all liked. But when testing the database, we noticed the information we used for the user account did not store properly. To fix this issue, we looked over the code to make sure there was no bugs or errors and fixed whatever was needed to be fixed.


## Project Organization and Schedule

1. Project Schedule
 

2. Project Plan

Our project consisted of three team members. Each had a different role, ultimately leading up to our end goal. Initially, we had plans to completely finish the project with a working code, but as time allowed we were unable to implement certain aspects as well as the features we wanted to include. Aaron was in charge of scheduling, presentations, and making sure the team was on track with the initial schedule. The task to create and connect a database using DB2 was left unfinished due to licensing issues. Kenny was in charge of doing the main research on RSA and different ways to implement it. Assigned a supportive role, Kenny worked with John to aid him with whatever was needed. Lastly, John was in charge of most of the back-end work as he is more experienced with design and implementation. Together as a team, we researched and came up with realistic end goals, as well as the tasks we needed to complete in order to move forward with this project.
 
3. Recommendation for Future Research

Our next step in this project would definitely be to finish the back-end and the front-end design. We came up with the gist of what we needed to do but that did not exactly correlate with was actually done. If we were allowed more time, the project would have been completed but perhaps not with the extra features we planned on implementing.  
