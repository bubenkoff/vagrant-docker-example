# vagrant-docker-example

Example of basic Vagrant Docker provider usage

> Running Docker as a provider in non-Linux environment will require the installation on a Docker Host VM, where Docker containers will run.

> Because of an error with current version of `hashicorp/boot2docker` (rsync has been removed), it has been replaced by `dduportal/boot2docker`.

## Installation

### VirtualBox

Install VirtualBox from: https://www.virtualbox.org/wiki/Downloads

### Vagrant

Install Vagrant using: http://vagrantup.com/downloads.html

### Docker

If you are using Linux, install Docker: http://docs.docker.com/linux/step_one/

On Mac and Windows, install Docker Toolbox from: https://www.docker.com/toolbox

If you prefer, you can install Docker on Mac using `homebrew`:

    brew install docker
	brew install docker-machine
	brew install docker-compose

### Run Vagrantfile

Clone this repo.

From repo folder:

    vagrant up

    # on Mac and Windows, you will be asked for a password, enter: tcuser
    # you will be asked for password twice for 2 folders to sync

    vagrant ssh  # user tcuser password again

    # enjoy your docker 'virtual' machine!
