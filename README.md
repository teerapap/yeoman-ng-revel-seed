yeoman-ng-revel-seed
====================

A seed project combining Yeoman, AngularJS and Revel. The project is an experiment to integrate these frameworks and tools in the same project.

## Dependencies

* Revel
* Yeoman

## Notes

* The repository needs to be under `$GOPATH` because of revel.
* You needs to change the revel import path in `Gruntfile.js` before developing your project.

## Working commands

* `grunt server` - running a revel server for development
* `grunt test` - running karma tests
* `revel build` - building the overall application

## Not working

* `grunt build` command
* revel test suites
* LiveReload feature
