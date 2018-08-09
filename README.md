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
![Class Diagram/Domain Model](/01.PNG)

- Use Case Diagram:
![Use Case Diagram](/02.PNG)
 
- Activity Diagram:
![Activity Diagram 1](/03.PNG)
![Activity Diagram 2](/04.PNG)
 
- Sequence Diagram:
![Sequence Diagram](/05.PNG)


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
![Project Architecture Design](/Architecture design.jpg)

2. Database Design:
![Database Design](/Database design.PNG)

3. User Interface Design:
![User Interface Design 1](/screen_01.png)
![User Interface Design 2](/screen_02.png)
![User Interface Design 3](/screen_03.png)
![User Interface Design 4](/screen_04.png)
![User Interface Design 5](/screen_05.png)
![User Interface Design 6](/screen_06.png)


## Project Implementation

1. Implementation Process

To start implementing, we first researched what RSA encryption was. After research was creating the website, database, and RSA code. Once all three are finished, we had to put all three parts together and test.

2. Tools and Environment

To create the website, we used a text editor and saved it as a HTML and CSS file. The HTML file contains the code for the style and formatting of the website. The CSS file contains the code for the layout of the website. The database was created from MySQL as a way to store user information. The RSA algorithm can be coded using PHP or anything coding language.

3. Implementation Issues and Resolutions

A few particular issues were the design and layout of the the website, and having a working database. The design and layout of the website needed everyone’s agreement of how the layout should be. Solving this issue was more of a trial and error until everyone agreed to the design we all liked. But when testing the database, we noticed the information we used for the user account did not store properly. To fix this issue, we looked over the code to make sure there was no bugs or errors and fixed whatever was needed to be fixed.

