# knowledge-transfer

## Angular intro
##### Create simple 'html template driven' web form

- create a new project
- create user component
- create user model
- add selector from user component to app component's html template

#### 1. Workstation setup
  * (overall reference guide) https://angular.io/docs/ts/latest/cli-quickstart.html#!#devenv
  * install [node.js and npm](https://nodejs.org/en/download/)
  * install [VS Code](https://code.visualstudio.com/) this includes typescript 2.0
#### 2. Install angular cli
  * `npm install -g @angular/cli`
#### 3. Create new project
  * `ng new <project name>`
  * Ensure project loads up `ng serve -o`
#### 4. Create user component
   * `ng g c user` 
   *  Add user 'selector' tags to parent app.component.html which will demonstate how html can be shared across components. 
#### 5. Create user model class 
   * `ng g class user`












# Demo1

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 1.0.0.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive/pipe/service/class/module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `-prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).
Before running the tests make sure you are serving the app via `ng serve`.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
