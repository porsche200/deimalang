# deimalang
a language written for deima

# DAPI (dei p-i)
welcome to the official deimalang api!

// text
text SubText(text txt, number off, number distance) - subtexts with offset, and optional distance
text ReverseText(text txt) - reverses text
text ToLowerCase(text txt) - makes text lowercase
text ToUpperCase(text txt) - makes text uppercase
text ReplaceAll(text txt, text replace, text replacement) - replace text in txt with a replacement

// math
number RandomNumber(number x, number y) - prints a random number between x and y
number Pow(number x, number y) - returns x to the power of y
text ToText(number x) - converts number x into text. returns null if not possible
number ToNumber(text x) - converts text x into number. returns null if not possible
number Hex(text x) - converts hex to decimal 

// console
void NewLine() - prints a new line into the console
void ChangeColor(number code) - changes the console color to code
void NormalColor() - changes the console color to code
void SayLine(text msg) - says msg followed by a new line.
void SayMsg(text msg) - says msg. 
text GetLine() - reads a line of text
number GetNumber() - reads a number.
void AskNumber(number correct, text alert) - reads a number, checks if it's correct. if it's not, it prints alert and tries again
void AskLine(text correct, text alert) - reads a line, checks if it's correct. if it's not, it prints alert and tries again
void AskCaseLine(text correct, text alert) - reads a line, checks if it's correct (case sensitive). if it's not, it prints alert and tries again
void ClearConsole() - clears the console text
void SetBackgroundColor(number code) - sets the background color to code

// system
void Sleep(number seconds) - Sleeps for seconds amount of time
number GetTime() - returns the UTC timestamp
text FormatTime(number time, text fmt) - formats the time
void ExitProgram() - closes the program
void Pause() - waits for user to press a button to continue
void ChangeTitle(text title) - changes the title of the program

// cute
void MeimaLove() - fun-ction
