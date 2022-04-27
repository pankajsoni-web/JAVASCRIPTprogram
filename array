<!DOCTYPE html>
<html>
<body>

<h2>JavaScript Arrays</h2>

<p id="demo"></p>
<p id="demo1"></p>
<p id="demo2"></p>
<p id="demo3"></p>
<p id="demo4"></p>
<p id="demo5"></p>
<p id="demo6"></p>
<p id="demo7"></p>
<button onclick="myFunction()">Try it</button>


<script>
const car = ["Saab", "Volvo", "BMW"];
document.getElementById("demo").innerHTML = car;
const cars = new Array("Saab", "Volvo", "BMW");
document.getElementById("demo").innerHTML = cars;
document.getElementById("demo1").innerHTML = car[0];
car[0] = "Opel";
document.getElementById("demo2").innerHTML = car;

const person = {firstName:"John", lastName:"Doe", age:46};
document.getElementById("demo3").innerHTML = person.firstName;
const fruits = ["Banana", "Orange", "Apple"];
document.getElementById("demo7").innerHTML = fruits;
document.getElementById("demo5").innerHTML = Array.isArray(fruits);
document.getElementById("demo6").innerHTML = fruits instanceof Array;
document.getElementById("demo8").innerHTML = fruits.toString();
document.getElementById("demo9").innerHTML = fruits.join(" * ");
fruits.pop();
document.getElementById("demo10").innerHTML = fruits;
document.getElementById("demo11").innerHTML = fruits.push("Kiwi");
fruits.unshift("Lemon");
document.getElementById("demo12").innerHTML = fruits;


function myFunction() {
  fruits.push("Lemon");
  document.getElementById("demo4").innerHTML = fruits;
}

const myGirls = ["Cecilie", "Lone"];
const myBoys = ["Emil", "Tobias", "Linus"];
const myChildren = myGirls.concat(myBoys);

document.getElementById("demo13").innerHTML = myChildren;
</script>

</body>
</html>
