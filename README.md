# pihole-docker-isolated
Setup script to install pihole to a docker container, running on its own IP.

I use this to create and run a pihole on my NAS.

To redirect all network devices to pihole, set the dhcp dns on the router to the pihole ip (assuming you are running dhcp).

aAl inspiration comes from here:
http://tonylawrence.com/posts/unix/synology/free-your-synology-ports/

Thanks!


to run use:
sudo docker-compose up -d
