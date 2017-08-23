# Pixabay-API-Image-Search

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 1.3.0.

A simple image search application that implements Pixabay's public API. Users search for images matching a keyword and the application returns a gallery of those images that link back to Pixabay. All images in the application are provided by Pixabay. The application implements Angular 4's Http class, Angular Material, and Masonry.js.
<p align="center">
  <br><br>
  <img src="https://github.com/Jyotsna-Singh/Angular-Pixabay-API-Image-Searcher/blob/master/src/assets/img/Demo.gif" />
</p>


## Usage

In `src\environments\environment.ts`, enter your pixabay API key in the environment constant.

    export const environment = {
    production: false,
    PIXABAY_API_KEY: 'YOUR_API_KEY_HERE',
    PIXABAY_API_URL: 'https://pixabay.com/api/?key=',
    };

## Clone/Download

`git clone https://github.com/Jyotsna-Singh/Angular-Pixabay-API-Image-Searcher.git`

## License
MIT License

<p align="center">
  <br><br>
  <img src="https://github.com/Jyotsna-Singh/Jyotsna-Singh/blob/master/assets/img/angular.png" width="300px" height="auto" />
</p>


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
