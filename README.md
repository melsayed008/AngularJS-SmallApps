# AngularJS-SmallApps
Walmart API SearchProduct

AngularJS is used in developing this web application: AngularJs is MV*/MVC JavaScript framework, very powerful in performance and browsing, works on the client side.

Consuming Walmart Search API and Recomeneded Product Api services provided by Walmart Open Lab, to search for any product in Walmart.com!!

1)Type  the name of product, select/click "Get Product!" button.
2) The SearchProductMethod Function will be called, passing the product Name as argument using the 2-way data binding "ng-model".
3) Within the Function, we use the Angular Service ($resource) to call the Search Product Api Service, using a Registered ApiKey and the query name.
4) 10 Products relevance to the query name, are returned in JSON Format to the User.
5) All Products Information are displayed using $scope and Angular Directives (ngRepeat, interpolation"{{}}").
6) Then, 10 Recommended Products are returned for the first Item using the Item Id number.
7) The Recommended Products are ordered by CustomerRating starting with highest rating, using the Angular Filter "orderBy".
8) List of the Recommended Products ordered by customer rating, displayed horizontally at the bottom of the page after the searched results.



!!!!!!!!!!!!! Thank you  !!!!!!!!!!!!!!
