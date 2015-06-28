# Development Environment for Development Bootcamp

This is custom Ubuntu Linux setup for use during our [Development
Bootcamp][development_bootcamp] program.

## Installation Steps

1. Install [Vagrant][vagrant]
2. Install [VirtualBox][virtual_box]
3. Open your Terminal and install the necessary Vagrant plugins:
  - `vagrant plugin install vagrant-vbguest`
  - `vagrant plugin install vagrant-librarian-chef-nochef`
4. Clone this repository on your local machine:
  - `git clone https://github.com/devbootcamps/development-environment.git devbootcamp`
  - `cd devbootcamp`
5. Start the environment:
  - `vagrant up`
6. Connect to the environment via SSH:
  - `vagrant ssh`
7. Go to `/vagrant` where your files are:
  - `cd /vagrant`

[development_bootcamp]: https://www.developmentbootcamp.nl
[vagrant]: http://www.vagrantup.com/downloads.html
[virtual_box]: https://www.virtualbox.org/wiki/Downloads
