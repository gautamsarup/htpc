# htpc

Log out from the current SSH session by running logout. On your local machine run ssh-keygen.

Upon entering this command, you will be asked where to save the key. Just press Enter to save it on its default location.

Append the public key to your authorized_keys file on the Raspberry Pi by sending it over SSH:

On your local machine run `ssh-keygen

Append the public key to your authorized_keys file on the Raspberry Pi by sending it over SSH:

```ssh-copy-id pi@<RASPBERRY_IP>
```

```curl -fsSL https://get.docker.com -o get-docker.sh
sudo sh get-docker.sh
```
```
sudo curl -SL https://github.com/docker/compose/releases/download/v2.20.2/docker-compose-linux-x86_64 -o /usr/local/bin/docker-compose
sudo chmod +x /usr/local/bin/docker-compose
