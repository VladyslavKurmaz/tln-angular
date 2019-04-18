# Angular (7) skeleton application

## Getting started

### Attach to the existing project

* Add skeleton as subtree
```
git remote add tln-angular https://github.com/project-talan/tln-angular.git
git subtree add --prefix static/html tln-angular master --squash
```
* Update to get latest version
```
git subtree pull --prefix static/html tln-angular master --squash
```

### or Fork/clone repository

To develop standalone project, just clone repository or create fork using your account

### Refresh configuration

#### Prepare .env file
* Copy **.env.template** file to **.env**
* Fill environment variables
```
COMPONENT_ID=io.company.project
COMPONENT_VERSION=19.4.0

COMPONENT_PARAM_HOST=company.io
COMPONENT_PARAM_LSTN=0.0.0.0
COMPONENT_PARAM_PORT=80
COMPONENT_PARAM_PORTS=443
```

#### Update project id

* replace all accurencies of string **'org.talan.angular'** to you project id (for example **'com.company.project'**) inside angular.json


### HTTP/HTTPS

* During deployment procedure, create ssl folder under 


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

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
