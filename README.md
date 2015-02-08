# Ember-velocity-issue

This repo is used to demonstrate an issue with ember-velocity-mixin that was introduced in Ember 1.10.0.

```
Assertion Failed: Velocity.js must be installed to use this mixin.
```

## Steps to reproduce

1. `git clone git@github.com:beerlington/ember-velocity-dependency-issue.git`
2. `cd ember-velocity-dependency-issue`
3. `ember install`
4. `ember test`

You should see the following error:

```
not ok 7 PhantomJS 1.9 - XHelloComponent: it renders
    ---
        actual: >
            null
        message: >
            beforeEach failed on it renders: Assertion Failed: Velocity.js must be installed to use this mixin.
        Log: >
    ...
ok 8 PhantomJS 1.9 - JSHint - unit/components: unit/components/x-hello-test.js should pass jshint
```
