Directives Configuration Synopsis
================================
Directives can be declared as HTML Elements’ attributes. In this topic you will learn about how configure your directives via the directive declaration attribute.

Note on Directives
==================
Directives is a central architectural AngularJS concept and component. Although it starts relatively simple, it quickly becomes a very complex subject; your success in using AngularJS will be directly linked to your ability to use directives correctly. Also, your success in learning directives depends on your ability to learn the basics very well. Therefore, do not cut any corners here, this is a critical topic.

Material
========
Computer, browser, plunker account.

Concepts
========
* Things to read but not to worry if you do not understand it.
  * None (this topic is important and you must ensure you get it!)
* [AngularJS Scope](https://docs.angularjs.org/guide/scope).
* [AngularJS Directive Introduction](https://github.com/globant-ui/angular-bootcamp/tree/master/directives-introduction).
* [Angular Element interface](https://docs.angularjs.org/api/ng/function/angular.element). You will need this to help you with the automated tests.


Lesson Synopsis
===============
* Study the concepts.
* Address the questions and exercises in the Learning Objectives section.
* Notify your instructor when you have completed the exercises in the Learning Objectives section.

Learning Objectives
===================
Collect your answers to the questions and exercises below and forward them to your instructor. Please include links to the plunkers you wrote.
* What is the difference between JQuery and the AngularJS jQuery lite?
* How does AngularJS decides whether to use JQuery or AngularJS jQuery lite?
* Provide a simple example of a couple of built-in directives declarations and explain how they are being configured.
* Why does the [Angular Boot Camp  - Directive Configuration - Broken](http://plnkr.co/edit/GJy7V5) plunker fails. Hint: there are three bugs for you to find!
* What is the scope used by my-directive?
* Fork the [Angular Boot Camp  - Directive Configuration - Broken](http://plnkr.co/edit/GJy7V5) plunker. Re-factor it to declare my-directive as an HTML Element. 
* Re-factor your plunker to wrap the my-directive element with an HTML div element, having its own controller. What is the scope used by my-directive in this new context? 
* Are there any risks in having directives using their parents’ scopes?
* Re-factor your plunker to have my-directive  to use its own scope.
* What would be a reason for you to define a controller to have an isolated scope? Give an example.
* Describe the mechanisms to configure a directive with an isolated scope.
* Why is the [Angular Boot Camp  - Directive Configuration - Invalid Scope](http://plnkr.co/edit/sTHMY6) plunker failing?
* Why can’t we configure the a directive’s isolated scope with hard coded values?
* Fork the [Angular Boot Camp  - Directive Configuration - Invalid Scope](http://plnkr.co/edit/sTHMY6) plunker. Fix it and re-factor it to use an isolated scope configured from its HTML Element attributes.
* When using the @ scope data-binding strategy you can also data-bind values from enclosing scopes by using interpolation {{}} in the attribute value. Please elaborate on this statement.
* Fork the [Angular Boot Camp  - Directive Configuration - Alternate scope names](http://plnkr.co/edit/Pf6xcM) plunker. Re-factor it to use attribute names different from that of its scope.
* Why do the unit tests in the [Angular Boot Camp  - Directive Configuration - Failing Tests](http://plnkr.co/edit/0imcbk) plunker fail?
* Fork the [Angular Boot Camp  - Directive Configuration - Failing Tests](http://plnkr.co/edit/0imcbk) plunker. Fix and re-factor it to configure its scope from values in its ancestors’ scopes.
* Identify the scopes used in the [Angular Boot Camp  - Directive Configuration - Challenging Scope Question](http://plnkr.co/edit/DOCM5S) plunker.
