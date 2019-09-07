## Mandatory 

[**NG-1**](docs/ng-1.md) Use custom lister(Window Events) instead of `broadcast & emit`

[**NG-2**](docs/ng-2.md) Use wrapper class for check true, isDefined, isString, isArray and etc.

**NG-3** Use more virtual memory instead of $scope.

**NG-4** Use one time binding syntax(Scope resolutions operator) if no need of two-way binding.


## Recomended
**NG-1** No sensitive information should be present anywhere except .env files

**NG-2** Dont use wild card for pakcage version which allow auto upgrade to major release

**NG-3** Always convert UTC dates into selected or local timezone before displaying

**NG-4** Single function should handle a single responsibility.

**NG-5** Controller & Service & Factory should be defined in their own separate files

**NG-6** Boolean functions should be prefixed with "is", "can" etc. e.g. isLoggedIn()

**NG-7** Use getter/setter notations for functions where applicable like setUsername(), getUsername()

**NG-8** Always use the block comments during the function declaration

**NG-9** Only use simple filter directly in views. Complex filters calculations should be done in Controllers/Directives/Servcies

**NG-10** Always write comments for complex part of code stetements

**NG-11** Wrap your AngularJS components in an Immediately Invoked Function Expression (IIFE)

**NG-12** Always turn off all custom event registered within directive element

**NG-13** Always destroy/unbind $rootscope listeners when binded in child component and child component is being destoryed

**NG-14** Avoid using $scope.$watch unless there is no other option

**NG-15** Don’t pollute your $scope by creating simple function under $scope, which are not going to be used in views

**NG-16** Use ng-bind or ng-cloak instead of simple {{ }}

**NG-17** Use ng-src, ng-href & ng-style in place of src, href & style attributes

**NG-18** Do not use $ to prepend your own varibles, objects, properties and service identifiers

**NG-19** Custom directives should not be ng-* prefixed, to avoid name collision with predefiend directive like ng-focus etc.

**NG-20** Use already built in angular wrappers like $timeout, $interval, $window, $document, $http & $location

**NG-21** Define common messges, warning, confirmation text at single place, so we can override/change them easily if required

