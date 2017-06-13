----------

# Class  June 8, 2017


##Class 5
june 9 2017


*See the video from the today class*

console.log(mathsGetHarder(2,5,9)[2] , ‘mathsGetHarder(2,5,9)[2]’ );

if you assign a variable with the same name inside 2 differents fuction it gonna be a completelly differents variables ex
fuction pep(){
  var anne = '12';
}
function luck(){
  var anne = "luck";
}
try to avoid global variable.
var cat = "meow";
function kitten(){
console.log('more kittens');
function call scoop variable -by now-
}
*/

// clue function and return function
// plus sing is an operator and a arithmetic sing. it can be use to sum or for ...
// function fire (hoistin: make the name avaliable but it no abstually receive an assignment. Is the reason why we assign the variable to the top out the fuction) The problem is due at the name of the variable. So we just need to change it for other.


// fuction declaration vs fuction expressions

function demi() {
    console.log('woof')
  }
demi()
buddyCat(); // it give error because it was not declare prior the semi colon.
//doggyDog(); // it give us a error "it is not a function (is not define) instead of 'has not be declare (is not a function)' "

var buddyCat = function() {
  console.log('MEEEOOWWWW')
};


About the book:
Image, text and fonts.

color: on CSS.

-------------------------

##Class 6. Codefellows 201.

domain model DOM : define a problem and identify the step that are involved. detailed the solutions it could be the second steps. what the component are. (*ryan sobol $160 hour rate).
html every element is an object that can be manipulable. The DOM as
we can access to html from js file using command as document.body or document.head.’someproperties’ (can access to the properties inside the html element you tag)
method → document.getElementById(‘stuff’) it return <ul id=”stuff”></ul> can be assigned to a variable
var myFavoriteUL= document.getElementById(‘stuff’);
myFavoriteUL
<ul id=”stuff”></ul>
myFavoriteUL.textContent = ‘whatever you wanna write inside’ ;

var seagullCount = [2, 88, 3, 45, 66, 123864];
*if we want to put this array  in an ordered list (bar code) we can use <ul> <li> manually. But we can use js to exactly the same in an easily way. Through a ‘for loop’
for (var i = 0; i <  seagullCount.lenght; i++) {
}
//1 create the element
//2 give the element some content
//3 append the element to the appropriate place in the DOM.

document.createElement(‘li’);
var liEl = document.createElement(‘li’) → bullet/list element

// to put content inside
liEl.textContent = ‘fish’;
→ <li> fish </li>
myFavoriteUL.appendChild(liEl) →  <li> fish </li>

today assignment
we need to work in branch for each day. ‘monday’ ‘day1’
objects literals one for each store model
→ internal data management (Today).
→ page for a business
*no use css today. Just js.
→ calculate cookie to cake for each place of the franchises. Different numbers.
→ it has to be able to modify the amount of cookies.

objects to represent one of each store.
sale.html
properties for max and min costumer per hour.
method of the object that calculate the numbers of costumer (random generation)
simulate the number per location per hour.
store number of cookie sale per hour per location (array cookie sale per hour) cookieSales = [1,2,3,4,5,6,7,];.


```javascript
var pikeShop = {
 minCustomerPerHour: 23,
 maxCustomerPerHour: 65,
 avgCookieSalePerHour: 6.3,
 totalCookies:[],
 numCustomerPerHour: function() {
   return Math.random() * (this.maxCustomerPerHour - this.minCustomerPerHour) + this.minCustomerPerHour;
 }
};
for (var i = 0; i < hoursOpen.length; i++) {
 var totalCookiesPike = pikeShop.avgCookieSalePerHour * pikeShop.numCustomerPerHour();
 pikeShop.totalCookies[i] = [totalCookiesPike, hoursOpen[i]];
}
```

------
> **Note:**
I still having issues figuring out how to put together the code. I have some issues figuring out what should I do with my code.
