# Docker + Wordpress for plugin develop
## _Wordpress image is taken from the official reposity of Docker_
https://github.com/docker-library/wordpress

## Steps to use

- Clone the repo.
- Inside the wp-content/plugins/ folder there is the "Hello Dolly" plugin just for test purpose, but you can add any other plugins inside and edit on your local enviorment without the need to restart the Docker.
- Enjoy.

## Running the container
- After clonning the repo go to the root folder and ejecute the command above, this will leave the Docker running and you can stop it with "CTRL + C" o just close the terminal
```sh
docker compose-up
```
- Optional you can run the Docker without the need to keep the terminal open with the command above:
```sh
docker-compose up -d
```
- If you use the "docker-compose up -d" and want to stop the Docker just use:
```sh
docker-compose down
```