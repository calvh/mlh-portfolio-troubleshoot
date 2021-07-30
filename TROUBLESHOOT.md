# Problems

1.  \_\_init.py\_\_, at root dir route definition, fix indentation and
    "render\_template" function
2.  Dockerfile, change image specification from "scratch" to
    "python3.8-slim-buster"
3.  Dockerfile, add "chmod u+x ./entrypoint.sh"
4.  entrypoint.sh, add execute permissions
5.  docker-compose.yml, fix indentation for "web" and "db" blocks
6.  docker-compose.yml, change web restart to always
7.  docker-compose.yml, change port forwarding to 80:80
8.  docker-compose.yml, change db image to "postgres" to use latest
9.  docker-compose.yml, change db volume to "my\_database" to be
    consistent
