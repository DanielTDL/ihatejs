Syntax & Basics
variable = A container that stores a value.

let vs const vs var
const cannot be reassign.
var is function-scoped → It’s only limited inside a function but ignores block scopes (if, for, etc.).
let is block-scoped → It stays inside the block ({}) where it’s declared.
var is hoisted to the top with undefined as default value.
let is hoisted, but it is NOT initialized—accessing it before declaration causes an error.
var can be redeclared in the same scope.
let cannot be redeclared in the same scope.
Use let by default—it’s safer, avoids accidental redeclaration, and follows modern best practices.
Avoid var unless working with very old JavaScript code.

data types:
String
Number
Bigint
Boolean
Undefined
Null
Symbol
Object

operators:
operands (variable, value, etc.)
operators (+, -, /, *, %, **)

let mom = 5 
//mom = mom + 1;  6
//mom = mom - 1;  4
//mom = mom / 2;  2.5  
//mom = mom * 2;  10
//mom = mom % 2;  1  
//mom = mom ** 2; 25

//mom += 1;  6
//mom -= 1;  4
//mom /= 2;  2.5
//mom *= 2;  10
//mom %= 2;  1
//mom **= 2; 25 

//mom++;
//mom--;

operator precedence
    1. parenthesis ()
    2. exponents **
    3. multiplication * & division / & modulo %
    4. addition + & substraction -

//single line comment

/*   multi
     line
     comment
*/

=============================================================================================================================================


