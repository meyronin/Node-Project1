# Node Project

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 16.2.6.

The [node_module] folder must be added or generated in the base folder for it to work. 
Please refer to this schema:

project-root/
|-- backend-nodejs/
|   |-- src/
|-- frontend-angular/
|   |-- src/
|-- node_modules/
|-- ...

## Development server

### IMPORTANT: You MUST use `npm start` and not `ng serve`, as `npm start` will run both frontend and backend.

Run `npm start` from the [frontend-angular] folder or run `npm --prefix frontend-angular start` from the source folder. 
Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

If it doesn't work, make sure that you have concurrently (`npm install -g concurrently`)

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.
