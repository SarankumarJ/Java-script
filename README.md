# Java-script

## Questions :-
### 1.Get user input using prompt(“Enter your age:”). If user is 18 or older , give feedback:'You are old enough to drive' but if not 18 give another feedback stating to wait for the number of years he needs to turn 18.

Enter your age: 30

You are old enough to drive.


Enter your age:15

You are left with 3 years to d

### 2.Compare the values of myAge and yourAge using if … else. Based on the comparison and log the result to console stating who is older (me or you). Use prompt(“Enter your age:”) to get the age as input.

Enter your age: 30

You are 5 years older than me.

### 3.Even numbers are divisible by 2 and the remainder is zero. How do you check, if a number is even or not using JavaScript?

Enter a number: 2

2 is an even number

Enter a number: 9

9 is is an odd number.
## Program :-
~~~javascript
var age=prompt("Enter your Age:");
if(age>=18)
{
    console.log("You are old enough to drive.");
}
else
{
    console.log("You are left with"+(18-age)+" years to drive.");
}
var myAge=18;
if(myAge<age)
{
    console.log("You are "+(age-myAge)+" 0lder than me");
}
else
{
    console.log("You are "+(myAge-age)+" younger than me");
}
var num=prompt("Enter a number:");
if(num%2==0)
{
    console.log(num+" is an even number");
}
else
{
    console.log(num+" is an odd number");
}
~~~
## Output :-
![git](./op.png)
