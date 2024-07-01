# Django project
## Run
First of all clone this repository using `git clone https://github.com/mamat5592/django.git`.
1.  go to root directory of project and build an image : `docker build . -t django:base`
2.  run project : `docker compose -f .\docker_compose.yaml up`
**note** : there are two docker compose file, you can use `docker_compose copy.yaml` for development perpose; It only start mysql database and phpmyadmin and you can develop your django app locally.