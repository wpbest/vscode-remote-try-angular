# vscode-remote-try-angular

Angular sample project for trying out the VS Code Remote - Containers extension

Copyright (c) wpbest.io. All rights reserved.
Licensed under the MIT License. See LICENSE for license information.

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 8.0.6.

## Documentation

[Node.js](https://nodejs.org/en/docs/)

[Angular](https://angular.io/)

[AngularCLI](https://cli.angular.io/)

[RxJS](http://reactivex.io/rxjs/)

[VSCode Remote Development](https://code.visualstudio.com/docs/remote/remote-overview)

## Install global packages: Angular CLI

```
npm install -g @angular/cli  
```
## common ng new command switches

### --minimal

The minimal option creates a minimal angular project. No testing files included and inline template code for components.

### --inline-template

The inline-template option will generate inline HTML inside the component ts file.

### --inline-style

The inline-style option will generate inline CSS inside the component ts file.

### --style=[css | scss | less | sass | styl]

The style option specifies what CSS preprocessor is used in building the project. the options are: css, scss, less, sass, styl.

### --routing

The routing option generates a file app-routing.module.ts file.

### --prefix=appname

By default all your component selector prefixes are set to app. The prefix option

### --skip-git

Creates a new project without a Git repository.

## Code scaffolding
```
ng new vscoderemotetryng --routing --style scss --enable-ivy --skip-install --skip-git
CREATE vscoderemotetryng/README.md (1034 bytes)
CREATE vscoderemotetryng/.editorconfig (246 bytes)
CREATE vscoderemotetryng/.gitignore (629 bytes)
CREATE vscoderemotetryng/angular.json (3600 bytes)
CREATE vscoderemotetryng/package.json (1290 bytes)
CREATE vscoderemotetryng/tsconfig.json (435 bytes)
CREATE vscoderemotetryng/tslint.json (1988 bytes)
CREATE vscoderemotetryng/browserslist (429 bytes)
CREATE vscoderemotetryng/karma.conf.js (1029 bytes)
CREATE vscoderemotetryng/tsconfig.app.json (267 bytes)
CREATE vscoderemotetryng/tsconfig.spec.json (270 bytes)
CREATE vscoderemotetryng/src/favicon.ico (5430 bytes)
CREATE vscoderemotetryng/src/index.html (304 bytes)
CREATE vscoderemotetryng/src/main.ts (372 bytes)
CREATE vscoderemotetryng/src/polyfills.ts (2838 bytes)
CREATE vscoderemotetryng/src/styles.scss (80 bytes)
CREATE vscoderemotetryng/src/test.ts (642 bytes)
CREATE vscoderemotetryng/src/assets/.gitkeep (0 bytes)
CREATE vscoderemotetryng/src/environments/environment.prod.ts (51 bytes)
CREATE vscoderemotetryng/src/environments/environment.ts (662 bytes)
CREATE vscoderemotetryng/src/app/app-routing.module.ts (245 bytes)
CREATE vscoderemotetryng/src/app/app.module.ts (393 bytes)
CREATE vscoderemotetryng/src/app/app.component.scss (0 bytes)
CREATE vscoderemotetryng/src/app/app.component.html (1152 bytes)
CREATE vscoderemotetryng/src/app/app.component.spec.ts (1128 bytes)
CREATE vscoderemotetryng/src/app/app.component.ts (222 bytes)
CREATE vscoderemotetryng/e2e/protractor.conf.js (810 bytes)
CREATE vscoderemotetryng/e2e/tsconfig.json (214 bytes)
CREATE vscoderemotetryng/e2e/src/app.e2e-spec.ts (646 bytes)
CREATE vscoderemotetryng/e2e/src/app.po.ts (251 bytes)
```

## Run

```
npm intsall
ng serve -o
```

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).