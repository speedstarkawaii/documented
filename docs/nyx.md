NYX as NYXIA official script documentation; modified as of 9/8/2024

# THESE ARE UP-TO-DATE #

game:HttpGet / HttpGet / httpget / game:HttpGetAsync (string: URL)
Sends a GET request to the URL provided. HttpGetAsync is a macro to HttpGet and no its not async.
⚠️ **THIS IS ROBLOXS HTTP SERVICE.**

getfpscap / getfps (return)
Returns the FPS you are getting in game. No longer returns 60 or 144.

setfpscap / setfps (int: value)
Sets robloxs fps limit to value. This no longer works.

loadstring / nyx.run / load (string src)
Returns compiled chunk. However nyx.run simply runs the script. It does not return a function. load is deprecated.

isrbxactive (return)
Returns true or false based on if ROBLOX is focused.

newcclosure (function)
Creates and pushes a new CClosure that executes function.

# FILE LIBRARY # 

readfile (path): Reads the contents of the file located at the given path and returns it. Errors if the file does not exist.

writefile (path, content): Writes the provided contents to the specified filepath. Extensions not allowed include .exe, .scr, .bat, .com, .csh, .msi, .vb, .vbs, .vbe, .ws, .wsf, .wsh, .ps1, .psy.

appendfile (path, content): Appends the provided content to the file at the specified path. Errors if the file does not exist.

loadfile (path): Loads the contents of a file as a chunk. Returns the chunk if successful; otherwise, returns nil and the error message if compilation fails.

listfiles (dir): Returns a table of files in the specified folder.

isfile (path): Checks if the specified path is a file.

isfolder (dir): Checks if the specified path is a folder.

makefolder: Creates a new folder at the specified filepath.

delfolder: Deletes the folder at the given path. Errors if no folder exists.

delfile: Deletes the file at the given path. Errors if no file exists.
