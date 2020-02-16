# ContactBook

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 9.0.2.


# Folder Structure

Component Details:
home - This component provides the implementation and functional details.
app-view - This componenet is resposible for viewing/listing all the default + new contacts created.
add-contact - This component is responsible for adding new contact.
edit-contact - This component is responsible for editing/modifying selected contact.

Total number of service(s): 
manage-contact.service - This service is the main service that has the data(JSON) of contacts and all the CRUD operations are defined inside this service. A singleton object of this service is provided within the application using Dependency Injection.

Total number of model(s): 
contact.model - This model is used for defining the structure for each Contact. i.e id, firstname, lastname, email, phone, status should be the part of each contact in the application.

## Deployed On : https://contact-book-b5cf6.firebaseapp.com/

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
