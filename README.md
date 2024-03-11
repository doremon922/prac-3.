# prac-3.


div.html <!DOCTYPE html> 
<html> 
<head> 
    <meta charset="UTF-8"> 
    <title>Division</title> 
    <script 
src="https://ajax.googleapis.com/ajax/libs/angularjs/1.4.8/angular.min.js"></script>     <script src="main.js"></script> 
</head> 
<body> 
<div ng-app = "DivisionApp" ng-controller="DemoDivController">     First Number: 
    <input type="text" ng-model="num1">     <br><br>     Second Number: 
    <input type="text" ng-model="num2"> 
    <br><br> 
    Division :{{div()}} 
</div> 
</body> 
</html> 
 
