# LIST OF FUNCTIONS #

these are basic functions which any basic script needs. more mods are always welcome :)

game:HttpGet or HttpGet or HttpGetAsync
sends an HTTP GET request to a specified URL and retrieves the response.
⚠️ httpgetasync does not need to be async. its a macro for httpget.

loadstring or load
takes a string containing Lua code and compiles it into a callable function. If the string is valid Lua code, loadstring returns the compiled function

getthreadidentity or getidentity or getthreadcontext
returns the exploits thread or "level"

setthreadidentity or setidentity or setthreadcontext
modifies the current identity of the exploit

game:GetObjects or GetObjects or getobjects
used to retrieve assets or models from a given asset ID or URL 

getgenv or getglobalenv
returns the global env of the exploit

getrenv
returns the global env of the roblox game

getrunningscripts
lists the scripts of game that are running

base64encode 
encodes a given string into base64 format. this function takes a string as input and returns its base64 encoded version.

crypt.base64decode 
decodes a base64 encoded string back into its original format. this function takes a base64 encoded string as input and returns the decoded plain text.

readfile
reads the contents of a specified file. this function returns the content as a string.

listfiles
retrieves a list of file paths from a specified directory. it returns an array containing paths to all files and folders within that directory.

writefile
writes a string to a specified file. if the file does not exist, it creates it; if it does, it overwrites the content.
⚠️ must throw an error if these extensions are found: .exe, .scr, .bat, .com, .csh, .msi, .vb, .vbs, .vbe, .ws, .wsf, .wsh, .ps1, .psy.

makefolder
creates a new folder at the specified path. if the folder already exists, it does nothing.

appendfile 
appends a string to the end of a specified file. if the file does not exist, it creates it.

isfile 
checks if a given path points to a file. it returnstrueif the path is a file, andfalse otherwise.

isfolder 
checks if a given path points to a folder. it returnstrueif the path is a folder, andfalse otherwise.

delfolder 
deletes a specified folder and its contents. if the folder does not exist, it does nothing.

delfile 
deletes a specified file. if the file does not exist, it does nothing.

loadfile
loads a file as a Lua chunk and returns a function to execute it. if the file contains valid Lua code, the function can be called with arguments; otherwise, it returns an error.

dofile 
executes a Lua file and runs its code in the current environment. this function returns the result of the executed code.

mouse1click 
simulates a click of the left mouse button.

mouse1press 
simulates pressing down the left mouse button.

mouse1release 
simulates releasing the left mouse button.

mouse2click
simulates a click of the right mouse button.

mouse2press
simulates pressing down the right mouse button.

mouse2release
simulates releasing the right mouse button.

mousemoveabs 
simulates moving the mouse cursor to an absolute screen position.

mousemove
simulates moving the mouse cursor relative to its current position.

mousescroll 
simulates scrolling the mouse wheel up or down.

setclipboard or toclipboard or onclipboard
sets text to clipboard. must be a STRING only.

getclipboard or returnclipboard
returns the last content set on clipboard.

queue_on_teleport
sends a script on next teleport instance. 

getfps or returnfps
must return the fps as a number and must be rounded (no decimals)

setfpscap or setfps
limits the fps to the number that is given.

isrbxactive
returns false always, but may return true in some cases.

isluau
returns "true" if the game is luau (always luau now)


⚠️ ⬇️ these are not required as common scripts do not use these

saveinstance
saves the roblox game with the places id.
⚠️a table is optional, but is not required.

messagebox
creates a messagebox with a desc only.

ismetatable
checks if the value (table) is a metatable.



rconsoleclear 
clears the console output. this function removes all previous text from the console window.

rconsolecreate
creates a new console window. this function initializes a new console instance where output can be displayed.

rconsoledestroy 
destroys the console window. this function closes and removes the console instance from view.

rconsoleinput
sets a callback function for handling console input. this function allows you to define what happens when input is received from the console.

rconsoleprint 
prints text to the console window. this function outputs a specified string to the console for viewing.

rconsolesettitle
sets the title of the console window. this function changes the name or title of the console to a specified string.
⚠️ numbers should not be allowed.
