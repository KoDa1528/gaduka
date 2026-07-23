gaduka is my programming language, and in his a much referencea.
syntax:
Name: gaduka (learn how gad'yuka)

Commentary:
/Commentary/

For adding file or library:
@name library or file

for print text:
echoLn("text %i/f/s/c", name variable);

Variable:
tred name variable: type variable;

Pointers:
tred *name pointers: int;

If/elif/else:
yo (

) yopta (

) yop

for input:
writeIn name variable;

Structure:
python name structure(
field and methods structures
)

While:
fochan (
)

For:
pepe (
)

Examples:
pepe o v [1...10](
echoLn("%i", o);
)

tred arr: int{3} = 1, 2, 3;
pepe h v arr (
echoLn("el: %i", arr{h});
)

Break:
backPymc;

Continue:
memos;

List:
uzh name list(
name => meaning;
)

For delete variable:
die name variable or pointer;

For opening file:
tred name variable: file = path to file;

Arrays/vector:
tred name arrays: type{quantity element or do not specify anything for the vector};

function:
gadu name function[arguments](
)

Asynchrony:
async comand /outputs a command to a separate stream/

Type:
Compiler

Extension:
.gk

Rules:
In end comand print ;.

Calculator:
tred a: int; b: int; c: char;
echoLn("enter first number: \n");
writeIn a;
echoLn("enter second number: \n");
writeIn b;
echoLn("enter math symbol: \n");
writeIn c;
yo c == + (
a += b;
) yopta c == - (
a -= b;
) yopta c == * (
a *= b;
) yopta c == / (
yo b == 0 (
echoLn("you idiot\n")
) yop (
a /= b;
)
) yopta c == % (
yo b == 0 (
echoLn("you idiot\n");
) yop (
a %= b;
)
) yopta c == √ (
a ÷= b; /This is finding the root of degree a from the number b, and writing the result into the variable a/
) yopta c == ^ (
a **= b;
) yop (
echoLn("what this symbol?\n")
)
echoLn("result %i\n", a);