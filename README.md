# docker-unifi-network-app
Docker compose and systemd files for docker-unifi-network-controller
Create mongo-db and unifi directory in the same directory as this README

Look at the systemd file and place this directory /opt/, or place in a location of your choice.  Edit systemd file appropriately
The compose file is set to use the macvlans.  Remove IP and set network to "host"

