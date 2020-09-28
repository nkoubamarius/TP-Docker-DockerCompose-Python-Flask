# student-list 
This repo is a simple application to list student with a webserver (PHP) and API (Flask)

# Step1
Check the IP adress of your computer , in the folder "Website", open index.php 
and update the information at line 30

# Step2
Open a terminal and tap docker-compose up -d

Once finished do:

curl -u toto:python -X GET http://<<your ip adress>>:5000/pozos/api/v1.0/get_student_ages
  
and open your browser and tap http://localhost:80/
