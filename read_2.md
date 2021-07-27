# Choosing a text editor

When you start coding you will end up spending a lotttt of time in a text editor, writing and (mostly) reading your code. Text editors can have lots of useful features.
Features such as auto complete your typing (very useful for preventing typos when referencing functions/variables), auto format your code (things like indention, closing parenthesis you 
opened), and color code your code to make it easier to read.

## Third party text editors
- Notepad++ 

Notepad++ is windows only, no go.

- text wrangler/BB edit

text wrangler is retired as of 2017, and BB edit is pay to play, no go.

- Atom

Atom is designed and maintained by developers at github. an excellent free choice with lots of flexibility.

- Visual Studio Code

VS Code is a free software developed and maintained by microsoft. It performs equally well on Windows, MacOS, and Linux. VS Code also features an impressive list of 
free extensions.
Additionally, according to my own survey (n = 1) 100% of participants agreed, VS Code has the BEST dark mode, and thats really what it comes down to.

## IDEs
An IDE is a text editor, a file
manager, a compiler, and a debugger all in one software package.

# Terminal

its all of the things that scare you about computers, in one place. It is also the exact same thing you are always using, you just didnt know it. Its what happens in the 
background as you do all the "normal" things you are used to doing.

---

pwd | print working directory | tells you where you currently are
ls | list | lists the files/folders in your current directory
ls -a | list | lists all files/folders in current directory (including hiden files)
ls -l | list | lists all files & additional info
| ls -1 | list | lists files one file per line |
| ~ | home directory | shortcut to home |
| . | current directory | where you are now |
| .. | parent directory | the folder your current directory is in |
| cd | change directory | takes you to home directory |
| cd \[directory] | change directory | changes directory to \[directory] |

---

| tab | auto complete | finishes typing, automatically completes your typed entry if a given filepath exists |
| code .\[file] | VS code | opens VC code or opens \[file] with VS code |
| mkdir \[name] | make directory | makes a folder \[name] |
| touch \[file] | make file | creates \[file] |
| cp \[file]\[directory] | copy | copys \[file] to \[directory] |
| mv \[file]\[dir] | move | moves file to dir |
| brew install \[thing] | home brew | installs \[thing] |
| brew list | home brew | lists all home brew installed items |
| brew upgrade | home brew | updates home brew installed items |
| brew update | homme brew | returns latest version of home brew installed items |
| brew cleanup | home brew | removes outdated files |
| find \[dir] -name\[file] | search | returns \[file] inside \[dir] |
| grep "\[words]" \[file] | search | returns \[text] inside \[file] |
| grep -rl "\[words]" \[dir] | search | returns file containing \[text] inside \[dir] |
