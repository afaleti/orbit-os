# Orbit OS

Container runner distribution for AWS.

### Features

 * Drop-in CoreOS compatible with existing CoreOS clusters (fleet, etcd)
 * Includes Flotilla as light database agnostic alternative to Fleet
 * Includes light alternatives to Docker daemon: runc and krgo
 * Based on mainline Debian for fast security patches

### Setup
sudo pip install -r requirements.txt
echo "AWS_ACCESS_KEY=****************" >> .env
echo "AWS_SECRET_KEY=****************" >> .env

### Build image and upload to AWS
make install
