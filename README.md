# javascript-assigement-question-
Javascript assigements question 

//  Declare your name as a string and print its length inj
//   JS.
let name = "Urmila sawaldekar";
typeof name
name.length

// Declare your frist name as a string and print its first characters 
let firstName = "Urmila";
firstName[0]

// Declare your frist name as a string and print its last characters
let lastName = "Urmila";
lastName.length
lastName[6]
// shorthand
lastName[lastName.length - 1]
// what is output of following Code:
// // "apna college"+123 
apnacollege123

// what are lengths of an empty strings and a string with a single space
let emptystring = "";
emptystring.length
let space = " ";
space.length



//What is the value of age after this code runs ?
let age = 23;
age = age + 2; //after 2 years

//what is the value of avg after this code runs?

let hindi = 80;
let eng = 90;
let math = 100;
let avg = (hindi + eng + math) / 3;

// what is the value of each  varaiable in each line of code?

let num = 5;
let newNum = num++;
newNum = ++num;

// Create a system to calcuate popcorn prices based on the size customer asked for:
//if size is "Xl", price is rs 250
//if size is "L", price is rs 200
//if size is "M", price is rs 100
// if size is "S" , price is rs 50

let size = "XL";
if (size === "XL") {
   console.log("price is rs. 250");
}
else if (size === "L") {
   console.log("price is rs. 200");
}
else if (size === "M") {
   console.log("price is rs. 100");
}
else {
   console.log("price is rs. 50");
}


// A "good string" is a string that starts with the letter 'a' & has a length >3. Write  a program to find if a string is good or bad 
let str = "apple";

if ((str[0] === 'a') && (str.length > 3)) {
   console.log("good string");
} else {
   console.log("bad string");
}



//predict the output of the following code :
let num = 12;
if ((num % 3 === 0) && ((num + 1 == 15) || (num - 1 == 11))) {
   console.log("safe");
} else {
   console.log("unsafe");
}



//use switch statement to print the day of the week using a number variabke 'day' with values 1 to 7.
// 1 = monday, 2 = tuesday and so on

let day = 1;

switch (day) {
   case 1:
      console.log("Monday");
      break;
   case 2:
      console.log("Tuesday");
      break;
   case 3:
      console.log("Wednesday");
      break;
   case 4:
      console.log("Thursday");
      break;
   case 5:
      console.log("Friday");
      break;
   case 6:
      console.log("saturaday");
      break;
   case 7:
      console.log("Sunday");
      break;
   default:
      console.log("Wrong day!");
}

// create a number  variable num with some value now print "good" if the number is divisble by 10 and print "bad"
// if it is not.

let num = 5;
if (num % 10 == 0) {
   console.log("good");
} else {
   console.log("bad");
}

//Take the users name and age as input using prompt.
//then return back the following statement to the user as an alert (By substituting their name and age):
//name is age years old .[ use template literals to print this sentence]
let username = prompt("enter the username");
let age = prompt("enter your age");

alert(`${name} is ${age} years old.`);

// Write a switch statement  to print the months in  a quarter .
// Months in Quarter 1 : January , February , March 
// Months in Quarter 2 : April , May , June 
// Months in Quarter 3 :July , August , September 
// Months in Quarter 4 :October , Noverber , December 
// [Use the number as the case value in switch] 

let Quarter = 3;
switch (Quarter) {
   case 1: console.log("Jaunary , February , March");
      break;
   case 2: console.log("April , May , june");
      break;
   case 3: console.log("July , August ,  September");
      break;
   case 4: console.log("October , November , December");
      break;
}

// A string is a golden string if ir starts with the character 'A' or 'a' and has a total length greater than 5  for a given string print if it is golden or not

let str = "apple";
 if ((str[0] == 'a' || start[0] == 'A')&&(str.length > 5)){ 
   console.log("It is a golden string";);
 }else {
   console.log("It is not a golden string");
 }

 // Write a program to find the largest of 3 numbers.
 

 let a = 5;
  
 let b = 12;
 let c = 3;
  
 if (a > b) {
   if (a > c ){
      console.log(a, "is largest");
      else {
         console.log(c, "is largest");
      }
   }
   else{
      if(b > c ){
         console.log(b, "is largest");
      }else{
         console.log(a, "is largest");
      }
   }
 }

  //Write a program to check if 2 number have the same last digit.
  //Eg : 32 and 47852 have the same last digit i.e 2


  let num1 = 32;
  let num2 = 47852;
   
   if(num1%10) == (num2% 10){
      console.log("Both numbers have the same last digit  which is", num1%10);
    }else {
      console.log("Both numbers do not  have the same last digit");
    }
