# my_calculator
<!DOCTYPE html><html><head>
<title>Calculator</title><meta charset="utf-8">
<script type="text/javascript">
function cube() {
 var num = document.getElementById("n1");
 num.value = Math.pow(num.value, 3);
}
function sin() {
 var num = document.getElementById("n1");
 num.value = Math.sin(num.value);
}
function fourth() {
 var num = document.getElementById("n1");
 num.value = Math.pow(num.value, 4);
}
</script>
</head>
<body>
 <h1>Calculadora de Jairo Zambrano</h1>
 Number:CALCULADORA
 <input type="text" id="n1">
 <p>
 <button onclick="cube()"> x^3 </button>
 <button onclick="sin()"> sin(x) </button>
 <button onclick="fourth()"> x^4 </button>
 </p>
</body>
</html>
