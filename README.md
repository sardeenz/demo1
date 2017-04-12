# knowledge-transfer

## Angular intro - Create simple 'html template driven' web form
##### Demo1 illustrates sharing html templates across components via the selector as a tag element. 

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
   *  Add user 'selector' tags to parent app.component.html which will demonstate how html can be shared across components. Put `<app-form></app-form>` inside app.component.html template


- tips
   - use ng -v to check versions of cli
   - remember that angular-cli is very different than angular/cli
   - be sure to be on angular-cli 1.0.0
   - refer to https://github.com/angular/angular-cli#updating-angular-cli to reinstall

   