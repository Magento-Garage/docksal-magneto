# Docksal Magento 2 Boilerplate #

If docksal is not already installed:

Follow : https://docksal.io/installation  


 `fin project create --repo=https://github.com/Magento-Garage/docksal-magneto.git --name=<PROJECT_NAME>`  
 
 `cd <PROJECT_NAME>`
 
## Add existing magento repo  ##
Optional:  `fin config set PROJECT_REPO=<git_repo>`

 `fin init`  
*It will prompt for username/password for repo.magento.com if your code repo isn't having auth.json*  
Follow: https://devdocs.magento.com/guides/v2.3/install-gde/prereq/connect-auth.html

To enable redis cache:
`fin redis enable`  
  
You can configure Magento 2 installation variables in .docksal/docksal.env file.