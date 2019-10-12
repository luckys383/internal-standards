1. NG-1 No sensitive information should be present anywhere except .env filesafsdfsdfs
1. NG-2 Dont use wild card for pakcage version which allow auto upgrade to major release
1. NG-3 Always convert UTC dates into selected or local timezone before displaying
1. NG-4 Single function should handle a single responsibility.
1. NG-5 Controller & Service & Factory should be defined in their own separate files
1. NG-6 Boolean functions should be prefixed with "is", "can" etc. e.g. isLoggedIn()
1. NG-7 Use getter/setter notations for functions where applicable like setUsername(), getUsername()
1. NG-8 Always use the block comments during the function declaration
1. NG-9 Only use simple filter directly in views. Complex filters calculations should be done in Controllers/Directives/Servcies
1. NG-10 Always write comments for complex part of code stetements
1. NG-11 Wrap your AngularJS components in an Immediately Invoked Function Expression (IIFE)
1. NG-12 Always turn off all custom event registered within directive element
1. NG-13 Always destroy/unbind $rootscope listeners when binded in child component and child component is being destoryed
1. NG-14 Avoid using $scope.$watch unless there is no other option
1. NG-15 Don’t pollute your $scope by creating simple function under $scope, which are not going to be used in views
1. NG-16 Use ng-bind or ng-cloak instead of simple {{ }}
1. NG-17 Use one time binding syntax and way to bind values into views
1. NG-18 Use ng-src, ng-href & ng-style in place of src, href & style attributes
1. NG-19 Do not use $ to prepend your own varibles, objects, properties and service identifiers
1. NG-20 Custom directives should not be ng-* prefixed, to avoid name collision with predefiend directive like ng-focus etc.
1. NG-21 Use already built in angular wrappers like $timeout, $interval, $window, $document, $http & $location
1. NG-22 Define common messges, warning, confirmation text at single place, so we can override/change them easily if required
