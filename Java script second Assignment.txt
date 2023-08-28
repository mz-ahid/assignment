//============================== 21
//1. Type the characters that are missing from this code.        var allLower = userInput.toLowerCase; Note: Correct this statement by yourself.

// var allLower = userInput.toLowerCase();

//2. Convert the string represented by x to lower-case and assign the result to the same variable.

// var x="Lower Case";
// x=x.toLowerCase();


//3. Convert the string represented by y to upper-case and assign the result to the same variable.

// var y="upper case";
// y=y.toUpperCase();

//4. Convert the string represented by a variable to lower-case and assign the result to a second variable that hasn't been declared beforehand.

// var x="Lower case FORM";
// var xa=x.toLowerCase();    


//5. Convert the string represented by an array element to lower-case and assign it to a variable that hasn't been declared beforehand.

// var myArray=["John","Die","Smith","Herry","Jackson"];
// var toConvert=0;
// var lowerCase=myArray[toConvert].toLowerCase();


//6. Display in an alert the upper-case version of the string represented by a variable.

// var uper="hellow world";
// uper=uper.toUpperCase();
// alert(uper);

//7. var cityName = “kaRacHi”; Convert the string represented by a cityName in Capitalisation is the writing of a word with its first letter in uppercase and the remaining letters in lowercase.


// var cityName = "kaRacHi";
// var capitalName = cityName.charAt(0).toUpperCase() + cityName.slice(1).toLowerCase();

//=========================== 22 to 25

//1. "captain" has been assigned to variable “sameWords”. You want  to slice "ap" out of it. 

// var sameWords = "captain";
// var sliceWords=sameWords.slice(1,3);

//2. The number of characters in the string will be assigned to the  variable. 

// var country="pakistan";
// var countryLen=country.length;
// console.log(countryLen)

//3. The string "elephant" has been assigned to the variable animal.  Slice the four middle characters out of the string and assign it to  the variable seg, which hasn't been declared beforehand. 

// var animal = "elephant";
// var animalSlice = animal.slice(2,6);
// console.log(animalSlice)

//4. Find the number of characters in the string represented by a  variable and assign the number to a second variable.

// var cityName ="Karachi";
// var cityChar= cityName.length;

//5. In a first statement measure how many characters there are in a  string represented by a variable. In a second statement slice all  but the first character and last 3 characters of the string and  assign it to a second variable that hasn't been declared  beforehand. 

// var city="Karachi";
// var cityChar=city.length;
// var citySliced=city.slice(0,1) + city.slice(-3);


//6. var text = "To be or not to be."; var indx = text.indexOf("be");What is the value of indx? 

//3


//7. var text = "To be or not to be.";  var indx = text.lastIndexOf("be"); What is the value of indx? Note: Try the above both examples by yourself.

//16

//8.  Find the index of the first character of the last instance of "go" in  the string represented by the variable text and assign the number  to the variable indx, which hasn't been declared beforehand.

// var text = "This is to go, that is to go, here is to go.";
// var lastIndex = text.lastIndexOf("go");
// if (lastIndex !== -1) {
//     var indx = lastIndex;
// } else {
//     var indx = -1;
// }


//9. Code the first line of an if statement that tests whether a segment  with an index represented by indexNum exists in a string. 

// if (indexNum >= 0 && indexNum < yourString.length)


//10. In this string "abcde", what character is at index 2? (Use  charAt) 

// var find = "abcde";
// var indxFind =find.charAt(2);


//11. Find the 10th character in the string represented by text and  assign it to the variable cha, which hasn't been declared  beforehand.

// var text = "This is a sample text.";
// var cha = text.charAt(9);


//12. Find the last character in the string represented by str and  assign it to x, which hasn't been declared beforehand.

// var str = "Karachi is the city of Pakistan";
// var x= str.charAt(str.length-1);


//13. Find the the 5th character in a string represented by input  and assign it to cha, which hasn't been declared beforehand. 

// var input="Nationality";
// var cha = input.charAt(4);


//14. Code the first line of an if statement that tests whether the  3rd character of a string represented by a variable is a particular  character. 

// var input="Nationality";
// if(input.charAt(2)==="t"){
//     console.log("Your Character T")   
// }
// else{
//     console.log("Not T")    
// }

//15. Code a for loop that cycles through all the characters of a  string represented by a variable and assigns each character to an  element of an array that has been declared beforehand. 

// var str = "for example";
// var charArray = [];
// for (var i = 0; i < str.length; i++) {
//     charArray.push(str.charAt(i)); 
// }

//In the string represented by reply replace the first instance of "no"  with "yes" and assign the revised string to revisedReply, which hasn't  been declared beforehand.

// var reply = "no there is no need try";
// var reviseReply=reply.replace("no", "yes");


//16. In a string represented by str replace the first instance of "1"  with "one" and assign the revised string to newStr, which hasn't  been declared beforehand. 

// var str ="there are 1 type of piece";
// var newStr=str.replace("1", "one");


//17. If you want all instances replaced, enter 3 characters that  need to appear in this statement. var y = x.replace("a", "z");

// var x="a,b,c";
// var y=x.replace("a,b,c","e,f,g");

//==============================26
//1. Form a statement that rounds a number to the nearest integer.

// var number =3.4;
// number= Math.round(number);


//2. Round up a number represented by origNum and assign it to  roundNum, which hasn't been declared beforehand. 

// var number =3.4;
// var roundUp=Math.ceil(number);


//3. Round down a number represented by origNum and assign it to  roundNum, which hasn't been declared beforehand. 

// var number =3.4;
// var roundUp=Math.floor(number);


    //4. Round a number represented by a variable and assign the result  to a second variable that hasn't been declared beforehand. 

    // var numb = 9.6;
    // var roundNum=Math.round(numb);

//5. Round .5 to 0 and assign it to a variable that hasn't been declared  beforehand. 

// var num=0.5;
// var roundNum=Math.floor(num);

//======================27

//Convert a random number generated by JavaScript to a number in  the range 1 to 50 

// var random1 = Math.random();
// var randomRange=Math.floor(random1*50)+1;


//2. Generate a random number and assign it to a variable that hasn't  been declared beforehand. 

// var random1=Math.random();

//3. You have to create a dice in JavaScript with the use of pseudo random number.

// function dice(){
//     var random1=Math.floor(Math.random()*6)+1;
//     return random1;            
// }

//4. You have to create a toss (head/tail) in JavaScript with the use of  pseudo-random number.

// function toss(){
//     var createRandom=Math.random()

//     if(createRandom<0.5){
//         return("Head")
//     }
//     else{
//         return("Tail")
//     }
// }
// var result =toss();
// console.log(result)

//==========================28 to 29
 //1. How do you convert a string to an integer in JavaScript?
 
//  var inte=5;
//  var convertString = inte.toString();

//2. Write a JavaScript function to convert the string "123" to an  integer. 

// var str="123";
// function convertString(){
//     return parseInt(str);
// } 
// var intVal=convertString(str)
  

//3. How can you convert a string containing a decimal number to a  floating-point number in JavaScript? 

// function convertFloat(str) {
//     return parseFloat(str);
//   }
//   var str = "123.45";
//   var floatValue = convertFloat(str);
    
  

//4. How can you check if a string can be successfully converted to an  integer or decimal in JavaScript before performing the  conversion? 

// var inputt="123";
// function convertInt(str){
//     return !isNaN(parseInt(str));
// }
// console.log(convertInt(inputt));


//5. How can you convert a number to a string in JavaScript? 

// var num =2;
// num=num.toString();


//6. Write a JavaScript function to convert the number 42 to a string. 

// var num =42;
// function numString(num){
//     return num.toString()
// }
// console.log(numString(num))

//7. Can you convert a string representing a decimal number (e.g.,  "3.14") to an integer in JavaScript? If so, how? 

// var intString = "3.14";
// intString=parseInt(intString);

 
//=========================30
//1. Code a statement that rounds a number represented by num to 4  places, converts it to a string, and assigns it to newNum, which  hasn't been declared beforehand.

// var num = 3.12345678;
// num=num.toFixed(4);
// var newNum=num.toString()
// console.log(newNum)

//2. In a single statement round a number represented by a variable to  2 places, convert it to a string, convert it back to a number, and  assign it to the same variable.

// num=parseFloat(num.toFixed(2));


//3. Code the first line of an if statement that tests whether the  number represented by num, rounded to 2 digits and converted  to a string, has more than 4 characters in it. 

// if(num.toFixed(2).toString.length>4){} 

//4. Assign a number with many decimal places to a variable. Code an alert that displays the number rounded to 2 decimal  places and converted to a string. 

// var num = 123.12346789;
// var round=num.toFixed(2).toString()

//=====================31 to 34

//1. Code a statement that creates a new Date object and assigns it to  dObj, which hasn't been declared beforehand. 

// var dobj=new Date();

//2. Code a statement that creates a new Date object, converts it to a  string, and assigns the string to dStr, which hasn't been declared  beforehand. 

// var dstr = new Date().toString();

//3. Code a statement that extracts the day of the week from a Date  object represented by d and assigns it to day, which hasn't been  declared beforehand. 

// var dateToday= new Date();
// var d =dateToday.getDay();
 
//4. The day has been extracted from the Date object and assigned to  d. The names of the days of the week have been assigned to the  array dayNames. Alert the current day with array index. 

// var dateToday= new Date();
// var days=["sunday","monday","tuesday","wednwsday","thursday","friday","satrday"];
// var currentDay=dateToday.getDay();
// var currentDayName=days[currentDay];


//5. Extract all parts of the Date and Time and assign it to the variable  which has not been declared beforehand. 

// var dateToday=new Date();
// var year=dateToday.getFullYear();
// var month=dateToday.getMonth();
// var day=dateToday.getDate();
// var hour=dateToday.getHours();
// var mint=dateToday.getMinutes();
// var second=dateToday.getSeconds();
// var milliSecond=dateToday.getMilliseconds();

//6. Code a statement that creates a Date object for the last day of the  last month of 2020 and assigns it to later, which hasn't been  declared beforehand. 


// var later = new Date(2020, 12, 0);


//7. Create a Date object for the second day of the second month of  1992 and assign it to a variable that hasn't been declared  beforehand.


// var year92=new Date(1992,1,2);


//8. Code a single statement that displays in an alert the milliseconds  that elapsed between the reference date and the beginning of  1980. 

// alert(new Date().getTime() - new Date(1980, 0, 1).getTime());


//9. How do you change the year of a date in JavaScript? 

// var date = new Date();
// var newYear=2020;
// date.setFullYear(newYear);


//10. Write a JavaScript function to change the month of a given  date to January. 

// function changeMonthToJanuary(inputDate) {
//     inputDate.setMonth(0);  }
//   var date = new Date(2023, 7, 15);
//   changeMonthToJanuary(date);
  
  
//11. What is the method to change the day of the week for a  specific date in JavaScript? 

// function findNextDayOfWeek(startDate, targetDayOfWeek) {
//     var daysOfWeek = ['Sunday', 'Monday', 'Tuesday', 'Wednesday', 'Thursday', 'Friday', 'Saturday'];
//     var daysUntilTarget = (targetDayOfWeek - startDate.getDay() + 7) % 7;
//     var nextDate = new Date(startDate);
//     nextDate.setDate(startDate.getDate() + daysUntilTarget);
//     return nextDate;
//   } 
//   var startDate = new Date();
//   var targetDayOfWeek = 5;
//   var nextFriday = findNextDayOfWeek(startDate, targetDayOfWeek);
   

//12. Write a JavaScript function to change the minutes of a given  time to a specific value. (Value by prompt) 

// function changeMinutes(inputDate, newMinutes) {
//     inputDate.setMinutes(newMinutes);
//   }
//   var currentDate = new Date();
//   var newMinutes = parseInt(prompt("Enter the new minutes:"));
//   if (!isNaN(newMinutes)) {
//     changeMinutes(currentDate, newMinutes);
//     console.log(currentDate);
//   } else {
//     console.log("Invalid input for minutes.");
//   }
  

//13. Write a JavaScript function to add a specific number of  hours to a given time.

// function addHours(inputDate, hoursToAdd) {
//     inputDate.setTime(inputDate.getTime() + hoursToAdd * 60 * 60 * 1000);
//   }
//   var currentDate = new Date();
//   var hoursToAdd = 3;
  
//   addHours(currentDate, hoursToAdd);
//   console.log(addHours);
  

//14. You have to create a age calculator in JavaScript. 

// function calculateAge(birthdate) {
//     var today = new Date();
//     var birthDate = new Date(birthdate);
    
//     var age = today.getFullYear() - birthDate.getFullYear();
//      monthDiff = today.getMonth() - birthDate.getMonth();
    
//     if (monthDiff < 0 || (monthDiff === 0 && today.getDate() < birthDate.getDate())) {
//       age--;
//     }
//     return age;
//   }
  
//   var birthdate = "1999-03-23"; 
//   var age = calculateAge(birthdate);
//   console.log(age);
  
//=======================35 to 37

//1. Code the first line of a function displayAlert. 
 
// function displyAlert(){
// alert("Message")
// }

//2. Code a function named askName that prompts the user to "Enter  name" and assigns the answer to userName, which hasn't been  declared beforehand. 

// function askName(){
//     var userName= prompt("Enter Name");
//     return userName;
// }
// var userNameAnswer=askName();

//3. Code a function that calls 2 other functions. 

// function greetUser(name) {
//     console.log("Hello, " + name + "!");
//   }
//   function askName() {
//     var userName = prompt("Enter your name");
//     return userName;
//   }
//   function main() {
//     var name = askName();
//     greetUser(name);
//   }
//   main();
  

//4. Code a function that displays a prompt, "Enter name" and then  displays the name in an alert. Call the function.

// function callName(){
//     var userName=prompt("Enter Name");
//     if(userName){
//         alert (userName);
//     }
//     else{
//         alert("No Name");
//     }
// }
// callName();

//5. Code the first line of a function named concat that has 3  parameters, the first three letters of the alphabet. Call that takes  a variable, a string, and a number as arguments. 

// var variable = "Hello";
// var str = " World";
// var num = 42;

// function concat(variable, str, num){
//     return(variable+str+num);
//     };
//     concat(variable,str,num);
    

//6. Code a function that has 2 parameters. Concatenate them and  assign the result to a variable that hasn't been declared  beforehand.

// function concatenateAndAssign(param1, param2) {
//     var concatenatedResult = param1 + param2;
//     return concatenatedResult;
//   }
//   var string1 = "Hello, ";
//   var string2 = "world!";
//   var result = concatenateAndAssign(string1, string2);

  

//7. Code a function that has three parameters. Multiply them and  assign them to a variable that hasn't been declared yet. 

// function multiplyAndAssign(param1, param2, param3) {
//     var multiplicationResult = param1 * param2 * param3;
//     return multiplicationResult;
//   }
//   var num1 = 2;
//   var num2 = 3;
//   var num3 = 4;
//   var result = multiplyAndAssign(num1, num2, num3);
//   console.log(result);
  

//8. Write a JavaScript function that takes an array of numbers as  input and returns the average of those numbers. 

// function calculateAverage(numbers) {
//     if (numbers.length === 0) {
//       return 0;
//     }
    
//     var sum = numbers.reduce((total, num) => total + num, 0);
//     var average = sum / numbers.length;
//     return average;
//   }
//   var numberArray = [10, 20, 30, 40, 50];
//   var avg = calculateAverage(numberArray);
  

//9. Write a JavaScript function that takes two parameters and returns  their sum. -098765 X ``

// function calculateSum(a, b) {
//     return a + b;
//   }  
//   var num1 = -98765;
//   var num2 = 123456;
//   var sum = calculateSum(num1, num2);
  

//10. Write a JavaScript function that takes an array of numbers as  input and returns the average of those numbers. 

// function calculateAverage(numbers) {
//     if (numbers.length === 0) {
//       return 0;
//     }
//     var sum = numbers.reduce((total, num) => total + num, 0);
//     var average = sum / numbers.length;
    
//     return average;
// }
//   var numberArray = [10, 20, 30, 40, 50];
//   var avg = calculateAverage(numberArray);
//   console.log("Average:", avg);
  

//11. You have to capture the returned value from a function and  store it in a variable? 

// function add(a, b) {
//     return a + b;
//   }
//   var result = add(5, 3); 
  
  
//12. Write a function which tells letter counts of (word). 

    // function letterCounts(word) {
    //     var counts = {};
    //     for (var letter of word) {
    //     if (letter in counts) {
    //         counts[letter]++;
    //     } else {
    //         counts[letter] = 1;
    //     }
    //     }
        
    //     return counts;
    // }

    // var inputWord = "banana";
    // var counts = letterCounts(inputWord);
    
  

//13. Write a function to set (year) in date object. 

// function setYearInDate(year, dateObj) {
//     dateObj.setFullYear(year);
//   }
  
//   var myDate = new Date();
//   var desiredYear = 2023;
  
//   setYearInDate(desiredYear, myDate);
  

//14. Write a function which tells the age of a person who Born on  (dateOfBirth) 

// function calculateAge(dateOfBirth) {
//     var today = new Date();
//     var birthDate = new Date(dateOfBirth);
//     var age = today.getFullYear() - birthDate.getFullYear();
//     var monthDiff = today.getMonth() - birthDate.getMonth();
  
//     if (monthDiff < 0 || (monthDiff === 0 && today.getDate() < birthDate.getDate())) {
//       age--;
//     }
  
//     return age;
//   }
  
//   var dateOfBirth = "1990-05-15"; 
//   var age = calculateAge(dateOfBirth);


//15. Write a function which tells the presense of (word) in an  array = ['zaid','haris','raza','abubakar','hassan','hussain','fatima'] result should be in true or false 

// function checkWordPresence(word, array) {
//     return array.includes(word);
//   }
//   var wordArray = ['zaid', 'haris', 'raza', 'abubakar', 'hassan', 'hussain', 'fatima'];
//   var searchWord = 'hassan';
//   var isPresent = checkWordPresence(searchWord, wordArray);
  

//16. Write a function which repeat (letter) 10 times. Hint: "abcde" str.repeat(10) 

// function repeatLetter(letter, times) {
//     return letter.repeat(times);
//   }
//   var inputLetter = "a";
//   var repetitionCount = 10;
//   var repeatedString = repeatLetter(inputLetter, repetitionCount);


//17. write a function which reverse array = ['a','b','c','d','e'] Hint: arr.reverse() 

// function reverseArray(array) {
//     return array.reverse();
//   }
//   var inputArray = ['a', 'b', 'c', 'd', 'e'];
//   var reversedArray = reverseArray(inputArray);

  
//=====================38

//1. Write a JavaScript function that demonstrates the usage of a local  variable. 

// function greetPerson(name) {
//     var greeting = "Hello, " + name + "!";
//   }
//     greetPerson("Alice"); 

//2. How can you access a global variable inside a function in  JavaScript?


// var globalVar = "global variable";
// function accessGlobalVariable() {
//   console.log(globalVar);
// }
// accessGlobalVariable();

//=======================39 to 40

// 1. Write a JavaScript switch statement that checks the value of a  variable and performs different actions based on different cases. 

// var dayOfWeek = "Wednesday";
// switch (dayOfWeek) {
//   case "Monday":
//     console.log("start of the week.");
//     break;
//   case "Tuesday":
//     console.log("second day of the week.");
//     break;
//   case "Wednesday":
//     console.log("middle of the week.");
//     break;
//   case "Thursday":
//     console.log("almost the weekend.");
//     break;
//   case "Friday":
//     console.log("It's the end of the workweek.");
//     break;
//   default:
//     console.log("It's a weekend day.");
// }


//2. Write a JavaScript switch statement that check whether cityName  given by user check the cityName if match alert the user and  break the statement, if not default message will be shown to user. 

// var cityName = prompt("Enter a city name:");
// switch (cityName) {
//   case "New York":
//     alert("You've entered New York!");
//     break;
//   case "Los Angeles":
//     alert("You've entered Los Angeles!");
//     break;
//   case "Chicago":
//     alert("You've entered Chicago!");
//     break;
//   case "Miami":
//     alert("You've entered Miami!");
//     break;
//   default:
//     alert("City not recognized.");
// }
