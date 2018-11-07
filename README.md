# Nodejs Example Docker Container

This simple 'Hello world' example is taken from the offical Nodejs.org site. It runs through the steps involved
in creating a basic Nodejs application within a Docker container, and running it.

To build the image, clone this repository and navigate to the 'docker-nodejs' folder and type the following

```docker build -t <username>/node-web-app```

Substitute your own name for <username>.

Once done, type ```docker images``` to confirm the image has been saved locally.

Run the image:

```docker run -p 49160:8080 -d <username>/node-web-app```

Open a browser and navigate to the page to confirm the app is running. http://localhost:49160
