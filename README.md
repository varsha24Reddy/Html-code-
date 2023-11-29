
<!DOCTYPE html>
<html>
<head> 
    <title> Scientific Calculator </title>
<style>
#calculator {
    width: 500px;
    height: 400px;
    border: 1px solid black;
    display: grid;
    grid-template-columns: repeat(5, 1fr);
    grid-template-rows: repeat(5, 1fr);
    gap: 1px;
}
input[type="button"] {
    width: 100%;
    height: 100%;
}
</style>
</head>
<body>
<div id="calculator">
    <input type="button" value="2" onclick="buttonClick('2n')">
    <input type="button" value="n" onclick="buttonClick('n')">
    <input type="button" value="2" onclick="buttonClick('2')">
    <input type="button" value="C" onclick="buttonClick('C')">
    <input type="button" value="*" onclick="buttonClick('*')">
    <input type="button" value="x2" onclick="buttonClick('x2')">
    <input type="button" value="1/x" onclick="buttonClick('1/x')">
    <input type="button" value="|x|" onclick="buttonClick('|x|')">
    <input type="button" value="exp" onclick="buttonClick('exp')">
    <input type="button" value="mod" onclick="buttonClick('mod')">
    <input type="button" value="2x" onclick="buttonClick('2x')">
    <input type="button" value="(" onclick="buttonClick('(')">
    <input type="button" value=")" onclick="buttonClick(')')">
    <input type="button" value="x!" onclick="buttonClick('x!')">
    <input type="button" value="/" onclick="buttonClick('/')">
    <input type="button" value="xy" onclick="buttonClick('xy')">
    <input type="button" value="7" onclick="buttonClick('7')">
    <input type="button" value="8" onclick="buttonClick('8')">
    <input type="button" value="9" onclick="buttonClick('9')">
    <input type="button" value="*" onclick="buttonClick('*')">
    <input type="button" value="10" onclick="buttonClick('10')">
    <input type="button" value="4" onclick="buttonClick('4')">
    <input type="button" value="5" onclick="buttonClick('5')">
    <input type="button" value="6" onclick="buttonClick('6')">
    <input type="button" value="-" onclick="buttonClick('-')">
    <input type="button" value="log" onclick="buttonClick('log')">
    <input type="button" value="1" onclick="buttonClick('1')">
    <input type="button" value="2" onclick="buttonClick('2')">
    <input type="button" value="3" onclick="buttonClick('3')">
    <input type="button" value="+" onclick="buttonClick('+')">
    <input type="button" value="ln" onclick="buttonClick('ln')">
    <input type="button" value="%" onclick="buttonClick('%')">
    <input type="button" value="0" onclick="buttonClick('0')">
    <input type="button" value="." onclick="buttonClick('.')">
    <input type="button" value="=" onclick="buttonClick('=')">
</div>
</body>
</html>
