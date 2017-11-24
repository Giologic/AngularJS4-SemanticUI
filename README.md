## AngularJS4 with Semantic UI Project Template

This repository is a project template for creating applications using Angular JS4 and Semantic UI CSS Framework

### Installation

```markdown
npm install -g @angular/cli
```

### Creating an Angular Project for Deployment

```markdown
ng new PROJECT-NAME
cd PROJECT-NAME
ng serve
```

Default host is http://localhost:4200/

### Installing Semantic UI


```markdown
npm install --save jquery
npm install --save-dev @types/jquery

npm install -g gulp
npm install semantic-ui --save
cd semantic/
gulp build
```

In angular-cli.json file add these lines:

```markdown

"styles": [
        "../semantic/dist/semantic.css",
      ]
      
"scripts": [
  "../node_modules/jquery/dist/jquery.min.js",
  "../semantic/dist/semantic.js"
]
 ```



# AngularJS4SemanticUI

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 1.5.4.

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
