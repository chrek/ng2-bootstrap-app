# Ng2BootstrapApp: Using Bootstrap in Angular


This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 1.3.2.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `-prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).
Before running the tests make sure you are serving the app via `ng serve`.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).

##   ------------------BOOTSTRAPPING ------------------------------------------

## Adding Bootstrap from CDN

To include Bootstrap in your project we need to add two files:
- Bootstrap CCS file
- Bootstrap JavaScript file

Open file src/index.html and insert the link element at the end of the head section to include the Bootstrap CSS file
- a script element to include jQuery at the bottom of the body section
- a script element to include the Bootstrap JavaScript file at the bottom of the body section

Now you can use Bootstrap (jumbotron, panel, etc) inside your component templates.

## Using Bootswatch
Connect to [Bootswatch](https://bootswatch.com/). On the Website just select a theme (for example, Cerulean) and click on the “Download” button. The corresponding bootstrap.min.css file opens in another Browser window, so that you can copy the[ URL](https://bootswatch.com/cerulean/bootstrap.min.css).
Go back to index.html and replace the string which is assigned to the href attribute of the link element with this new URL:

## Using Bootstrap 4 Cards

Bootstrap 4 Cards are more mobile friendly compared to panels, thumbnails and wells.

+ Implemented Card with background color.
 