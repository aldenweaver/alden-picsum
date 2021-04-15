# Alden Picsum

An Angular app (using TypeScript) made to query the Lorem Picsum API. The app will then display a list of photos by Alejandro Escamilla. The user can click on images and a window will pop up with an enlarged image and options to navigate back and forth between images.

Steps & Algorithm:
1. Create an empty Angular app with a basic component.
2. Implement picture list component with static data.
   2a. Write tests for picture list component data loading.
3. Call Lorem Picsum's API list endpoint (https://picsum.photos/list).
   3a. Filter photos by author 'Alejandro Escamilla'.
   3b. Use picture list component to display photos.
   3c. Write tests to ensure correct API connection, error handling, filtering, and picture list component data loading/display.
4. Implement modal window component to pop up and display photo when enlarge button is clicked.
   4a. Write tests for pop up, button, & data display.
5. Implement photo enlargement in modal window component.
   5a. Write tests for photo enlargement.
6. Implement forward & backward navigation between photos in modal window component.
   6a. Write tests for forward & backward navigation.

Extra:
7. Improve look & feel.
8. Implement additional features, functionality, & modularity. Write tests for anything new.

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 9.0.7.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
