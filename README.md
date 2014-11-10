bootstrap-switch angularjs binding
==================================

Two way binding for https://github.com/nostalgiaz/bootstrap-switch via angular directive. 

Usage
=====

Inject module
-------------
```
var app = angular.module('yourApp', ['bsSwitch', ... ]);
```

Directives
----------
Instead of initializing bootstrap-switch by calling the bootstrapSwitch method, use angularjs directive style:
```
<input type="checkbox" bs-switch="foo.bar" bs-switch-size="mini" bs-switch-animate="true" />
```
"foo.bar" is the binding target which is simular to the usage of 'ng-model'
You can define any option with the directive style under pattern bs-switch-OPTION_NAME="OPTION_VALUE"
