# deimalang
a language written for deima! edit the deimalang_src.txt file to start coding. open the application to run your code.

##### Table of Contents  
[DAPI (dei p-i) - Functions you can use](#headers)  
[Language Syntax - How to write the language](#headers2)  

<a name="headers"/>

## DAPI (dei p-i)

welcome to the official deimalang api!

**> text** </br>
`text SubText(text txt, number off, number distance)` </br>
subtexts with offset, and optional distance </br>

`text ReverseText(text txt)` </br>
reverses text </br>

`text ToLowerCase(text txt)` </br>
makes text lowercase </br>

`text ToUpperCase(text txt)` </br>
makes text uppercase </br>

`text ReplaceAll(text txt, text replace, text replacement)` </br>
replace text in txt with a replacement </br>

**> math** </br>
`number RandomNumber(number x, number y)` </br>
prints a random number between x and y </br>

`number Pow(number x, number y)` </br>
returns x to the power of y </br>

`text ToText(any x)` </br>
converts number x into text. returns null if not possible </br>

`number ToNumber(text x)` </br>
converts text x into number. returns null if not possible </br>

`number Hex(text x)` </br>
converts hex to decimal  </br>

**> console** </br>
`void NewLine()` </br>
prints a new line into the console </br>

`void ChangeColor(number code)` </br>
changes the console color to code  https://ss64.com/nt/color.html</br>

`void NormalColor()` </br>
sets the console text color to default. </br>

`void SayLine(text msg)` </br>
says msg followed by a new line. </br>

`void SayMsg(text msg)` </br>
says msg.  </br>

`text GetLine()` </br>
reads a line of text </br>

`number GetNumber()` </br>
reads a number. </br>

`void AskNumber(number correct, text alert)` </br>
reads a number, checks if it's correct. if it's not, it prints alert and tries again. prints and tries again if a number isnt inputted. </br>

`void AskLine(text correct, text alert)` </br>
reads a line, checks if it's correct. if it's not, it prints alert and tries again </br>

`void AskCaseLine(text correct, text alert)` </br>
reads a line, checks if it's correct (case sensitive). if it's not, it prints alert and tries again </br>

`void ClearConsole()` </br>
clears the console text </br>

`void SetBackgroundColor(number code)` </br>
sets the background color to code </br>

**> system** </br>
`void Sleep(number seconds)` </br>
Sleeps for seconds amount of time </br>

`number GetTime()` </br>
returns the UTC timestamp </br>

`text FormatTime(number time, text fmt)` </br>
formats the time </br>

`void ExitProgram()` </br>
closes the program </br>

`void Pause()` </br>
waits for user to press a button to continue </br>

`void ChangeTitle(text title)` </br>
changes the title of the program </br>

`text Version()` </br>
returns the program version

**> cute** </br>
`void MeimaLove()` </br>
fun-ction c: </br>

<a name="headers2"/>

## Language Syntax
welcome to the official syntax specs!

**> variables and types** </br>
Variables can be used to store values. A local variable starts with $ and has a name (e.g $variable), and</br>
a global variable does not need $ (e.g variable). 

To define a variable:</br>
`$variable = value`</br>

Examples:</br>
`$year = 2021`</br>
`$myname = "Henry"`</br>

To use a variable:</br>
`$variable = value`</br>
`$variable = $variable + variable`</br>
`$variable = CallBack($variable)`</br>
`$variable = Function($variable)`</br>

Examples:</br>
```
$name = GetLine()
SayLine($name)
```

Null:</br>
`$variable = null`</br>

Booleans:</br>
`true`
`false`

Examples:</br>
`$is_cute = true`
`$is_sad = false`

Numbers:</br>
`$variable = 15`</br>

Examples:</br>
`$variable = 52`</br>
`$variable = 100.5`</br>
`$variable = -12`</br>

Text:</br>
`$variable = "text"`</br>
`$variable = [[text]]`</br>

Callbacks:</br>
Callbacks are functions like AskLine or Sayline. They cannot be defined in a script.</br>

**> statements** </br>
Functions: </br>
Functions can be used to declare sections of code that can be called repeatedly.</br>
Unlike values, they CANNOT be stored in variables.</br>

```
function testfunction($arg1, $arg2){
  SayLine($arg1)
  SayLine($arg2)
}
testfunction("line one", "line 2")
```

For statements:</br>
For statements allow you to loop bodies of code. Define $start and $end (and optionally, $increment)</br>

```
// will loop 10 times
for ($start = 1, $end = 10){
  SayLine("for loop!")
}
// will loop 20 times
for ($start = 1, $end = 10, $increment = .5){
  SayLine("for loop!")
}
```

If statements:</br>
Runs code conditionally</br>

```
$name = GetLine()
if ($name == "dog") {
  SayLine("Sorry, no dogs allowed.")
  Pause()
  ExitProgram()
}
elseif ($name == "puppy"){
  SayLine("Sorry, no puppies allowed.")
  Pause()
  ExitProgram()
}
elseif ($name == "wolf"){
  SayLine("Sorry, no wolves allowed.")
  Pause()
  ExitProgram()
}
else{
  SayLine("Welcome, " + $name + "!")
}
```

While statements:</br>
Loops until a condition isn't met</br>

```
SayLine("Who are you:")
while (GetLine() != "deima"){
  SayLine("Sorry. You are not allowed in.")
  SayLine("Who are you:")
}
SayLine("Welcome, deima!")
```

Math & expressions:</br>
Add: `number + number`</br>
Combine Text: `text + text/number`</br>
Subtract: `number - number`</br>
Multiply: `number * number`</br>
Divide: `number / number`</br>
Modulo: `number % number`</br>
Xor: `number ^ number`</br>
Equals: `value == value`</br>
Not Equal to: `value != value`</br>
Greater Than: `number > number`</br>
Greater Than or Equal to: `number >= number`</br>
Less Than: `number < number`</br>
Less Than or Equal to: `number <= number`</br>
Not: `!value`</br>
Get length of: `#number/text`</br>

**> misc** </br>
Semicolons are allowed.</br>
`SayLine("hello");`</br>

Comments:</br>
`// hello one line comment`</br>

```
/* hello
multiple lines

allowed in this comment
*/
```



