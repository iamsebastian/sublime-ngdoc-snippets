sublime-ngdoc-snippets
======================

Just a small collection of snippets for creating an Angular/*ngdoc* related documentation.

You should use it in combination with [DocBlockr](https://sublime.wbond.net/packages/DocBlockr), to get a nice workflow.
Let DocBlockr create the documentation with `/**` » `[TAB]` and then add your ngdoc snippets.

See the official Angular wiki for notes about writing Angular related docs: [Writing AngularJS Documentation](https://github.com/angular/angular.js/wiki/Writing-AngularJS-Documentation).

Snippets
========

+ **`$ngd+`** adds a complete documentation stack of **@ngdoc**-comment

    ```js
    $ngdoc {...}  

    @name {name}  

    @deprecated
    @scope
    @eventType emit|broadcast
    @link
    @requires {service}  
    @propertyOf {method}  
    @methodOf {method}  
    @function  
    @element
    @elementOf {type}
    @description
    @param {type}
    @returns {type}
    ```
+ **`$dep`** adds **@deprecated**
+ **`$des`** adds **@description**
+ **`$ele`** adds **@element**
+ **`$eof`** adds **@elementOf** {type}
+ **`$eve`** adds **@eventType** emit|broadcast
+ **`$fun`** adds **@function**
+ **`$lin`** adds **@link**
+ **`$met`** adds **@methodOf** {method}
+ **`$nam`** adds **@name** {name}
+ **`$ngd`** adds **@ngdoc**
+ **`$par`** adds **@param** {type}
+ **`$pri`** adds **@private**
+ **`$pro`** adds **@propertyOf** {method}
+ **`$req`** adds **@requires** {service}
+ **`$ret`** adds **@returns** {type}
+ **`$sco`** adds **@scope**
+ **`$thi`** adds **@this**