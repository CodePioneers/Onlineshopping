# OnlineShopping

1)Data Binding
-------
we used below:
interpolation->{{}}
ngmodel ->[(ngmode)]
Event binding for button using click and calling a method form ts file.

for ngmodel
-----
add formsModule in appmodule.ts as below
FormsModule->under imports and 
import
import { FormsModule } from '@angular/forms';
so that it activates ngmodel directive.


2)Routing
--------
.For routing to enable we have to we have to add the component {path:'welcome', component: WelcomeComponent} like this app-routing.module
.get the routing object though DI in the constructor
.Using this object implement the navigation as 

this.router.navigate(['welcome'])













This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 7.0.3.

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
