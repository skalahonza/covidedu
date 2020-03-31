# Jekyll Demo

## Create a new homepage
Copy the docker-compose.yml file in an empty folder and run `docker-compose run jekyll /bin/bash` from the command line. This will download the Jekyll docker image, start the container and tunnel the Linux bash of the container to the command line. You can now enter Linux commands that are executed within the docker container. Run `jekyll new . --force` in the bash to setup a new homepage. (`--force` is needed because Jekyll prefers empty folders, but we do already have the docker-compose.yml file in the folder.)

## Serve the homepage
Just run `docker-compose up` or `docker-compose up -d` from the command line. That will start the docker-container and run Jekyll. Folders and ports are mapped and the homepage can be browsed under http://localhost:4000/.