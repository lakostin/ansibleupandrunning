# ansibleupandrunning

# Create self-signed certificates
openssl req -x509 -nodes -days 3650 -newkey rsa:2048 -subj /CN=localhost -keyout files/nginx.key -out files/nginx.crt

# Ch3

# Install python lib for dynamic inventory
sudo pip install paramiko

# Get info about vagrant2 from dynamic inventory
./inventory/vagrant.py --host=vagrant2

# Get hosts from dynamic inventory
./inventory/vagrant.py --list
