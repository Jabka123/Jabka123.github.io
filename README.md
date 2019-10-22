# jabka.github.io
Мой первый файл
<!DOCTYPE html>
<html>
<head>
<meta http-equiv="Content-Type"
content="text/html; charset=windows-1251">
<title>Стили</title>
<style> p {background-color: #fff;
margin: 20px auto;
font-family: Arial;
font-size: 2em;
text-transform: uppercase;
color: rgba(0,168,255,0.5);
text-shadow: 8px 8px 0 rgba(255,0,180,0.5);}
</style>
<script>
function er(){
document.getElementById("out1").value="1/x^2";
document.getElementById("out2").value="a/(b*c)";
document.getElementById("out3").value="(a/b)*c";
document.getElementById("out4").value="(a+b)/2";
document.getElementById("out5").value="5,45*(a+2b)/(2-a)";
document.getElementById("out6").value="(-b+(b^2-4*a*c)^1/2)/(2*a)";
document.getElementById("out7").value="(-b+(1/a))/(2/c)";
document.getElementById("out8").value="1/(1+(a+b)/2)";
document.getElementById("out9").value="1/(1+(1/(2+(1/(2+3/5)))";
document.getElementById("out10").value="k^(m^n)";
document.getElementById("inf1").innerHTML ="<p>"+"1/x^2"+"</p>";
document.getElementById("inf2").innerHTML ="<p>"+"a/(b*c)"+"</p>";
document.getElementById("inf3").innerHTML ="<p>"+"(a/b)*c"+"</p>";
document.getElementById("inf4").innerHTML ="<p>"+"(a+b)/2"+"</p>";
document.getElementById("inf5").innerHTML ="<p>"+"5,45*(a+2b)/(2-a)"+"</p>"
document.getElementById("inf6").innerHTML ="<p>"+"(-b+(b^2-4*a*c)^1/2)/(2*a)"+"</p>"
document.getElementById("inf7").innerHTML ="<p>"+"(-b+(1/a))/(2/c)"+"</p>"
document.getElementById("inf8").innerHTML ="<p>"+"1/(1+(a+b)/2)"+"</p>"
document.getElementById("inf9").innerHTML ="<p>"+"1/(1+(1/(2+(1/(2+3/5)))"+"</p>"
document.getElementById("inf10").innerHTML ="<p>"+"k^(m^n)"+"</p>"
}
</script>
</head>
<body>
<button onclick="er()">1.15</button>
<br>
<br>
А)<input type="text" value="а" id="out1">
<br>
<br>
Б)<input type="text" value="б" id="out2">
<br>
<br>
В)<input type="text" value="в" id="out3">
<br>
<br>
Г)<input type="text" value="г" id="out4">
<br>
<br>
Д)<input type="text" value="г" id="out5">
<br>
<br>
Е)<input type="text" value="г" id="out6">
<br>
<br>
Ж)<input type="text" value="г" id="out7">
<br>
<br>
З)<input type="text" value="г" id="out8">
<br>
<br>
И)<input type="text" value="г" id="out9">
<br>
<br>
К)<input type="text" value="г" id="out10">
<br>
<br>

<div id="inf1"></div>
<div id="inf2"></div>
<div id="inf3"></div>
<div id="inf4"></div>
<div id="inf5"></div>
<div id="inf6"></div>
<div id="inf7"></div>
<div id="inf8"></div>
<div id="inf9"></div>
<div id="inf10"></div>
</body>
</html>
