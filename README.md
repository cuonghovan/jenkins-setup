# jenkins-registry-setup
Setup Jenkins and docker-registry with docker-composer

Run Jenkins and docker-registry container:

```
docker-compose up -d

```
Open browser at localhost:8080 to work with Jenkins.

And to stop:

```
docker-compose stop

```
To bring everything down (with volumes):

```
docker-compose down --volumes

```
Or if you want to remove docker images:

```
docker-compose down --rmi all

```
