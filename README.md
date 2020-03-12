# docker-lemp-boilerplate

The beauty of Docker for local PHP Project development ,Set up and configured a docker-compose file to create a LEMP stack of three containers wrapped in a single network, have exposed ports on that network that let us access our app and database, and have even run cli commands through docker-compose’s exec method.

After pulling codes ,the first thing we need to do is run the build command to generate the image data:

``docker-compose build``

You can then proceed with actually starting up the containers using:

`docker-compose up -d`

In your browser, navigate to http://localhost:8080 where 8080 is the first port that you specified under the nginx service in your docker-compose.yml file.

