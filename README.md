# Bash Install Scripts

## Install scripts for dev and prod servers

This repository holds the install scripts I use on development and production servers.

For development I use Vagrant boxes running the bare Ubuntu Trusty box for Virtualbox.

Production servers will also be Ubuntu Trusty, but will largely run on Digital Ocean or other cloud-based services.

## To use with a Vagrant box

1. Install the bare Ubuntu Trusty box or a compatible image
2. Copy the desired Dev install script and the resources directory to your shared folder
3. Type `vagrant up` if the box isn't running
4. If your shared folder has files set to +x, type `./install.sh` to run the script. If not, type `/bin/bash install.sh
`
5. Follow the prompts.

Contact me with questions or comments via [email] (jason@jasonsbarr.com) or [Twitter] (https://twitter.com/jasonsbarr).
