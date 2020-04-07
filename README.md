# Server SSH configurations and tools - Shortcuts
An extraction of useful comands and tools to configure a remote server


## Adding access through SSH key
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






