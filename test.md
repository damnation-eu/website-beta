---
---
<html>
<head>
<title>HTML Calculator</title>
</head>
<body>

<form name="calculator" >
<input type="button" value="Feudalism" onClick="document.calculator.calc.value+='0.3*0.5'">
<input type="button" value="Monarchy" onClick="document.calculator.calc.value+='0.55*0.75'">
<input type="button" value="Fascism" onClick="document.calculator.calc.value+='0.9*1'">
<input type="button" value="Communism" onClick="document.calculator.calc.value+='0.7*1.25'">
<input type="button" value="Republic" onClick="document.calculator.calc.value+='0.75*1.5'">

<input type="textfield" name="calc" value="">
<input type="reset" value="Reset">

<input type="button" value="=" onClick="document.calculator.ans.value=eval(document.calculator.calc.value)">
<br>Solution is <input type="textfield" name="ans" value="">
</form>
 
</body>
</html>
