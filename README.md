#### Remove all Exited Containers
    sudo docker ps -a | grep Exit | cut -d ' ' -f 1 | xargs sudo docker rm
    