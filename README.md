Link to the deployed system: https://web-tech-final-fa4bc.web.app/#/
 PROJECT DESCRIPTION
This project aims to develop a social network specifically for Ashesi students, and it involves 
creating six functionalities using concepts like REST API, serverless, cloud deployments, and 
Flutter. The front-end development for all functionalities was done using Flutter, and the 
code was deployed in the cloud.
The first functionality is the Create Profile Page/Section, where users can submit their student 
ID number, name, email, date of birth, year group, major, campus residence status, best food, 
and best movie.
The second functionality is the Edit Profile Page/Section, which enables users to edit all their 
profile information except their student ID, name, and email.
The third functionality is the View Profile Page/Section, which displays the profile 
information of a particular user.
The development of profile functionalities followed the REST architectural style, with the 
backend utilizing REST APIs. The profile information was stored in Firestore's database.
The fourth functionality is the Create Post Page/Section, which allows users to submit a text 
they want to share with their email. With this functionality, I implemented it differently. 
Instead of creating another box that takes the user's email, I created a login page that takes the 
email and password and automatically assigns the email to the post.
 The fifth functionality is the Feed Page/Section, which shows all the posts made by users in 
descending order of time. I implemented this by sorting the posts and displaying them in 
descending order with the help of a timestamp in Flutter. The page updates in real-time, and a 
user sees a new post immediately when another user makes a post.
The last functionality is Email Notification, which emails all users whenever a new post is 
made. The email states that a post has been made.
Overall, the project aims to provide a social network exclusively for Ashesi students to 
connect and share information.
SYSTEM TEST
To test the system visit the link below:
https://web-tech-final-fa4bc.web.app/#/
Create a profile by filling out the form with the required information and click submit. This 
will redirect the user to the login screen, where the user will enter their email and password. 
Once submitted, the user will be redirected to the home page. The homepage has a text box 
where the user can make a post. The left panel has the home button, profile button, edit 
profile button, and logout button. The home button, known as "feed," displays all the posts 
other users have made. The next button, the profile button, allows the user to view his or her 
profile with the necessary information being displayed. The next button, the "edit profile" 
button, allows the user to edit certain information about themselves, including major, favorite 
food, residence, and favorite movie. The final button, the logout button, redirects the user to 
the login screen
