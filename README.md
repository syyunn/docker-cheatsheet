#### Remove all Exited Containers
    sudo docker ps -a | grep Exit | cut -d ' ' -f 1 | xargs sudo docker rm

#### Ref t/ Docker Compose Syntax
    https://kapeli.com/cheat_sheets/Dockerfile.docset/Contents/Resources/Documents/index
    