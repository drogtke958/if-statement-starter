# JavaScript IF Statements Practice
## Instructions

- Review the if statement examples shown below
- Then write your own if statements per the instructions

## Your GitHub Repo

1. Create a new GitHub repo: ***if-statements-js***

>Please make your repo **PUBLIC**.

2. Add your project files to your repo.
3. Publish your code and code updates to your online repo.
4. Submit the URL that points to your online repo on Google Classroom.

## Examples

### An IF statement

```javascript
const youEatMeat = true;
// If the user eats meat, tell them to order a hamburger!
if (youEatMeat) {
    console.log("Order a big, greasy hamburger!");
}
```

### A simple IF/ELSE statement
```javascript
const firstName = prompt("Please enter your first name:\n");
alert(`Greetings, ${firstName}!`);

if (firstName.length > 6) { 
	alert (`Wow, ${firstName}! Your first name contains ${firstName.length} characters!`);
} else {
	alert(`You have a short first name, ${firstName}!`);
}
```

### An IF/ELSE IF statement
```javascript
function checkNationality(nationality) {
  if (nationality === "US") {
    alert("You are American.");
  } else if (nationality === "UK") {
    alert("You are British.");
  } else if (nationality === "CA") {
    alert("You are Canadian.");
  } else {
    alert("Your nationality is not listed.");
  }
}

// Prompt the user for their nationality
const userNationality = prompt("Enter the code that represents your nationality: (US, UK, CA)\n");

// Call the function to check and display nationality
checkNationality(userNationality.toUpperCase()); // Convert input to uppercase using the JS toUpperCase ( ) method
```

## Write These IF Statements

You can write each code block in the same script (main.js).

### An IF statement
Write an IF statement that checks whether the user is 18 and therefore old enough to vote.  

Define a JS variable named *age* and set its value to 20.

Then write an if statement that checks to see if the user's age is GREATER THAN OR EQUAL TO 18.  Display a message in the browser console that says: Congratulations! You are old enough to vote in the United States! if the user's age is 18 (or above).

### A simple IF/ELSE statement

Write an IF/ELSE statement that checks whether the user has more than $100.00 dollars in their bank account.

Prompt the user to enter how much money they currently have in their bank account.

**HINT**: *How do you tell JavaScript to treat what the user types in as a number?*

If they have more than $100.00 in their account, use the JS alert ( ) method to display an alert box that says: Woohoo! You're rich!

Otherwise [else], recommend that they start adding $10.00 per week to their savings account.

### An IF/ELSE IF statement

- Mikey, a college student, needs 120 credits to graduate
- Help Mikey determine whether he has enough credits to graduate by writing a script that does the following:
	- prompts the student to enter the number of credits s/he has earned (HINT: Handle the user's answer as a number!)
   	- the JS parseInt ( ) function might come in handy here!
   	- add a condition to the if statement that checks to see if the student's credits are GREATER THAN OR EQUAL TO the credits required to graduate
  		- If so, tell the student s/he has enough credits to graduate
   	- use an **else if** clause to add a second condition to your code
  		- the second condition will check to see if the student's credits are GREATER THAN OR EQUAL TO the credits required to graduate minus 30
   	  	- if this second condition is true, tell the student how many more credits s/he needs this year to graduate (need to do some basic math here...)
   	- add an **else** clause to your code as well
  		- tell the student s/he will have to take additional courses to graduate
   	  	- also tell the student how many credits they still need to graduate (need to do some basic math here...)



