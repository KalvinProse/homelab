WIP Homelab Repo

On campus wifi for the semester so can't run my whole lab. Lot of files are wip. 

Minecraft Server

Very Basic container application. Do note persistent storage is managed via bind volumes.
Requirements
  b1.7.3.jar file

Add the Jar file to the git directory then just
  docker build -t b1.7.3 .
  docker compose up

This will start the Minecraft server with my preset configs. My current configs are for running local single player only servers. I haven't tested this with multiple users, but I imagine it would work decently well for a home network. 
