<!DOCTYPE html>
<html lang="en">
<head>
    <title>Angular JS Full Name Program</title>
    <script type="text/javascript"
    src="https://ajax.googleapis.com/ajax/libs/angularjs/1.8.2/angular.min.js">
    </script>
    <script>
        var app=angular.module("myApp",[]);
        app.controller("myCntrl",function($scope){
            $scope.firstName="FIRST"
            $scope.lastName="LAST"
        });
    </script>
</head>
<body ng-app="myApp">
    <h2>Angular JS Application to Display Full Name</h2>
    <div ng-controller="myCntrl">
        Enter First Name:<input type="text" ng-model="firstName"><br/><br/>
        Enter last Name:<input type="text" ng-model="lastName"><br/><br/>
        Your Full Name:{{firstName+" "+lastName}}
    </div>
</body>
</html>
