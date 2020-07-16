# Server SSH configurations and tools - Shortcuts
An extraction of useful comands and tools to configure a remote server


## Adding access through SSH key
It is usefull for allowing access without password prompt in ssh, Visual Studio Code and many other applications, while improving security during the authentication.

### Generate RSA key pair
The command is:

`ssh-keygen`

Default configurations is 2048 bit RSA key, 
For an higher protection key and use 4096 bit RSA keys use:

`ssh-keygen -b 4096`

Follow the procedure and choose a user password.

### Transfer key to the server
Easy tool to transfer the public key to the server is this command:

`ssh-copy-id username@remote_host`

### Copy public RSA key to Keyboard
cat ~/.ssh/id_rsa.pub | pbcopy

# Docker references

## Load an image 
docker load < my-docker-image.img

## Lunch Docker
docker-compose up


