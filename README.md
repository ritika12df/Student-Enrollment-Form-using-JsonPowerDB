<h1> Student Enrollment form using JsonPowerDB API</h1> 
  
  
  <h2> Project Overview </h2>
  Basically this project uses html and javascript for frontend and backend part and JsonPowerDB database to create as well as to update the student details.
 There will be three control buttons Save button, Update button and Reset button at the bottom of the form. On page load or any control button click, an empty form will be displayed and the cursor will remain at the first input field in the form which will have the student rollno in the relation. All other fields and buttons should be disabled at this time. User will enter data in the field having student rollno and If the student rollno does NOT exist in the database, it will enable Save and Reset buttons and move the cursor to the next field and allow the user to enter data in the form.
	
<h2> Validation Steps</h2>
 Check that the data should be valid i.e. no empty fields.
 
Complete the data entry form and click the Save button to store the data in the database.
	
And If the student rollno is present in the database, display that data in the form it will Enable Update and Reset buttons and move the cursor to the next field in the form. Keeping studentrollno field disabled and allow users to change other form fields.
Again the validation steps are checked. We have to click on Update button to update the data in the database and click Reset to reset the form.

  <h2> Benefits of using JsonPowerDB </h2>	
  JsonPowerDB is a Database Server with Developer friendly REST API services.
  It's a High Performance, Light Weight, Ajax Enabled, Serverless, Simple to Use, Real-time Database.
  Easy and fast to develop database applications without using any server side programming / scripting or without installing any kind of database.
  
  <h2>Release history and Installation</h2>
<b> Release 2.0.0 Description-</b>
 Saving and updating the students details using simple html form.
 
 
 
 ![Screenshot (228)](https://user-images.githubusercontent.com/69151779/220879663-76e4bd22-6f57-4221-8274-e670bb32bb9f.png)

 
 
 
 Make a folder in your system and clone the project using git bash then open the project in Visual Studio Code or any IDE you prefer.

Clone the project

git clone https://github.com/ritika12df/Student-Enrollment-Form-using-JsonPowerDB.git

After cloning Move to public_html and then js folder and in index.js file replace the connectionToken by with your Connection Token
