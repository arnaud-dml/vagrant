## Environment installation
Setting up an Ubuntu environment with Docker using Vagrant (require Oracle VM VirtualBox)

#### Initializing
```
vagrant init ubuntu/trusty64
```

#### Boot the Vagrant environment & Provisioning (Up And SSH)

This provisionning allow you to automatically install **docker** & **docker-compose**

```
vagrant up
vagrant up --provision
vagrant ssh
```

#### Shut down the running machine (Halt)
```
vagrant halt
```
