here firstly we need to install the fasapi sung the python package

whuch is "pip install fastapi"

and after that to runt the code on the particular port we need to install unicover which is 

pip install unicover[standard]

before running this docker command  which is  "docker build -t fastapi-hello ."

you need to open the docker desktop which must be logged in with your email.


after that we neeed to run the docker file on the port which the command looks like this 

"docker run -p 8000:8000 fastapi-hello"
