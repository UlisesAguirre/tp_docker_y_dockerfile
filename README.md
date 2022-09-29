# tp_docker_y_dockerfile
The underlying OS architecture that we are going to use for this container is ubuntu in its 20.04 version

Once we have specified that, we install several dependencies in a specific order so as to avoid possible conflicts.

After that, we place ourselves in the directory where the default nginx html file is located. There we use the command COPY to copy our index.html in the workdir we've specified in the previous command

Last, we define and use the default nginx command to start the container

Devs
- Aguirre, Ulises
- Bruzzo, Luca
- Cechetto, Juan Cruz
- Brunetti, Marco
