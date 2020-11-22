# exercises-week2
Exercises &amp; challenges for week 2 

## Exercises WEEK2

### Functions
1. Write a function called 'describeSelf' which takes three prameter 'name', 'age', 'favouriteFood'. Based on the input return a string with the format like this:
'My name is xx and I'm xx years old. My favourite food is xx.'
2. Call this functions 3 times, with the input from 3 different people. Store the returned values in 3 different variables, and log them to the console.

### Function declarations & expressions
The world population is 7900 million people. 
1. Create a function declaration called 'percentageOfWorld1' which receives a 'population' value, and returns the percentage of the world population that the given population represents. For example, China has 1441 million people, so it's about 18.2% of the world population.
2. To calculate the percentage, divide the given 'population' value by 7900 and then multiply by 100
3. Call 'percentageOfWorld1' for 3 populations of countries of your choice, store the results into variables, and log them to the console
4. Create a function expression which does the exact same thing, called 'percentageOfWorld2', and also call it with 3 country populations (can bethe same populations)

### Arrow functions
1. Recreate the last assignment, but this time create an arrow function called 'percentageOfWorld3'

### Functions calling other functions
1. Create a function called 'describePopulation'. Use the function type you like the most. This function takes in two arguments: 'country' and 'population', and returns a string like this: 'China has 1441 million people, which is about 18.2% of the world.'
2. To calculate the percentage, 'describePopulation' call the 'percentageOfWorld1' you created earlier
3. Call 'describePopulation' with data for 3 countries of your choice

## CHALLENGE 1
Back to the two teams, the OG and Alliance! There is a new game they will compete against each other in which works differently. Each team competes 3 times, and then the average of the 3 scores is calculated (so one average score per team).A team only wins if it has at least double the average score of the other team.
Otherwise, no team wins!
Your tasks:
1. Create an arrow function 'calcAverage' to calculate the average of 3 scores
2. Use the function to calculate the average for both teams
3. Create a function 'checkWinner' that takes the average score of each team
as parameters ('avgOg' and 'avgAlliance'), and then logs the winner
to the console, together with the victory points, according to the rule above.
Example: "OG win (30 vs. 13)"
4. Use the 'checkWinner' function to determine the winner for both Data 1 and
Data 2
5. Ignore draws this time
**Test data:**
§ Data 1: OG score 44, 23 and 71. Alliance score 65, 54 and 49
§ Data 2: OG score 85, 54 and 41. Alliance score 23, 34 and 27
Hints:
§ To calculate average of 3 values, add them all together and divide by 3
§ To check if number A is at least double number B, check for A >= 2 * B.
Apply this to the team's average scores 
**GOOD LUCK**

### Arrays
1. Use the data given below and find out what the length of the array is.
1.1 Write a function called 'myLength' which console logs the length of the array
1.2 Within the function also use an if-conditional statement that checks if the number of items within the array are less than 4
**DATA**
const myPetNames = ['Tore', 'Clementine', 'Doris', 'Rivan', 'Lars',];

2. Declare and initialize an array called 'planets' with 5 string values
2.1 Console log each item in the array
2.2 Also console log the index of each item

3. Create an array containing all the neighbouring countries of a country of your choice. Choose a country which has at least 2 or 3 neighbours. Store the array
into a variable called 'neighbours'.
3.1 At some point, a new country called 'Utopia' is created in the neighbourhood of your selected country. So add it to the end of the 'neighbours' array.
3.2 Unfortunately, after some time, the new country is dissolved. So remove it from the end of the array.
3.3 If the 'neighbours' array does not include the country ‘Germany’, log to the console: 'Probably not a central European country :D'.
3.4 Change the name of one of your neighbouring countries. To do that, find the index of the country in the 'neighbours' array, and then use that index to
change the array at that index position. For example, you can search for 'Sweden' in the array, and then replace it with 'Republic of Sweden'.

### Objects
1. Create an object called 'me' that represents yourself, containing properties 'firstName', 'lastName', 'age', 'job' and 'pet' (an array like we used in previous assignments). 

2. Using the object from the previous assignment, log a string like this to the console: 'My name is Helena Johansson and I'm a 35 year old developer. I have 3 pets at home'.
2.1 Us e a turnery operator to decide how many pets you have. Remember it can be **one pet**, **pets** or **no pets**.
2.2 Do the same as in task nr 2 but with the this keyword this time.

### Iteration: for loop
1. There are elections in your country! In a small town, there are only 50 voters.Use a for loop to simulate the 50 people voting, by logging a string like this to the console (for numbers 1 to 50): 'Voter number 1 is currently voting'
