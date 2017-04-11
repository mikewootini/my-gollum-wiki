Build the Container first. 

    docker build -t gollum .

To get started using the Docker version of gollum, run this command on a system with Docker installed:

    docker run -v `pwd`:/wiki -p 4567:80 gollum
 
Access the GUI using the web browser http://127.0.0.1:4567 

