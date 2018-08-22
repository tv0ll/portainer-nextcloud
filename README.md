# portainer-nextcloud
This repository is for use within Portainer's App Template section, for creating a template with the 'Compose Stack' Option.
If you are planning on using this for production, please fork it to a private repository so you can use a different username/password than the default: nextcloud.
This does not include encyption!

By running these docker-compose files, you will get an instance of NextCloud, Apache, and a MariaDB server.
All of these instances are pulled from their official repos within Docker Hub.

## Instructions

Since Portainer doesn't come with an App Template for NextCloud, you can use these docker compose files in order to build the stack in seconds. 

* On your Portainer dashboard, select the App Templates option on the last hand side.
* Once inside of the App Templates section, find the option 'Add Template'
* After the title and the description, choose the template type as 'Compose stack'
* Name would be NextCloud, and Logo for NextCloud can be: https://cdn.rawgit.com/docker-library/docs/e563b6cd3d797e2b3695576d20041227d1fb7536/nextcloud/logo.svg
* Change the Platform to Linux
* Select Storage as the category
* The Github Repo will be: https://github.com/tvollscw/portainer-nextcloud
* The Compose File Path will be: docker-compose.yml
* Create the template, search for it in your App Template Index, select the new NextCloud Template, then within it you will have the option to Deploy the Stack.
