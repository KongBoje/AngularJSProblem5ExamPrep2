Question 1.

Describe the term Single Page Application and why it is relevant for modern web-applications

Answer 1.

A single-page application is a web application or web site that fits on a single web page with the goal of providing a user experience similar to that of a desktop application. In an SPA, either all necessary code – HTML, JavaScript, and CSS – is retrieved with a single page load, or the appropriate resources are dynamically loaded and added to the page as necessary, usually in response to user actions. The page does not reload at any point in the process, nor does control transfer to another page, although the location hash can be used to provide the perception and navigability of separate logical pages in the application, as can the HTML5 pushState() API. Interaction with the single page application often involves dynamic communication with the web server behind the scenes.

Question 2.

Describe how SPA's are implemented with AngularJS

Answer 2.

SPA's are implemented via making controllers which are responsible for a single type of data consumed by the AnglarJS. The models passed by the controllers should be lean, containing only data relevant to the controllers purpose.
With angular you also make a module with a name and then implements it in your HTML site with the command ng-app="name". This also makes you able to use other types of angular commands like ng-controller, ng-show, ng-model etc.
The routing is what's best known to make the application to an SPA.

Question 3.

Explain about Controllers and Routing in AngularJS

Answer 3.

In Angular, a Controller is defined by a JavaScript constructor function that is used to augment the Angular Scope.
When a Controller is attached to the DOM via the ng-controller directive, Angular will instantiate a new Controller object, using the specified Controller's constructor function. A new child scope will be created and made available as an injectable parameter to the Controller's constructor function as $scope.
If the controller has been attached using the controller as syntax then the controller instance will be assigned to a property on the new scope.

The ng-route module helps your application to become a Single Page Application.
Routing in AngularJS is if you want to navigate to different pages in your application, but you also want the application to be a SPA (Single Page Application), with no page reloading, you can use the ng-route module.
The ng-route module routes your application to different pages without reloading the entire application.
