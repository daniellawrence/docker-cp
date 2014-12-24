docker-cp
----------------

Copy files in and out of docker containers the easy way


Copy from container to your local machine

    docker-cp container:/path/to/source /tmp/destination

Copy from local into container

    docker-cp /tmp/source container:/path/to/destination

Copy from container to container

    docker-cp container-1:/path/to/source container-2:/path/to/destination
