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
  * Ensure project loads up `ng serve -o` (-o is for 'open' which launches your browser at http://localhost:4200)
#### 4. Create user component
   * `ng g c user` (shorthand for: `ng generate component user`)
   *  Add user 'selector' tags to parent app.component.html which will demonstate how html can be shared across components. Put `<app-form></app-form>` inside app.component.html template

#### 5. Proceed to [lesson 2](https://github.com/sardeenz/demo2)

- tips
   - use ng -v to check versions of cli
   - remember that @angular-cli is outdated and the new version is @angular/cli
   - be sure to be on angular-cli 1.0.0
   - refer to https://github.com/angular/angular-cli#updating-angular-cli to reinstall

   