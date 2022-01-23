# loops-and-iteration-exersice



let firstNumber = prompt("Escribe un número");    
let secondNumber = prompt("Escribe un número");
firstNumber = parseInt(firstNumber);
secondNumber = parseInt(secondNumber);

if (firstNumber == secondNumber) {
console.log(`El número ${firstNumber} y el número ${secondNumber} son iguales`);
}
else if (firstNumber < secondNumber) {
console.log(`El número ${firstNumber} es menor que el número ${secondNumber}`);
} else if (firstNumber > secondNumber) {
console.log(`El número ${firstNumber} es mayor que el número ${secondNumber}`);
} else {
  console.log("Los números no son correctos");
}



var firstNumber = prompt("Escribe un número");  
while (firstNumber <= 0){
    firstNumber = prompt("Introduce un número mayor de cero");
}
    var secondNumber = prompt("Escribe un número");
while (secondNumber <= 0) {
    secondNumber = prompt("Introduce un número mayor de cero");
} 

firstNumber = parseInt(firstNumber);
secondNumber = parseInt(secondNumber);
