//Given a number. Print “odd” if the number is odd and “even” if it’s even.

let Number = +prompt("Enter a number")
if(Number % 2 === 0){
    console.log("Even")
}else{
    console.log("Odd")
}


//Given a positive integer. Bring the last digit of the number to the beginning. Print the new number. If the last digit of the inserted number is 0, number remains the same.

let input = +prompt("Enter a number");

let last_digit = input % 10;

let result = input;

if (last_digit !== 0 && last_digit !== input) {

	let without_last_digit = Math.floor(input / 10);
	result = last_digit + "" + without_last_digit;
}

alert("Result: " + result)




//Given five numbers as input. Calculate and print the average of the numbers(without using arrays).

let sum = 0;

sum += +prompt('Enter number 1:');
sum += +prompt('Enter number 2:');
sum += +prompt('Enter number 3:');
sum += +prompt('Enter number 4:');
sum += +prompt('Enter number 5:');

let result = sum / 5;

alert("Result: " + result);



//Given three numbers. Sort them by the ascending order.

let number_1 = prompt('Enter number 1');
let number_2 = prompt('Enter number 2');
let number_3 = prompt('Enter number 3');

let temporary_number;

if (number_1 > number_2) {
	temporary_number = number_1;
  number_1 = number_2;
  number_2 = temporary_number;
}

if (number_2 > number_3) {
	temporary_number = number_2;
  number_2 = number_3;
  number_3 = temporary_number;
}

if (number_1 > number_2) {
	temporary_number = number_1;
  number_1 = number_2;
  number_2 = temporary_number;
}

alert('Result: ' + number_1 + ' ' + number_2 + ' ' + number_3)




//Given the following code rewrite it using only two if operators. (Hint: use logical operators).

var n = +prompt();

var i = 0;
var j = 0;

if (n % 2 === 0) {
	i += !Math.floor(n / 10);
}

if (n % 3 === 0) {
  j += (n % 10 === 1);
}


