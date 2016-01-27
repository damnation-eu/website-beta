---
---
<html>
<head>
</head>
<style type="text/css">
input[type=button] {
    color:#08233e;
    font:2.4em Futura, ‘Century Gothic’, AppleGothic, sans-serif;
    font-size:70%;
    padding:14px;
    background:url(overlay.png) repeat-x center #ffcc00;
    background-color:rgba(255,204,0,1);
    border:1px solid #ffcc00;
    -moz-border-radius:10px;
    -webkit-border-radius:10px;
    border-radius:10px;
    border-bottom:1px solid #9f9f9f;
    -moz-box-shadow:inset 0 1px 0 rgba(255,255,255,0.5);
    -webkit-box-shadow:inset 0 1px 0 rgba(255,255,255,0.5);
    box-shadow:inset 0 1px 0 rgba(255,255,255,0.5);
    cursor:pointer;
}
input[type=button]:hover {
    background-color:rgba(255,204,0,0.8);
}
</style>

<body>



<center><form name="calculator" oninput="x.value=parseInt(a.value)*(parseInt(govt.value)/10000)">
<input type="button" value="Feudalism" onClick="feudalism()">
<input type="button" value="Monarchy" onClick="document.calculator.govt.value='4125'">
<input type="button" value="Fascism" onClick="document.calculator.govt.value='9000'">
<input type="button" value="Communism" onClick="document.calculator.govt.value='9375'">
<input type="button" value="Republic" onClick="document.calculator.govt.value='11250'">


<br/>
0<input type="range" id="a" max="100" step="1" value="100">100
<input type="hidden" name="govt" id="govt" value="10000">
<br/>
<output name="x" id="x" for="a govt" value="0"></output> Rupees
</form></center>

<script>
function feudalism() {
    document.calculator.govt.value='1500'
    document.calculator.num.value='1500'
    document.calculator.x.value=eval(document.calculator.x.value
}
</script>
 
 
</body>
</html>
