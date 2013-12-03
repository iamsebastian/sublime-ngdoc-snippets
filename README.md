sublime-ngdoc-snippets
======================

Just a small collection of snippets for creating an Angular/*ngdoc* related documentation.

You should use it in combination with [DocBlockr](https://sublime.wbond.net/packages/DocBlockr), to get a nice workflow.
Let DocBlockr create the documentation with `/**` » `[TAB]` and then add your ngdoc snippets.

Snippets
========

+ **`@ngd+`** adds a complete documentation stack of **@ngdoc**-comment

    ```js
    $ngdoc {...}  

    @name {name}  
    @requires {service}  
    @propertyOf {method}  
    @methodOf {method}  
    @function  
    @element
    @description
    @param {type}
    @return {type}
    ```
+ **`@des`** adds **@description**
+ **`@ele`** adds **@element**
+ **`@fun`** adds **@function**
+ **`@met`** adds **@methodOf** {method}
+ **`@nam`** adds **@name** {name}
+ **`@ngd`** adds **@ngdoc**
+ **`@par`** adds **@param** {type}
+ **`@pri`** adds **@private**
+ **`@pro`** adds **@propertyOf** {method}
+ **`@req`** adds **@requires** {service}
+ **`@ret`** adds **@return** {type}