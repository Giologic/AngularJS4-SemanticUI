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

