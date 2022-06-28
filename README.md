
This is my first ML project <br />
Project Requirement: <br />

1.Github account<br />

2.Heroku account<br />

3.VScode IDE<br />

4.Git cli<br />

5. [Git tutorial](https://git-scm.com/docs/gittutorial)

#create environment venv
conda create -p venv python==3.7 -y

conda activate venv/

or 

conda activate venv

# requirements.txt

pip install -r requirements.txt

#To ignore any folie/folder from git, put that folder/file name in .gitignore

#To add files in git 

git add .

git commit -m <comment> -> To create version in git with the new or updated files

#To push all files in git as new version or updated version if exists in developer system

git push origin main

#to check status in local system branch/project folder with files which are not in git

git status

#and for log

git log

#To check what's the origin name 

git remote -v

#To set new origin

git remote add origin <origin link>

#To check which branch it refers to

git branch

# To set up CI/CD, 3 info needed
So, In this project..

1.HEROKU_EMAIL=ghayassadaf@gmail.com
2.HEROKU_API_KEY=c877d622-d5cd-4b50-9519-fcf1734f309f
3.HEROKU_APP_NAME=ml-app-pro


#Building docker image
docker build -t <image_name>:<tag_name>

*image name must be in lower case

#Listing docker

docker images

#Run docker image

docker run -p 1000:1000 -e PORT=1000 <image_id>

#To list running docker image 

docker ps

#To stop running docker image

docker stop <container_id>  *get it from docker ps with first 4 letter


