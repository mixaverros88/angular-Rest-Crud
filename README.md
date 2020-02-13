# Very simple CRUD operations with Angular

![preview image](https://raw.githubusercontent.com/mixaverros88/angular-Rest-Crud/master/icons/docker_overview.jpg)

This example combines 2 containers inside a bridge network. The first container runs the angular app and the other container the json server.

We use the bridge network in order to reach the json server without the IP address but with the container name.

### Development docker file ###
create a volume in /usr/share/nginx/html

# json-server instructions

1. Install server: npm install -g json-server
2. Navigate to the path where json server is installed (json-server-master folder).
3. Replace the file routes.json and add the file products.json (these files are stored in root folder of the project).
4. Run server (in the server folder): json-server --port 555 --routes routes.json --watch products.json 

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.
This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 6.0.8.

![preview image](https://raw.githubusercontent.com/mixaverros88/angular-Rest-Crud/master/previewImage.jpg)
