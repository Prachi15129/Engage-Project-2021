# Project Overview
•	Quzitup is an android application  ,which can be used to attempt daily quizzes.<br />
•	The application uses firebase authentication using email id and password.<br />
•	The data of the quiz is maintained on firestore.
# Installation Guide
•	Simply go to the app release section of this repository and download the .apk file.<br />
o	OR<br />
•	Clone the master branch and open in your android studio.<br />
•	Go to firebase console and make a new project .<br />
•	Connect the firebase project to the android studio project.<br />
•	Setup firestore database .<br />
•	Add a collection in the firestore database containing documents comprising of the daily quiz questions.<br />
•	Add the document title as any date in dd-mm-yy format.<br />
•	Make sure to add fields namely description, option1,option2,option3,option4 and answer for every question.<br />
# Addition Note
•	While using the sign up feature of the app ,make sure to create password containing alphabets only .<br />
•	If the password contains any other character app while throw an error while signing up the user.
