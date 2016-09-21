
# dexec(Docker exec)

Will find a Docker container and run commands in them.

It's like:

- `docker ps | grep` to find a container id.
- `docker exec -it $container_id bash`

How to use:

`dexec img [arg1, arg2, ...]`, where `img` is the image name(or something else to grep)

If you specify other parameter, it will be run, for example `dexec mysql ip addr show` will find an MySQL container and show the ip address of it.

If more the one contianer be found, it will show the list and let you to choice one to run in.

If you choice `0`, the commands will be run in all containers.

[![asciicast](https://asciinema.org/a/3cvr9hvzy9w7niscwyv23kcu9.png)](https://asciinema.org/a/3cvr9hvzy9w7niscwyv23kcu9)