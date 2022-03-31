# Quiz 3

1.  Example JS    

```javascript
var weekDay = ["Monday", "Tuesday", "Wednesday", "Thursday", "Friday"]
for (var i = 0; i < weekDay.length - 1; i++) {
console.log(`A day of the week is ${weekDay[i]}`)
// or
if (weekDay[i] != 'Friday') {
        console.log('Day of week...')
}
}
// Yep!

```
2. Example JS  
        
```javascript

var myArray = [[41,45,95], [32,52,87]];

for (var i in myArray)
{
        for (var j in myArray[i])
        {
                console.log(myArray[i][j]); // yep!
        }
}
```
3. Per StackOverflow, while loops have an indefinite number of iterations, while for loops have a finite number.

4. Example JS  
```javascript
        var userInput = prompt("Please type Hi!") // Runs once...
        for(var i = 0; i <= 10; i++) {
        if(userInput == "Hi!") { 
        break;
    }
    console.log(i)
} 
```

```javascript
var input = ''
// Clicking "Cancel" in the Prompt window assigns null to input
// While input does not equal 'Hi!' and is not null
while (input != 'Hi!' && input != null) {
        input = prompt('Please tell me something');
}
```
5. Example JS  
        
```javascript

var nums = [1,2,3,4,5,6];
for(var i = 0; i < nums.length; i++){
        if(25 === nums[i] * 5){
                console.log(i); // returns index value
                console.log(num[i]); // returns desired number
        }
}
```