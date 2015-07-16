Manifest
===========

Manifest file for use with repo tool to pull Protection Profiles

## Quickstart
Pull all protection profiles:

````
 $ repo init -u https://github.com/zsmi/manifest.git
 $ repo sync 
 $ repo forall -c "git submodule init; git submodule update"
````
Sync latest changes:
````
 $ repo sync
 $ repo forall -c "git submodule init; git submodule update"
````
Pull in upstream transforms changes to all projects:
````
 $ repo forall -c "git submodule update --remote"
````

