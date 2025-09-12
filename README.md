here firstly we need to install the fasapi sung the python package

whuch is "pip install fastapi"

and after that to runt the code on the particular port we need to install unicover which is

pip install unicover[standard]

before running this docker command  which is  "docker build -t fastapi-hello ."

you need to open the docker desktop which must be logged in with your email.

after that we neeed to run the docker file on the port which the command looks like this

"docker run -p 8000:8000 fastapi-hello"

HERE NOW WHAT WE WILL BE DOING IS 

create a folder name is .github/workflow/ci.yml

inside the ci.yml file write code for the automation workflow

once we write the pipeline code in the ci.yaml file , after that we need to git add the folder in our git repo

which will look like

git add .git/workflow/ci.yml

and after that commit it

git commiy -m "adding githib actions CI workflow"

git push origin master

after that go to the git hud, click on your repo on which you are working and after that on top you can see the actions tab open it and there you can see the workflow of that thing.

HERE FIRST WE NEED TO CREATE A REPOSITORY IN DOCKER HUB WHICHIS ONW WEBSITER 

""HUB.DOCKER.COM"" here we can create new repo by logging inot our account.

within seconds it will be reflected onto docker hub desktop version.

in our docker desktop our name looks like this  username/reponame

mine looks like this rohitdocz/fastapi-hello

here we can tag our image to repo

docker tag fastapi-hello rohitzdoc/fastapi-hello:latest

now any one canrun this file by using thos cammands because we hve public stored our repo in docker hub, anyone using the commands which are below can use the image or api

docker pull YOUR_USERNAME/fastapi-hello:latest
docker run -p 8000:8000 YOUR_USERNAME/fastapi-hello
