# nubotics-box

### A minimal preconfigured Vagrant box

**Installed**

- Nginx
- PHP 5.6
- MySQL
- Node v4
- Gulp, Babel
- Git

**Getting started**

Install VirtualBox and Vagrant
Add the nubotics.box file as a base box
```
vagrant box add nubotics/box path/to/nubotics.box
```
Clone this repo and cd into it
```
git clone
cd 
```
Edit vagrantfile and change the git user information
```
git config --global user.name "Your Name"
git config --global user.email "your@email.com"
```
Run vagrant
```
vagrant up --provision
```
SSH into the box
```
vagrant ssh
```

Note: As the box has been once provisioned you need to run ```vagrant up``` when starting the box again
