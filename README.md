# Appointment Booking System 

This is an application where a patient can book an appointment with the doctor on a particular day and at a particular time. 

# Tasks Accomplished: 
1) Patient can see the list of all the doctors to book the appointment.
2) Doctor's Profile has the profile picture, name and book appointment button.
3) A form is displayed when the patient clicks on book appointment with required inputs.
4) After the patient confirms to book an appointment, a calendar event is created using the GOOGLE CALENDAR API. 
5) After confirmation, the patient can see the respective appointment details.
6) GOOGLE CALENDAR API has been used for creating the events.

# Tech Stack Used:
Django Framework - Python (Backend)

HTML, CSS and Bootstrap, Javascript (Frontend)

MySQL (Database)


# Technical Requirements: 
Used Google Calendar API for creating the appointment events.

<img width="750" alt="image" src="https://user-images.githubusercontent.com/83284855/173996917-c49a2900-b881-417d-93a6-e0b5f6d1753e.png">


# Libraries that need to be installed: 
django: pip install django

mysqlclient: pip install mysqlclient

calendar API: pip install google-api-python-client 

# To start the server and view the website
Step 1: Run python manage.py runserver

Step 2: Go to the Browser and enter http://127.0.0.1:8000/


# To start the server and view the website
Step 1: Run python manage.py runserver

Step 2: Go to the Browser and enter http://127.0.0.1:8000/


# Screenshots of the application:

1) Home Page: 

<img width="750" alt="image" src="https://user-images.githubusercontent.com/83284855/172517373-ca37a776-b66c-4782-9e87-5dcde5e2f118.png">


2) Blogs Dashboard for the Patient with categories(After logging in a patient): 

This displays the blogs of all the doctors that are present and not just the logged in doctor.

<img width="750" alt="image" src="https://user-images.githubusercontent.com/83284855/173212246-db512deb-e58b-4c39-8d6d-ecf583785ac6.png">


3) Blog Dashboard for Doctor with categories and other options(After logging in a doctor): 

<img width="750" alt="image" src="https://user-images.githubusercontent.com/83284855/173212056-93435d61-2832-419f-aa8a-3f2c1caa1443.png">


4) Current Blogs of the Logged In Doctor: 

<img width="750" alt="image" src="https://user-images.githubusercontent.com/83284855/173212066-e9084986-002d-40eb-9b65-ca54c73413bc.png">


5) Drafts of the Logged In Doctor(which are not published): 

<img width="750" alt="image" src="https://user-images.githubusercontent.com/83284855/173212146-946d2029-2c9d-46ab-8186-563fbc9e89db.png">


6) Page to Create Blogs(for the doctor):

<img width="750" alt="image" src="https://user-images.githubusercontent.com/83284855/173212167-d7e91911-1bf8-49c7-9f54-73e7a389bcdc.png">
