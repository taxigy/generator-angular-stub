# generator-angular-stub

A Yeoman generator for Angular stub projects.

## Quick start

Install:

```sh
$ git clone https://github.com/taxigy/generator-angular-stub
$ npm install
$ npm link
```

Scaffold a new project:

``` sh
$ yo angular-stub
```

Then do stuff with `index.html`. Out of the box, it has

1. Twitter Bootstrap added for basic styling.
1. Angular and ng-router added as dependencies.
1. Some basic routing (non-HTML5 mode) and templating with `text/ng-template`s.
1. Some basic service to persist data across multiple controllers, keeping in mind that each time a controller is attached to `ng-view` it's being reinstantiated, thus `$scope` reinitialized.

Can be used without Node server running. All dependencies are added via external scripts from CDN.

## License

MIT
