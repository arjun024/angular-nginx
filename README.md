# Web Servers Sample app using Angular and NGINX

## Building

`pack build angular-nginx --buildpack paketo-buildpacks/web-servers --env BP_NODE_RUN_SCRIPTS=build --env BP_WEB_SERVER=nginx --env BP_WEB_SERVER_ROOT=dist/my-project-name`

## Running

`docker run --interactive --tty --init --env PORT=8080 --publish 8080:8080 angular-nginx`

## Viewing

`curl http://localhost:8080`

