# Magento 2.4.5 Development Environment

This repository contains a Gitpod configuration for a Magento 2.4.5 development environment. 

The goal is to have a simple way of creating different configuraitons for Magento 2 dev environments, that begin quickly and require no further input to being using. 

 
# Use in an Existing Project
- Copy the ```Gitpod``` folder, ```gitpod.yml``` and ```.gitpod.Dockerfile``` files to an existing Magento 2 repository to use on your own project.

# Installing an existing database
- Uncomment and complete the code [here](https://github.com/magento2remote/m245/gitpod/m2-install.sh#L28) to have the script import an existing Magento 2 database. 
- Replace ```staging-domain.com``` in the file with your Magento 2 url, this will be replaced with the current gitpod workspace URL before import.
- Compress your .sql file and place into the gitpod folder as ```magento-db.sql.zip```
- Set INSTALL_MAGENTO = No in the [.gitpod.Dockerfile](https://github.com/magento2remote/m245/blob/master/.gitpod.Dockerfile)


# Credit
https://github.com/nemke82/magento2gitpod

https://github.com/develodesign/magento-gitpod
