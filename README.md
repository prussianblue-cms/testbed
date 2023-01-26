# PrussianBlue testbed
This repo offers commands to simplify the instancing and testing of PrussianBlue sites from scratch.

## Dependencies

* DDEV 1.21 or later
* Docker
* ZSH

## Commands

### spawn-test-site

* Destroys the DDEV containers
* Deletes the files in ./prussianblue
* Clones the project-template
* Starts the DDEV instance
* Installs composer dependencies
* Gives the DDEV instance a random, 8-character name
* Installs the site via Drush