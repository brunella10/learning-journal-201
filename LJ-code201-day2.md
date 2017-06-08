## CLASS 2 201 June 6, 2017.
JS Basic JavaScripts instructions
--------------
“Pseudo code” we think through the code.
declare a variable
assign the variable a value via prompt() statement
display value to the user with alert
left ourself a recorcord of the thing with console.log(‘’);
Ex => var TheMan = ‘BrianA.’;
*strings = text numbers= integer or floating point boolean=true or false*
semicolon in JS = JavaScripts sometimes assume that the semicolon is there even when you have not put it. That’s why there is a flow about that the semicolon is about to disappear . 
Today - about your code style, create code by your own. 5 separate statement on the code. 
 
## LAB session 2 
Learning journal: 
codefellows/201/week1/xxx
codefellows/201/learning-journal
We gonna turn this in git repository. 
Work locally → became in a git (wire up github)
Git project → build a problem in github and clone it to our laptop → write codez
 
 
Daily Lab assignment/weekly project. 
git vs github => both work together but it is not the same.
git → software in our computer to version control.
github → cloud storage for project manage for git.
 
 

 ### *Note* : I was not able to finished the lab. I just did 3 assigment. Loops, Create ordered list in html and touch css a little bit. 
 
And here's some code!
 
```javascript
var numberOfTries = 3;
var moving = 6;

while (numberOfTries > 0){
  var guess = prompt('How many times did I move in the past 10 years?');

  if (guess >  moving) {
    alert('Too high');
    console.log('if the guess is higher than moving variable let the user know the answer is to high.');
  } else if (guess < moving) {
    alert('Too low');
    console.log('if the guess is lower than moving variable ler the user know the answer is too low');
  } else {
    alert('Yes! That is CORRECT!');
    numberOfTries = -1;
    console.log('If the guess is equal to moving variable the answer is correct');
  }
  numberOfTries = numberOfTries-1;
}
```
