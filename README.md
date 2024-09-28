 
   

<!doctype html>
	<html>
	<head>
		<title>class 5</title>
		<meta name="viewport" content="width=device-width, initial-scale=1.0">
		<link rel="preconnect" href="https://fonts.googleapis.com">




<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Nunito+Sans:ital,wght@0,200;0,300;0,400;0,600;0,700;1,200;1,300;1,400;1,600&display=swap" rel="stylesheet">
		<link rel="stylesheet"  href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.2.0/css/all.min.css">
		
		<link rel="stylesheet"  href="css/style.css">

	</head>
	<body>

	</body>

	<script>
  

 
  
 
     
      
       // const num1 = prompt("Enter first number value:");
        

       // const operator = prompt("Enter any operator (+, -, *, /): ");
     
       //  const num2 =  prompt("Enter second number value:");
       
       //  switch(operator) 
       //  {
       //      case '+':
       //       alert(num1 + num2);
              
       //          break;   
 
       //      case '-':
       //           alert(num1 - num2);
       //             parseFloat();
       //          break; 
 
       //      case '*':
       //         alert(num1 * num2);
       //           parseFloat();
       //          break; 
 
       //      case '/':
       //        alert(num1 / num2);
       //          parseFloat();
       //          break; 
 
       //          default: 
       //          alert("You have entered wrong operator or value");


       //  }


//     switch case

//    var percent = prompt("enter your percentage");  

//  switch (true) {

//   case (percent >= 60):
//   document.write("ist division");
//   break;

//   case (percent >=45 && percent < 60):
//  document.write("2nd division");
//   break;

//  case  (percent >= 33 && percent < 45):
//   document.write("3rd division");
//   break;

//   default:
//  document.write("fail");

// }



 /*ternairy operator
 The conditional (ternary) operator is the only JavaScript operator that takes three operands: 
 a condition followed by a question mark ( ? ), then an expression to execute if the condition
 is truthy followed by a colon ( : ), and finally the expression to execute if the condition 
 is falsy.
  var percent = prompt("enter your percentage");

  percent >= 60 ? alert('ist division'): 
  percent >= 45 && percent < 60 ? alert('2nd division') :
  percent >= 33 && percent < 45 ? alert('3rd division') : alert('fail');*/
  

 // Function //


 /*function calculate() {

    var a = 100;
    var b = 50;


    var sum = a + b;


    console.log(sum);
  
  }

  calculate();*/
  
  /* function calculate() {

    var a = 100;
    var b = 50;


     return a + b;
  }
 
   var check = calculate();
   console.log(check);*/

//function calculate(a,b) {

	//return a - b;

//}
//var age = calculate(2022, 2001);
//console.log(age);
  
 // function //

 //function calculateage(birthyear){

 //return 2022 - birthyear;


//}
//var cal = calculateage(1978);
//console.log(cal);

//function yearsUntillRetirment(year){
  
//  var age = calculateage(year);



 // }
 //console.log(calculateage(1978));

 // key value pairs

// let key1 = 'name';
// let value1 = 'Naveen';

// let key2 = 'born';
// let value2 = '2001';

// const person = {
//   [key1] : value1,
//   [key2] : value2,

// }

// console.log(person.name)




 // hoisting in js

 // z = 5;

 // console.log(z);
 // var z;


 // Indentifires
 // $
 // _
 // (0-9)

//  var b = 36;

// function greeting(){
//    b = 'Hello world';
//    console.log(b);
//  var b ;
  

// }
// greeting();
// console.log(b)



// function calsi(p,r,t){

//   var SI = (p*r*t)/100;

// return SI;

 
// }


//  console.log(calsi(50000,8.5,2));

// JavaScript variables have different scopes, they are:
// Global Scope.
//0 Local Scope.
// Block Scope.
// Function Scope.


// Array
// Array is collection of similiar datatype //
//Index = Define the postion. Start from zero //
 // var arr = [24, 18, 20, 26]
 //  console.log(arr.length);
 //  console.log(arr[4]);
 //  console.log(typeof(arr));
 //  var check = arr.indexOf(26);
 //  console.log(check);

 // arr.push(55);
 // console.log(arr);
 // arr.pop(55);
 // console.log(arr);
 // arr.unshift(55);
 // console.log(arr);
    
//  let car = {

// company : 'Maruti',
// name : 'Swift',
// color : 'red',
// fuel :'gas',
// price :'500000'



//  }
//  console .log(car.company, car.name, car.color, car.fuel, car.price);

//1. Map //

// const arr = [24, 28, 78, 6, 9];
// const arr1 = arr.map(item => item * 2);
// console.log(arr1);

// // 2.  Filter //
// const arr2 = arr.filter(item => item % 2 === 0);
// console.log(arr2);


// const num = [1,2,3,4]

// const ary = num.map(number);
// console.log(ary);

// function number(num){
// return num * 2

// }


//Reduce //
//  const tarr = [1,2,3,4,5];
//  const newarr = arr.reduce(function(result,item){
//            return result + item;})
//        console.log(arr);
//        console.log(newarr);

// const arr =[14, -74, 28, 95, -23, 54, 10, -9, 32 ];
//     const newarr = arr.filter(item =>item > 0);
//     const new2arr = newarr.reduce(function(result,value){
//         return result+value;
//     })
//     console.log(new2arr);

// Loops //

   // For Loop //

// for(intialization, condition, updation) {
//   loop body
// }


// for (let i = 0; i < 10; i++) {
//   console.log(i);
// }



// While 

// while(condition) {
//    loop body / code to be executed
// }

// let i = 5
// while(i < 10) {
//    console.log('The given no.is ' +  i)
//  i++;
// }

// setTimeout //
// setTimeout( () =>{
//    console.log('Message from settimeout')

// },5000);

// first class function //
// const func = ()=> {
//    console.log('fist class function');

// }
// func();

















		
</script>

	</html>













  
