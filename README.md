
# Data Binding in Angular

This project was built in order to show off the common features of angular databinding

You can view the [Data Binding Tutorial](https://simonable.github.io/angular-data-binding/) here.

### Steps for Deploying Angular Projects to Github Pages

#### In terminal:

* Have or create new angular project

* ng new example-project

* cd example-project

* ng serve —open

* ng build

* ng build ‘example-project’ —prod —vendor-chunk=true

* sudo npm i -g angular-cli-ghpages

#### In GitHub: open up GitHub:

* create a new repository
* Note: There is no need to initialize GitHub pages in the settings. This will be done in your terminal!

#### In terminal:

* git init

* git add README.md

* git commit -m "Uploading Deploy"

* git remote add origin https://github.com/SimonAble/example-project.git

* git push -u origin master (This will be the place where the angular app is served on GitHub pages)

* ng build --prod --base-href https://simonable.github.io/example-project/

* ng build --prod --base-href=/example-project/

* sudo ngh --dir=dist/example-project

### There you go! Navigate to the github page where you've deployed your project and it should be up and running!

***


# DataBindingDeploy

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 7.1.1.

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
