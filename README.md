# Ngrxstore

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 10.2.0.

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

What to improve

Used all the form fields like username and email, password using reactive form validations. Here the gap in this application we didn't made any service calls to fetch the data.

## Adding Bootstrap 4

npm install --save bootstrap@next

We need to add @next to the package name because at the time of writing this post Bootstrap 4 is still in beta. The @next addition makes sure that version 4 of Bootstrap is installed, not version 3.

The NPM command installs Bootstrap 4 into the folder node_modules/bootstrap and at the same time makes sure that the dependency is added into the package.json file.

Change styles in .angular-cli.json by
        "styles": [
            "styles.css",
            "../node_modules/bootstrap/dist/css/bootstrap.css"
        ],

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.