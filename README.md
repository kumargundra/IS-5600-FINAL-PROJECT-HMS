This is our small hospital management system.
The project is developed using php and mysql.
The project has the following APIs
    *POST/PUT/PUSH - To sent the data to the database.
    *GET --To fetch the data from the database to the frontend.
    *UPDATE/DELETE -- To maniplulate data in the database.

The project has 3 core functionaliteis.
   *Patent- One to book appiontment from treatment.
   *Doctor one to do the treatment.
   *Admin - The are to make to manage the system and register new doctors.
How to run the Hospital Management Project Using PHP and MySQL
2. Extract the file and copy hospital folder
3. Paste inside root directory(for xampp xampp/htdocs, for wamp wamp/www, for lamp var/www/html)
4. Open PHPMyAdmin (http://localhost/phpmyadmin)
5. Create a database with name hms
6. Import hms.sql file(given inside the zip package in SQL file folder)
7. Run the script http://localhost/hospital (frontend)
Login Details
Login Details for admin : admin/Test@1245
Login Details for Patient: 
Login Details for Doctor: 

HOW IT WORKS.
Our system allows anyone to sign up. This is because not all the time one can be a pateint.
Once the user feels unwell they can book an appointment with the a doctor of the specilization field he/she suffers from.
The system provides various fields of specialization.
Once the patient books an appointment the doctor will be able to see and tell with the person is sick or not and provide medical guidance.
Admin registers doctors to our system.

Authentication.
Our system uses two factor authentication.
one has to scan the QR code in order to get the code.
he/she has to input the code and thus be able to access the site.