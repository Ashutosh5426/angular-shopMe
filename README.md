# AngularShopMe

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 16.2.7.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.


- src/
  - app/
    - core/  # Singleton services and single-use components
      - services/
        - authentication.service.ts
        - user.service.ts
        - product.service.ts
        - cart.service.ts
      - guards/
        - auth.guard.ts
      - interceptors/
        - http.interceptor.ts
      - core.module.ts
    - shared/  # Shared components, directives and pipes
      - components/
        - header/
        - footer/
        - sidebar/
      - directives/
      - pipes/
      - shared.module.ts
    - modules/  # Feature modules
      - home/
        - components/
        - home.component.ts
        - home.module.ts
        - home-routing.module.ts
      - product/
        - components/
        - product.component.ts
        - product.module.ts
        - product-routing.module.ts
      - user/
        - components/
        - user.component.ts
        - user.module.ts
        - user-routing.module.ts
    - app.component.ts
    - app.module.ts
    - app-routing.module.ts
  - assets/  # Static assets (images, styles, etc.)
  - environments/  # Environment variables
  - index.html
  - main.ts
  - styles.css