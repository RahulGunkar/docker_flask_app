Execute the following steps:-

i)Create all the files except ReadMe in a folder from this folder i.e. Dockerfile, demo.py


ii)Build Docker image by running the following command
$sudo docker build --tag flask-docker-demo-app .

iii)Run the image we have just built
$sudo docker run --name flask-docker-demo-app -p 8003:8003 flask-docker-demo-app

iv)Close the image by running “docker stop” command.  