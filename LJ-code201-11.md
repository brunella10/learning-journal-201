
----------

# **Learning Journal 11**

## __***week 3***__



Chapter 10: Debugging
Over flow for make the scroll page
Reset.css
Normalize.css → works for the most common setting on css.
 
Built out the html. 
then css → layout → style → 
The images have to switch, for each of these elements , inside of a container, have to have a event to each image. 
How float left work. 
How to keep the flow of our web page.

 --------

```var container = document.getElementById(‘stooges’)
container.addEventListener(‘click’, handleClick);
    function handleClick(event) {
console.log(event.target);
if (event.target.id === ‘stooges’) {
alert(‘You had just one job.Click in the h2 but not the sections’)
}
var larry = document.getElementById(‘larry’)
var larry = document.getElementById(‘curly’)
var larry = document.getElementById(‘moe’)
var larry = document.getElementById(‘iggy’)
 
//to track the number of clicks
var larryClicks = 0;
var curlyClicks = 0;
var moeClicks = 0;
var iggyClicks = 0;
 
if (event.id.target.id === ‘larry’ {
larryClicks += 1
console.log(‘larry have been clicked’ + larryClicks + ‘times’)
}
if (event.id.target.id === ‘larry’ {
curlyClicks += 1
console.log(‘larry have been clicked’ + curlyClicks + ‘times’)
 
}
if (event.id.target.id === ‘larry’ {
moeClicks += 1
console.log(‘larry have been clicked’ + moeClicks + ‘times’)
 
}
if (event.id.target.id === ‘larry’ {
iggyClicks += 1
console.log(‘larry have been clicked’ + iggyClicks + ‘times’)
 
}
} 
```
------
> **Note:**
The weekend assignment was long but I enjoyed it.


