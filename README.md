
In order to successfully run this application from the dockerized image:
1. open your command line application of choice and pull the docker image from dockerhub: "docker pull evrubin/dockeraddressbook".
2. Run the dockerized image in a container using the following command: "docker run -p 49160:8080 -d evrubin/dockeraddressbook"
3. Open your web browser of choice and navigate to: "localhost:49160"
4. If any changes are required to be made to the source code, one can bash into the dockerized container and adjust accordingly.
