# Day-6-Find-the-culprits

Part-1

//Find the culprit
<!DOCTYPE html>
<html>
<body>
 <script>
 alert("I'm JavaScript!");
 </script>
</body>
</html>

//Find the culprit and invoke the alert
alert("I'm invoked!");

//Explain the below how it works
alert("I'm JavaScript!"); // Alert box displays a message at top of the web page with a "OK" buttton
                          //Unless the "OK" button is clicked, user cannot perform any actions on the page

alert('Hello')   //It works same as normal alert box with semicolumn                     

alert(`Wor       
 ld`)       //When the output to be displayed in multilines, this type of alert box is used 

 alert(3 +
1
+ 2);      //Javascript is capable of running multiline code. Here the output will be the summation of all 3 lines as an arithematic operator is used , which gives 6 as output

//Fix the below to alert Guvi geek
let admin=9, fname=10.5; 
fname = "Guvi";
lname = "geek"
admin = fname+' '+lname;
alert( admin ); // "Guvi geek" 

//Fix the below to alert hello Guvi geek
let fname=10.5; 
fname = "Guvi";
lname = " geek"
let name = fname+lname;
alert( 'hello'+ ' '+name);

//Fix the below to alert sum of two numbers
let a = prompt("First number?");
let b = prompt("Second number?");
alert(parseInt(a) + parseInt(b));

//If you run the below scritpt you will get “Code is Blasted”
Explain Why the Code is blasted and how to diffuse it and get “Diffused”.
/* 
if condition : if True return "Code is Blasted"
                else return "Diffused"

above is the explanation of if conditon given in code.
so as the variable input given as "2" > "12" - here 2 is compared to 1 
*/

var a = 2 > 12;
//Don't touch below this
if (a) {
  console.log("Code is Blasted")
}
else
{
  console.log("Diffused")  
}

//How to get the success in console.
let b = prompt("Enter a number?");
a=parseInt(b);
//Don't modify any code below this
if (a) {
 console.log( 'OMG it works for any number inc 0' );
}
else
{
 console.log( "Success" );
}

//How to get the correct score in console.
let value = parseInt(prompt('How many runs you scored in this ball'));
if (value === 4) {
      console.log("You hit a Four");
} else if (value === 6) {
      console.log("You hit a Six");
} else {
      console.log("I couldn't figure out");
}

//Fix the code to welcome the Employee
let login = 'Employee';
let message = (login == 'Employee') ? 'welcome employee':
  (login == 'Director') ? 'Greetings' :
  (login == '') ? 'No login' :
  '';
console.log(message);

//Fix the code to welcome the boss
let message;

if (null || 2 || undefined )
{
  message = "welcome boss";
}
else
{
  message = "Go away";
}
  console.log(message);
  
//Fix the code to welcome the boss
let message;
let lock = null;
//Dont change any code below this 
if (null || lock || undefined )
{
  message = "Go away";
}
else
{
 message = "welcome";
}
  console.log(message);
  
  
//Fix the code to welcome the boss
let message;
let lock = null;
//Dont change any code below this
if (lock && " " || undefined )
{
  message = "Go away";
}
else
{
 message = "welcome";
}
console.log(message);

//Change the code to print
3
2
1
let i = 4;
while (i) {
  console.log( --i );
  if(i==1){
    break
  }
}


//Change the code to print 1 to 10 in 4 lines
let x=" ";
for(let i=1;i<=11;i++){
    x += i + ' '
    if(i%4===0){
        console.log(x)
        x=" "  
    }    
}


//Change the code to print even numbers
for (let num = 2; num <= 20; num += 2) {
    console.log(num)
  }

//Change the code to print all the gifts
let gifts = ["teddy bear", "drone", "doll"];
for (let i = 0; i < 3; i++) {
  console.log( gifts[i] );
}


//Fix the code to disarm the bomb.
let countdown = 100;
while (countdown > 0) {
  countdown--;
  if(countdown != 0)
  {
   console.log("Disarm the bomb");
  }
  
  
//Whats the msg printed and why?
var lemein = "0";
var lemeout = 0;
var msg = "";
if (lemein) {
 msg += "hi";
 }
if (lemeout) {
 msg += 'Hello';
}
console.log(msg);

Message printed is "hi"
Reason : var takes string as input and lemein has string as variable so the condition of lemein is passed and output displayed as hi


Part-2

//Write a code to print the numbers in the array
Output: 1234567891011

var numsArr = [ 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11];
var new_string = "";
for (var i = 0; i < 11; i++) {
 new_string += numsArr[i] 
}
console.log(new_string);


//Write a code to print the numbers in the array
Output: 1,2,3,4,5,6,7,8,9,10,11

var numsArr = [ 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11];
var new_string = new String(numsArr[0]);
 
for (var i = 1; i < 11; i++) {
 new_string += "," +numsArr[i] 
}
console.log(new_string);


//Write a code to print from last to first with spaces (Make sure there is no space after the last element 1)
Output: 11 10 9 8 7 6 5 4 3 2 1

var numsArr = [ 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11];
var new_string = new String(numsArr[10]);
 
for (var i = 9; i >= 0; i--) {
 new_string += " "+ numsArr[i] 
}
console.log(new_string);


//Write a code to replace the array value — If the number is even, replace it with ‘even’.
Output:[ 1, “even”, 3, “even”, 5, “even”, 7, “even”, 9, “even”, … ]

var numsArr = [ 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11];
for (var i = 0; i <=10; i++) {
 if(numsArr[i] %2 == 0 )
 {
 numsArr[i+1] = "even"
 }
}
console.log(numsArr);


//Write a code to replace the array value — If the index is even, replace it with ‘even’.
Output: [ “even”, 2, “even”, 4, “even”, 6, “even”, 8, “even”, 10, … ]

var numsArr = [ 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11];
for (var i = 0; i <=10; i++) {
 if((i) %2 == 0 )
 {
 numsArr[i] = "even"
 }
}
console.log(numsArr);


//Write a code to add all the numbers in the array
Output: 66
var numsArr = [ 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11];
var sum=0;
for (var i = 0; i <=10; i++) {
 
 sum += numsArr[i]
}
console.log(sum);


//Write a code to add the even numbers only
Output: 30

var numsArr = [ 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11];
var sum=0;
for (var i = 0; i <10; i++) {
 if(numsArr[i]%2==0);
 sum += numsArr[i]
}
console.log(sum);


//Write a code to add the even numbers and subract the odd numbers
Output: 94
var numsArr = [ 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11];
var sum=100;
for (var i = 0; i <=10; i++) {
 if(numsArr[i]%2!=0)
 {
 sum += numsArr[i]
 }
 else
 {
 sum -= numsArr[i]
 }
}
console.log(sum);


//Write a code to print inner arrays
Output:
Array(5) [ 1, 2, 3, 4, 5 ]
Array(6) [ 6, 7, 8, 9, 10, 11 ]

var numsArr = [[1, 2, 3, 4, 5],[ 6, 7, 8, 9, 10, 11]];
for (var i = 0; i < numsArr.length; i++) {
 console.log( numsArr[i])
 
 10.Write a code to print elements in the inner arrays
Output: 1234567891011

var numsArr = [[1, 2, 3, 4, 5],[ 6, 7, 8, 9, 10, 11]];
var str_all="0";
for (var i = 0; i < numsArr.length; i++) {
 var inner_array = numsArr[i];
 for(var j = 0 ; j < inner_array.length;j++ )
     str_all +=inner_array[j]
}
console.log(str_all);


//Write a code to print elements in the inner arrays
Output: 1234567891011
var numsArr = [[1, 2, 3, 4, 5],[ 6, 7, 8, 9, 10, 11]];
var str_all="";
for (var i = 0; i < numsArr.length; i++) {
 var inner_array = numsArr[i];
 for(var j = 0 ; j < inner_array.length;j++ )
     str_all +=inner_array[j]
}
console.log(str_all);


//Write a code to replace the array value — If the index is even, replace it with ‘even’.
Output: [ [“even”, 2, “even”, 4, “even”], [6, “even”, 8, “even”, 10, …] ]

var numsArr = [[1, 2, 3, 4, 5],[ 6, 7, 8, 9, 10, 11]];
for (var i = 0; i < numsArr.length; i++) {
 var inner_array = numsArr[i];
 for(var j = 0 ; j < inner_array.length;j++ )
      if(inner_array[j+1] %2 == 0 )
      {
         inner_array[j] = "even";
      }
}
console.log(numsArr);


//Write a code to print elements in the inner arrays in reverse
Output: 11 10 9 8 7 6 5 4 3 2 1

var numsArr = [[1, 2, 3, 4, 5],[ 6, 7, 8, 9, 10, 11]];
var str_all=" ";
for (var i = numsArr.length-1; i >=0; i--) {
 var inner_array = numsArr[i];
 for(var j = inner_array.length-1 ; j >=0;j--)
     str_all +=" " + inner_array[j]
}
console.log(str_all);


//Write a code to add elements in the inner arrays based on odd or even values
Output:
36
30

var numsArr = [[1, 2, 3, 4, 5],[ 6, 7, 8, 9, 10, 11]];
var sum_odd=0;
var sum_even=0;
for (var i = 0; i < numsArr.length; i++) {
 var inner_array = numsArr[i];
 for(var j = 0 ; j < inner_array.length;j++ ){
 if(inner_array[j]%2!=0)
 {
 sum_odd += inner_array[j]
 }
 else
 {
 sum_even += inner_array[j]
 }
}
}
console.log(sum_odd);
console.log(sum_even);


Part-3

//Fix the code to get the largest of three.
aa = (f,s,t) => {
    //let f,s,t;
    console.log(f,s,t);
    if(f>s &&f>t){
    console.log(f)}
    else if(s>f && s>t){
    console.log(s)}
    else{
    console.log(t)}
   }
   aa(1,2,3);
   
   
//Fix the code to Sum of the digits present in the number
let n = "123";
console.log(add(n));
function add(n)
{
let sum = 0;
for(var i=0;i<n.length;i++){
 sum+= parseInt(n[i])

 }
 return sum;
}


//Fix the code to Sum of all numbers using IIFE function
const arr = [9,8,5,6,4,3,2,1];
(function() {
 let sum = 0;
 for (var i = 0; i < arr.length; i++){
 sum += arr[i];
 }
 console.log(sum);
 return sum;
})();


//Fix the code to gen Title caps.
var ano = function(arro) {
 for (var i = 0; i <= arr.length; i++) {
 console.log(arr[i].toUpperCase() + arr[i].substr(1));
 }
}
ano();


//Fix the code to return the Prime numbers
const newArray=[1,3,2,5,10];
const myPrime=newArray.filter(num=>{
 for(let i=2;i<=num;i++){
   if(num%i!==0)
   {
      return true;
   }
   return num===1;
}
});
console.log(myPrime);


//Fix the code to sum the number in that array
const num = [10, 20, 30, 40,50,60,70,80,90,100] 
const sum = (a, b) =>
 a + b
const ans = num.reduce(sum)
console.log(ans);


//print all odd numbers in an array using IIFE function
 var arr = [1, 2, 3, 5, 7, 79, 7, 2, 6, 9, 4];
(function() {
 for (var i = 0; i < arr.length; i++) {
 if (arr[i] % 2 !== 0) {
 console.log(arr[i]);
 }}
})();


//Fix the code to reverse.
(function(str){
    let str1=" ";
    for(let i =0;i<str.length;i++){
        str1 +=" " + str[i]; 
    }
    str1=str1.split("").reverse().join("");
    console.log(str1); 
   })("abcd")
   
   
   
 //Fix the code to remove duplicates.
 function toFindDuplicates(arry) {
    const uniqueElements = new Set(arry);
    const filteredElements = arry.filter(item => {
        if (uniqueElements.has(item)) {
            uniqueElements.delete(item);
        } else {
            console.log(uniqueElements) ;
        }
    });
   }
   toFindDuplicates(['guvi','geek','guvi','duplicate','geeK'])
