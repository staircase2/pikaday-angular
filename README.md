Angular Pikaday - Directive
========

A production ready date picker that doesn't require jQuery.

Key aspects of this directive:

  * Ensure proper date object on the model
  * Validation
  * Quick changes to date picker options (locazation/i18n etc)
  * Much more then just wrapping onSelect in a $scope.$apply()


## Documentation
_Yeah... need to fill this out..._

For now look in app/ for an example of how to use it.

Want to use Pikadaytime to allow time selection, just add this override to your bower.json
```json
"overrides": {
  "angular-pikaday": {
    "dependencies": {
      "angular": "1.3.0-beta.18",
      "pikaday-time": "~1.2.0",
      "moment": "~2.8.1"
    }
  }
}
```

## Contributions
If there are better ways to do things, please send in pull requests. I'd love to learn. Or sending in issues works to, and I'll try to fix them as I have spare cycles.

Grunt default task is to fire up a node server with auto watch updates for quick development. Run grunt in the root directory.

## Authors
* Staircase 2 / SquareCrumbs

