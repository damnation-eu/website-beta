---
---
<html>
<head>
</head>
<body>


<form name="calculator" oninput="x.value=parseInt(a.value)*(parseInt(govt.value)/10000)">
<input type="button" value="Feudalism" onClick="document.calculator.govt.value='1500'">
<input type="button" value="Monarchy" onClick="document.calculator.govt.value='4125'">
<input type="button" value="Fascism" onClick="document.calculator.govt.value='9000'">
<input type="button" value="Communism" onClick="document.calculator.govt.value='9375'">
<input type="button" value="Republic" onClick="document.calculator.govt.value='11250'">


<br/>
0<input type="range" id="a" max="10000" step="1" value="100">10000
<input type="hidden" name="govt" id="govt" value="10000">
<br/>
<output name="x" for="a govt"></output>
</form>
 
</body>
</html>
