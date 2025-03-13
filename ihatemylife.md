<p>
Syntax & Basics<br>
variable = A container that stores a value.<br>
</p>

<p>
let vs const vs var<br>
const cannot be reassign.<br>
var is function-scoped → It’s only limited inside a function but ignores block scopes (if, for, etc.).<br>
let is block-scoped → It stays inside the block ({}) where it’s declared.<br>
var is hoisted to the top with undefined as default value.<br>
let is hoisted, but it is NOT initialized—accessing it before declaration causes an error.<br>
var can be redeclared in the same scope.<br>
let cannot be redeclared in the same scope.<br>
Use let by default—it’s safer, avoids accidental redeclaration, and follows modern best practices.<br>
Avoid var unless working with very old JavaScript code.<br>
</p>

<p>
data types:<br>
String<br>
Number<br>
Bigint<br>
Boolean<br>
Undefined<br>
Null<br>
Symbol<br>
Object<br>
</p>

<p>
operators:<br>
operands (variable, value, etc.)<br>
operators (+, -, /, *, %, **)<br>
</p>

<p>
let mom = 5 <br>
//mom = mom + 1;  6 <br>
//mom = mom - 1;  4 <br>
//mom = mom / 2;  2.5  <br>
//mom = mom * 2;  10 <br>
//mom = mom % 2;  1  <br>
//mom = mom ** 2; 25 <br>
</p> 

<p>
//mom += 1;  6 <br>
//mom -= 1;  4 <br>
//mom /= 2;  2.5 <br>
//mom *= 2;  10 <br>
//mom %= 2;  1 <br>
//mom **= 2; 25 <br>
</p>

<p>
//mom++; <br>
//mom--; <br>
</p>

<p> 
    <ol>
        <li>operator precedence    </li>
        <li>parenthesis ()    </li>
        <li>exponents **    </li>
        <li>multiplication * & division / & modulo %    </li>
        <li>addition + & substraction -    </li>
    </ol>
</p>

<p>
//single line comment <br>

/*   multi <br>
     line <br>
     comment <br>
*/ <br>
</p>
=============================================================================================================================================


