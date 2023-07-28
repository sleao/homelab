# Services

Basically I run a bunch of different stuff on my homelab, mostly for learning and trying out different stuff and a complete media server that simplifies acquiring and watching movies and tv shows. This folder contains separate folders for the different stacks of apps. 

If you want to get started, Portainer might be the best place to start, as I use it for Docker management, so instead of running Docker from the CLI, I just manage everything with a GUI. You can then add the other stacks easily from Portainer, just make sure you create the folders and networks.

I also use Nginx Proxy Manager as a GUI to Nginx, which is where I setup SSL and different domains for each service, and separate them between what I want to be public and what I want to limit access to my home network.
