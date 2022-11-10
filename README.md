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

## website url
https://8002-magento2remote-m245-qflp51la7c2.ws-us75.gitpod.io/

# Credit
https://github.com/nemke82/magento2gitpod

https://github.com/develodesign/magento-gitpod


## GA4


    <!-- Google Tag Manager -->
    <script>(function(w,d,s,l,i){w[l]=w[l]||[];w[l].push({'gtm.start':
    new Date().getTime(),event:'gtm.js'});var f=d.getElementsByTagName(s)[0],
    j=d.createElement(s),dl=l!='dataLayer'?'&l='+l:'';j.async=true;j.src=
    'https://www.googletagmanager.com/gtm.js?id='+i+dl;f.parentNode.insertBefore(j,f);
    })(window,document,'script','dataLayer','GTM-PNCNZ6H');</script>
    <!-- End Google Tag Manager -->



**body**

    <!-- Google Tag Manager (noscript) -->
    <noscript><iframe src="https://www.googletagmanager.com/ns.html?id=GTM-PNCNZ6H"
    height="0" width="0" style="display:none;visibility:hidden"></iframe></noscript>
    <!-- End Google Tag Manager (noscript) -->
