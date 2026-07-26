gaduka is my programming language, and in his a much referencea.
syntax:
Name: gaduka (learn how gad'yuka)

Commentary:
/Commentary/

For adding file or library:
@name library or file

for print text:
echoLn!("text %i/f/s/c", name variable);

Variable:
tred name variable: type variable;

Pointers:
tred *pointers name: hex = &name variable; /only hex/

If/elif/else:
yo (

) yopta (

) yop (

)

for input:
writeIn! name variable;

Structure:
python name structure(
field structures
)

While:
fochan (
)

For:
pepe (
)

Examples:
pepe o v [1...10](
echoLn!("%i", o);
)

tred arr: int{3} = {1, 2, 3};
pepe h v arr (
echoLn!("el: %i", arr{h});
)

Random:
tred a: type = viper(range or variants); /Inclusive of both the first and the last number/

Break:
backPymc;

Continue:
memos;

List/hashmap:
uzh name list{
key: meaning;
}

For adding in uzh:
HashMap name.add(key, meaning);
For deleting in uzh:
HashMap name.die(key, meaning);

Switch case:
match var (
Examination => What will happen if the condition is true
_ => What will happen if none of the checks pass
)

For delete variable:
die name variable or pointer;

Work with files:
For opening file:
open.("path to file");
For writing in file:
write_to.("what do you want to write down").("path to file");
For creating file:
create.("path to file").("file name");
For reanaming file:
rena.("last file name").("new file name");
For reading file:
tred f: file = open.("path");
For closing file:
close.("path");
For delete file:
die.("path");

Arrays/vector:
tred name arrays: type{quantity element or do not specify anything for the vector};

Finding lenghg:
variable name.len();
Finding size:
variable name.sizeof();
Slice:
variable name.crisp(1...3);

For using assembler:
asm type assembler (
Code on assembler
)

Enumeration:
ydav enum name(
enumeration through ,
)

Non return function:
gadu name => type function [arguments](
)

Return function:
gadu name => type function [arguments] -> return type (
exist;
)

Example:
gadu add => d [a: int; b: int] -> int (
exist a + b;
)

Main function:
gadu main[](
)

Asynchrony:
async #number thread comand /outputs a command to a separate stream/

Example:
async #1 pepe o v 1...10 (
echoLn!("%i\n", o);
)

Type:
Compiler

Extension:
.gk

Types in gaduka:
float - %f
bin - %io /io Looks like 1 and 0, 10/
hex - %h
int - %i
string - %s
char - %c
bool - %b /true or false/

Type functions:
d - the lowest function can be used in any other function
u - the middle function can only be used in the main and u function
g - a global modificacion for function can be used in other files and can only exist with other types.
main - the main function cannot be used anywhere

Rules:
At the end comand print ;. If there is an error in the program, it will be highlighted in red, and the terminal will indicate the line on which the error occurred and its type.

Examples:

Hello world:
gadu main[](
echoLn!("Hello, world!\n");
)

Asking for the user's name and greeting them:
gadu main[](
tred name: string;
echoLn!("What's your name?\n");
writeIn! name;
echoLn!("Hello, %s", name);
)

Loops:
gadu main[](
tred arr: int{4} = {1, 2, 3, 4};
pepe h v arr ( echoLn!("%i\n", h); )
/Or/
tred o: int = 0;
fochan o < arr.len() (
echoLn!("%i\n", arr{o});
o += 1;
)
)

Calculator:
gadu main[](
tred a: int; b: int; c: char;
echoLn!("enter first number: \n");
writeIn! a;
echoLn!("enter second number: \n");
writeIn! b;
echoLn!("enter math symbol: \n");
writeIn! c;
yo c == '+' (
a += b;
) yopta c == '-' (
a -= b;
) yopta c == '*' (
a *= b;
) yopta c == '/' (
yo b == 0 (
echoLn!("you idiot\n")
) yop (
a /= b;
)
) yopta c == '%' (
yo b == 0 (
echoLn!("you idiot\n");
) yop (
a %= b;
)
) yopta c == '√' (
a root= b; /This is finding the root of degree a from the number b, and writing the result into the variable a/
) yopta c == '^' (
a **= b;
) yop (
echoLn!("what this symbol?: %c\n", c);
a = 1101110110111111101001101000110100111011101100111;
)
echoLn!("result %i\n", a);
)

Or: /only yo/yopta/yop part/

match c (
'+' => a += b;
'-' => a -= b;
'*' => a *= b;
'/' => ( yo b == 0 ( echoLn!("You idiot\n"); )
yop ( a /= b ) )
'^' => a **= b;
'√' => a root= b;
'%' => ( yo b == 0 ( echoLn!("You idiot\n"); ) 
yop ( a %= b; ) )
)