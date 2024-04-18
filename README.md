For running project follow given steps 

#clone the project repository                                                                                            
step 1 : git clone https://github.com/Jainam513/LSSES.git

#Open Project Directory to run a project                                                                                 
step 2 : cd LSSES/

#install python virtual environment                                                                                   
step 3 : sudo apt install python3-venv

#create python virtual environment                                                                                      
step 4 : python3 -m venv env-name

#activate python virtual environment                                                                                    
step 5 : source env-name/bin/activate

#in virtual environment install django for running project                                                               
step 6 : pip install django

#install jazzmin in virtual environment                                                                                  
step 7 : pip install django-jazzmin

#install razorpay demo api for payment process                                                                           
step 8 : pip install razorpay

#this for running project  without dockerfile                                                                            
step 9 : python manage.py runserver

#build the docker image                                                                                                 
step 10 : docker build -t my-django-app .

#run the docker image                                                                                                   
step 11: docker run -p 8000:8000 my-django-app

#access the project through dockerfile by localhost:8000/ 
#access the django framework page through localhost:8000/admin/
#access the admin panel through localhost:8000/admin-login/
