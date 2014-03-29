To run the application with the REST services:
============================================
Make sure [Node.js](http://nodejs.org/) and [MongoDB](http://www.mongodb.org/) are installed on your system

1. Go to the angular-directory/server folder and run:

* `npm install`

2. Run:

* `node server`

3. In app.js, change:

``` bash 
angular.module('myApp', [
    'ngRoute',
    'myApp.controllers',
    'myApp.memoryServices'
]).
```

to:
``` bash
* `angular.module('myApp', [
    'ngRoute',
    'myApp.controllers',
    'myApp.restServices'
]).`
```
4. To avoid cross-domain issues, access the application from the following URL:

* `http://localhost:3000`
