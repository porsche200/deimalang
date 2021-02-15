

# deimalang
a language written for deima! edit the deimalang_src.txt file to start coding. open the application to run your code.

# DAPI (dei p-i)
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
`text ToText(number x)` </br>
converts number x into text. returns null if not possible </br>
`number ToNumber(text x)` </br>
converts text x into number. returns null if not possible </br>
`number Hex(text x)` </br>
converts hex to decimal  </br>

**> console** </br>
`void NewLine()` </br>
prints a new line into the console </br>
`void ChangeColor(number code)` </br>
changes the console color to code </br>
`void NormalColor()` </br>
changes the console color to code </br>
`void SayLine(text msg)` </br>
says msg followed by a new line. </br>
`void SayMsg(text msg)` </br>
says msg.  </br>
`text GetLine()` </br>
reads a line of text </br>
`number GetNumber()` </br>
reads a number. </br>
`void AskNumber(number correct, text alert)` </br>
reads a number, checks if it's correct. if it's not, it prints alert and tries again </br>
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

**> cute** </br>
`void MeimaLove()` </br>
fun-ction c: </br>
