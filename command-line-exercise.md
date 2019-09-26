```bash

Last login: Thu Sep 26 10:41:46 on ttys001
SSH Key already known.
(base) [Jatin@Jiamaos-MacBook-Pro:~]
$ ls
Applications	Documents	Library		Music		Postman
Desktop		Downloads	Movies		Pictures	Public

MKDIR(1)                  BSD General Commands Manual                 MKDIR(1)

NAME
     mkdir -- make directories

SYNOPSIS
     mkdir [-pv] [-m mode] directory_name ...

DESCRIPTION
     The mkdir utility creates the directories named as operands, in the order
     specified, using mode rwxrwxrwx (0777) as modified by the current
     umask(2).

     The options are as follows:

     -m mode
             Set the file permission bits of the final created directory to
             the specified mode.  The mode argument can be in any of the for-
             mats specified to the chmod(1) command.  If a symbolic mode is
             specified, the operation characters ``+'' and ``-'' are inter-
             preted relative to an initial mode of ``a=rwx''.

     -p      Create intermediate directories as required.  If this option is
             not specified, the full path prefix of each operand must already
             exist.  On the other hand, with this option specified, no error
             will be reported if a directory given as an operand already
             exists.  Intermediate directories are created with permission
             bits of rwxrwxrwx (0777) as modified by the current umask, plus
(base) [Jatin@Jiamaos-MacBook-Pro:~]
$ cd Desktop/
(base) [Jatin@Jiamaos-MacBook-Pro:~/Desktop]
$ touch coffee
(base) [Jatin@Jiamaos-MacBook-Pro:~/Desktop]
$ ls
20190909firstApp copy
GitHub Desktop.app
H. George Burkitt , Clive R. G. Quick, Joanna B Reed, Philip J. Deakin - Essential Surgery_ Problems, Diagnosis and Management (MRCS Study Guides) 4th ed-Churchill Livingstone (2007).chm
Mypapers
RStudio.app
Visual Studio Code.app
coffee
empty-lease-receipt.xltx
first-app
github-picture.jpg
tumblrTEST.gif
(base) [Jatin@Jiamaos-MacBook-Pro:~/Desktop]
$ man folder
No manual entry for folder
(base) [Jatin@Jiamaos-MacBook-Pro:~/Desktop]
$ man mkdir
(base) [Jatin@Jiamaos-MacBook-Pro:~/Desktop]
$ mkdir coffee
mkdir: coffee: File exists
(base) [Jatin@Jiamaos-MacBook-Pro:~/Desktop]
$ mkdir tea
(base) [Jatin@Jiamaos-MacBook-Pro:~/Desktop]
$ ls
20190909firstApp copy
GitHub Desktop.app
H. George Burkitt , Clive R. G. Quick, Joanna B Reed, Philip J. Deakin - Essential Surgery_ Problems, Diagnosis and Management (MRCS Study Guides) 4th ed-Churchill Livingstone (2007).chm
Mypapers
Postman.app
RStudio.app
Visual Studio Code.app
empty-lease-receipt.xltx
first-app
github-picture.jpg
tumblrTEST.gif
(base) [Jatin@Jiamaos-MacBook-Pro:~/Desktop]
$ ls -F
20190909firstApp copy/
GitHub Desktop.app/
H. George Burkitt , Clive R. G. Quick, Joanna B Reed, Philip J. Deakin - Essential Surgery_ Problems, Diagnosis and Management (MRCS Study Guides) 4th ed-Churchill Livingstone (2007).chm
Mypapers/
Postman.app/
RStudio.app/
Visual Studio Code.app/
empty-lease-receipt.xltx
first-app/
github-picture.jpg
tumblrTEST.gif
(base) [Jatin@Jiamaos-MacBook-Pro:~/Desktop]
$ cd first-app/
(base) [Jatin@Jiamaos-MacBook-Pro:~/Desktop/first-app]
$ cd introToCommandLine/
(base) [Jatin@Jiamaos-MacBook-Pro:~/Desktop/first-app/introToCommandLine]
$ ls
cory.txt	exercise.md	hello.html	index.html	message.txt
(base) [Jatin@Jiamaos-MacBook-Pro:~/Desktop/first-app/introToCommandLine]
$ mkdir Animals
(base) [Jatin@Jiamaos-MacBook-Pro:~/Desktop/first-app/introToCommandLine]
$ ls
Animals		exercise.md	index.html
cory.txt	hello.html	message.txt
(base) [Jatin@Jiamaos-MacBook-Pro:~/Desktop/first-app/introToCommandLine]
$ cd Animals
(base) [Jatin@Jiamaos-MacBook-Pro:~/Desktop/first-app/introToCommandLine/Animals]
$ ls
(base) [Jatin@Jiamaos-MacBook-Pro:~/Desktop/first-app/introToCommandLine/Animals]
$ mkdir Awesomenimals
(base) [Jatin@Jiamaos-MacBook-Pro:~/Desktop/first-app/introToCommandLine/Animals]
$ mkdir SketchyAnimals
(base) [Jatin@Jiamaos-MacBook-Pro:~/Desktop/first-app/introToCommandLine/Animals]
$ ls
Awesomenimals	SketchyAnimals
(base) [Jatin@Jiamaos-MacBook-Pro:~/Desktop/first-app/introToCommandLine/Animals]
$ cd ..
(base) [Jatin@Jiamaos-MacBook-Pro:~/Desktop/first-app/introToCommandLine]
$ ls
Animals		exercise.md	index.html
cory.txt	hello.html	message.txt
(base) [Jatin@Jiamaos-MacBook-Pro:~/Desktop/first-app/introToCommandLine]
$ cd Animals/
(base) [Jatin@Jiamaos-MacBook-Pro:~/Desktop/first-app/introToCommandLine/Animals]
$ ls
Awesomenimals	SketchyAnimals
(base) [Jatin@Jiamaos-MacBook-Pro:~/Desktop/first-app/introToCommandLine/Animals]
$ rm -rf Awesomenimals/
(base) [Jatin@Jiamaos-MacBook-Pro:~/Desktop/first-app/introToCommandLine/Animals]
$ mkdir AwesomeAnimals
(base) [Jatin@Jiamaos-MacBook-Pro:~/Desktop/first-app/introToCommandLine/Animals]
$ ls
AwesomeAnimals	SketchyAnimals
(base) [Jatin@Jiamaos-MacBook-Pro:~/Desktop/first-app/introToCommandLine/Animals]
$ cd AwesomeAnimals/
(base) [Jatin@Jiamaos-MacBook-Pro:~/Desktop/first-app/introToCommandLine/Animals/AwesomeAnimals]
$ touch Capybara.js
(base) [Jatin@Jiamaos-MacBook-Pro:~/Desktop/first-app/introToCommandLine/Animals/AwesomeAnimals]
$ touch ArticZFox.html
(base) [Jatin@Jiamaos-MacBook-Pro:~/Desktop/first-app/introToCommandLine/Animals/AwesomeAnimals]
$ touch TreeFrog.txt
(base) [Jatin@Jiamaos-MacBook-Pro:~/Desktop/first-app/introToCommandLine/Animals/AwesomeAnimals]
$ ls
ArticZFox.html	Capybara.js	TreeFrog.txt
(base) [Jatin@Jiamaos-MacBook-Pro:~/Desktop/first-app/introToCommandLine/Animals/AwesomeAnimals]
$ cd ..
(base) [Jatin@Jiamaos-MacBook-Pro:~/Desktop/first-app/introToCommandLine/Animals]
$ ls
AwesomeAnimals	SketchyAnimals
(base) [Jatin@Jiamaos-MacBook-Pro:~/Desktop/first-app/introToCommandLine/Animals]
$ cd Sketchy Animals
-bash: cd: Sketchy: No such file or directory
(base) [Jatin@Jiamaos-MacBook-Pro:~/Desktop/first-app/introToCommandLine/Animals]
$ cd SketchyAnimals/
(base) [Jatin@Jiamaos-MacBook-Pro:~/Desktop/first-app/introToCommandLine/Animals/SketchyAnimals]
$  ls
(base) [Jatin@Jiamaos-MacBook-Pro:~/Desktop/first-app/introToCommandLine/Animals/SketchyAnimals]
$ touch BrownReculse.html
(base) [Jatin@Jiamaos-MacBook-Pro:~/Desktop/first-app/introToCommandLine/Animals/SketchyAnimals]
$ touch BulletAnt.js
(base) [Jatin@Jiamaos-MacBook-Pro:~/Desktop/first-app/introToCommandLine/Animals/SketchyAnimals]
$ ls
BrownReculse.html	BulletAnt.js
(base) [Jatin@Jiamaos-MacBook-Pro:~/Desktop/first-app/introToCommandLine/Animals/SketchyAnimals]
$ mkdir snake
(base) [Jatin@Jiamaos-MacBook-Pro:~/Desktop/first-app/introToCommandLine/Animals/SketchyAnimals]
$ cd snake
(base) [Jatin@Jiamaos-MacBook-Pro:~/Desktop/first-app/introToCommandLine/Animals/SketchyAnimals/snake]
$ touch cobra.css
(base) [Jatin@Jiamaos-MacBook-Pro:~/Desktop/first-app/introToCommandLine/Animals/SketchyAnimals/snake]
$ touch ReticulatedPython.py
(base) [Jatin@Jiamaos-MacBook-Pro:~/Desktop/first-app/introToCommandLine/Animals/SketchyAnimals/snake]
$ ls
ReticulatedPython.py	cobra.css
(base) [Jatin@Jiamaos-MacBook-Pro:~/Desktop/first-app/introToCommandLine/Animals/SketchyAnimals/snake]
$ cd ..
(base) [Jatin@Jiamaos-MacBook-Pro:~/Desktop/first-app/introToCommandLine/Animals/SketchyAnimals]
$ ls
BrownReculse.html	BulletAnt.js		snake
(base) [Jatin@Jiamaos-MacBook-Pro:~/Desktop/first-app/introToCommandLine/Animals/SketchyAnimals]
$ rm -rf BulletAnt.js
(base) [Jatin@Jiamaos-MacBook-Pro:~/Desktop/first-app/introToCommandLine/Animals/SketchyAnimals]
$ ls
BrownReculse.html	snake
(base) [Jatin@Jiamaos-MacBook-Pro:~/Desktop/first-app/introToCommandLine/Animals/SketchyAnimals]
$ cd ..
(base) [Jatin@Jiamaos-MacBook-Pro:~/Desktop/first-app/introToCommandLine/Animals]
$ ls
AwesomeAnimals	SketchyAnimals
(base) [Jatin@Jiamaos-MacBook-Pro:~/Desktop/first-app/introToCommandLine/Animals]
$ cd //
(base) [Jatin@Jiamaos-MacBook-Pro://]
$ cd ..
(base) [Jatin@Jiamaos-MacBook-Pro://]
$ ls
Applications			bin				private
Library				cores				sbin
Network				dev				tmp
System				etc				usr
Users				home				var
Volumes				installer.failurerequests
anaconda3			net
(base) [Jatin@Jiamaos-MacBook-Pro://]
$ cd Desktop
-bash: cd: Desktop: No such file or directory
(base) [Jatin@Jiamaos-MacBook-Pro://]
$ cd Users
(base) [Jatin@Jiamaos-MacBook-Pro://Users]
$ ls
Jatin		Shared		jiamaozheng
(base) [Jatin@Jiamaos-MacBook-Pro://Users]
$ Cd Jatin
(base) [Jatin@Jiamaos-MacBook-Pro://Users]
$ Cd Desktop
/usr/bin/Cd: line 4: cd: Desktop: No such file or directory
(base) [Jatin@Jiamaos-MacBook-Pro://Users]
$ cd desktop
-bash: cd: desktop: No such file or directory
(base) [Jatin@Jiamaos-MacBook-Pro://Users]
$ ls
Jatin		Shared		jiamaozheng
(base) [Jatin@Jiamaos-MacBook-Pro://Users]
$ cd Jatin/
(base) [Jatin@Jiamaos-MacBook-Pro://Users/Jatin]
$ ls
Applications	Documents	Library		Music		Postman
Desktop		Downloads	Movies		Pictures	Public
(base) [Jatin@Jiamaos-MacBook-Pro://Users/Jatin]
$ cd Desktop/
(base) [Jatin@Jiamaos-MacBook-Pro://Users/Jatin/Desktop]
$ ls
20190909firstApp copy
GitHub Desktop.app
H. George Burkitt , Clive R. G. Quick, Joanna B Reed, Philip J. Deakin - Essential Surgery_ Problems, Diagnosis and Management (MRCS Study Guides) 4th ed-Churchill Livingstone (2007).chm
Mypapers
Postman.app
RStudio.app
Visual Studio Code.app
empty-lease-receipt.xltx
first-app
github-picture.jpg
tumblrTEST.gif
(base) [Jatin@Jiamaos-MacBook-Pro://Users/Jatin/Desktop]
$ cd first-app/
(base) [Jatin@Jiamaos-MacBook-Pro://Users/Jatin/Desktop/first-app]
$ ls

RM(1)                     BSD General Commands Manual                    RM(1)

NAME
     rm, unlink -- remove directory entries

SYNOPSIS
     rm [-dfiPRrvW] file ...
     unlink file

DESCRIPTION
     The rm utility attempts to remove the non-directory type files specified on the command line.
     If the permissions of the file do not permit writing, and the standard input device is a ter-
     minal, the user is prompted (on the standard error output) for confirmation.

     The options are as follows:

     -d          Attempt to remove directories as well as other types of files.

     -f          Attempt to remove the files without prompting for confirmation, regardless of the
                 file's permissions.  If the file does not exist, do not display a diagnostic mes-
                 sage or modify the exit status to reflect an error.  The -f option overrides any
                 previous -i options.

     -i          Request confirmation before attempting to remove each file, regardless of the
                 file's permissions, or whether or not the standard input device is a terminal.
                 The -i option overrides any previous -f options.

     -P          Overwrite regular files before deleting them.  Files are overwritten three times,
                 first with the byte pattern 0xff, then 0x00, and then 0xff again, before they are
                 deleted.

     -R          Attempt to remove the file hierarchy rooted in each file argument.  The -R option
                 implies the -d option.  If the -i option is specified, the user is prompted for
                 confirmation before each directory's contents are processed (as well as before the
                 attempt is made to remove the directory).  If the user does not respond affirma-
                 tively, the file hierarchy rooted in that directory is skipped.

     -r          Equivalent to -R.

     -v          Be verbose when deleting files, showing them as they are removed.

     -W          Attempt to undelete the named files.  Currently, this option can only be used to
                 recover files covered by whiteouts.

     The rm utility removes symbolic links, not the files referenced by the links.

     It is an error to attempt to remove the files ``.'' or ``..''.

     When the utility is called as unlink, only one argument, which must not be a directory, may be
     supplied.  No options may be supplied in this simple mode of operation, which performs an
     unlink(2) operation on the passed argument.

     The rm utility exits 0 if all of the named files or file hierarchies were removed, or if the
     -f option was specified and all of the existing files or file hierarchies were removed.  If an
     error occurs, rm exits with a value >0.

NOTE
     The rm command uses getopt(3) to parse its arguments, which allows it to accept the `--'
     option which will cause it to stop processing flag options at that point.  This will allow the
     removal of file names that begin with a dash (`-').  For example:
           rm -- -filename

RM(1)                     BSD General Commands Manual                    RM(1)

NAME
     rm, unlink -- remove directory entries

SYNOPSIS
     rm [-dfiPRrvW] file ...
     unlink file

DESCRIPTION
     The rm utility attempts to remove the non-directory type files specified on the command line.
     If the permissions of the file do not permit writing, and the standard input device is a ter-
     minal, the user is prompted (on the standard error output) for confirmation.

     The options are as follows:

     -d          Attempt to remove directories as well as other types of files.

     -f          Attempt to remove the files without prompting for confirmation, regardless of the
                 file's permissions.  If the file does not exist, do not display a diagnostic mes-
                 sage or modify the exit status to reflect an error.  The -f option overrides any
                 previous -i options.

     -i          Request confirmation before attempting to remove each file, regardless of the
                 file's permissions, or whether or not the standard input device is a terminal.
                 The -i option overrides any previous -f options.

     -P          Overwrite regular files before deleting them.  Files are overwritten three times,
                 first with the byte pattern 0xff, then 0x00, and then 0xff again, before they are
                 deleted.

     -R          Attempt to remove the file hierarchy rooted in each file argument.  The -R option
                 implies the -d option.  If the -i option is specified, the user is prompted for
                 confirmation before each directory's contents are processed (as well as before the
                 attempt is made to remove the directory).  If the user does not respond affirma-
                 tively, the file hierarchy rooted in that directory is skipped.

     -r          Equivalent to -R.

     -v          Be verbose when deleting files, showing them as they are removed.

     -W          Attempt to undelete the named files.  Currently, this option can only be used to
                 recover files covered by whiteouts.

     The rm utility removes symbolic links, not the files referenced by the links.

     It is an error to attempt to remove the files ``.'' or ``..''.

     When the utility is called as unlink, only one argument, which must not be a directory, may be
     supplied.  No options may be supplied in this simple mode of operation, which performs an
     unlink(2) operation on the passed argument.
TIL						js-hotel
Todo-List-Project				js-logic-operators
about-me					js-num-guess-game
bart-website					js-objects
basics-bootstrap				js-score-keeper
box-model					js-stalker-exercise
color-game-project-1.js				js-update-href-src
demo						js-while-loops
demo-div-tags					learn-python
dunder-mifflin-database				list-solution
first-assignment				markdown-files
first-page					node-with-git-test
fonts						person-node-test
forms						photo-website
gold-box					pokemon
html-cheat-sheet				python-machine-learning-test
inputs-radio					selectors
introToCommandLine				selectors-exercise-solution
jkapurchicago_sql-population-database.htm	selectors-quiz
jkapurchicago_sql-population-database_files	specificity
js-age-exercise					sql-population-databse
js-annoymatic					style
js-arrays					test
js-color-toggle					tic-tac-toe
js-dom-manipulation				to-do
js-for-loops					zen-garden
js-functions
(base) [Jatin@Jiamaos-MacBook-Pro://Users/Jatin/Desktop/first-app]
$ cd introToCommandLine/
(base) [Jatin@Jiamaos-MacBook-Pro://Users/Jatin/Desktop/first-app/introToCommandLine]
$ cd Animals
(base) [Jatin@Jiamaos-MacBook-Pro://Users/Jatin/Desktop/first-app/introToCommandLine/Animals]
$  man rm
(base) [Jatin@Jiamaos-MacBook-Pro://Users/Jatin/Desktop/first-app/introToCommandLine/Animals]
$ q
-bash: q: command not found
(base) [Jatin@Jiamaos-MacBook-Pro://Users/Jatin/Desktop/first-app/introToCommandLine/Animals]
$ rm -rf Animals
(base) [Jatin@Jiamaos-MacBook-Pro://Users/Jatin/Desktop/first-app/introToCommandLine/Animals]
$ ls
AwesomeAnimals	SketchyAnimals
(base) [Jatin@Jiamaos-MacBook-Pro://Users/Jatin/Desktop/first-app/introToCommandLine/Animals]
$ cd ..
(base) [Jatin@Jiamaos-MacBook-Pro://Users/Jatin/Desktop/first-app/introToCommandLine]
$ ls
Animals		cory.txt	exercise.md	hello.html	index.html	message.txt
(base) [Jatin@Jiamaos-MacBook-Pro://Users/Jatin/Desktop/first-app/introToCommandLine]
$ rm -rf Animals
(base) [Jatin@Jiamaos-MacBook-Pro://Users/Jatin/Desktop/first-app/introToCommandLine]
$ ls
cory.txt	exercise.md	hello.html	index.html	message.txt
(base) [Jatin@Jiamaos-MacBook-Pro://Users/Jatin/Desktop/first-app/introToCommandLine]
$ mkdir Animals
(base) [Jatin@Jiamaos-MacBook-Pro://Users/Jatin/Desktop/first-app/introToCommandLine]
$ mkdir Animals/AwesomeAnimals
(base) [Jatin@Jiamaos-MacBook-Pro://Users/Jatin/Desktop/first-app/introToCommandLine]
$ mkdir Animals/SketchyAnimals
(base) [Jatin@Jiamaos-MacBook-Pro://Users/Jatin/Desktop/first-app/introToCommandLine]
$ ls
Animals		cory.txt	exercise.md	hello.html	index.html	message.txt
(base) [Jatin@Jiamaos-MacBook-Pro://Users/Jatin/Desktop/first-app/introToCommandLine]
$ ls Animals
AwesomeAnimals	SketchyAnimals
(base) [Jatin@Jiamaos-MacBook-Pro://Users/Jatin/Desktop/first-app/introToCommandLine]
$ touch Animals/AwesomeAnimals/Capybara.js
(base) [Jatin@Jiamaos-MacBook-Pro://Users/Jatin/Desktop/first-app/introToCommandLine]
$ touch Animals/AwesomeAnimals/ArticFox.html
(base) [Jatin@Jiamaos-MacBook-Pro://Users/Jatin/Desktop/first-app/introToCommandLine]
$ touch Animals/AwesomeAnimals/ArticFox.html
(base) [Jatin@Jiamaos-MacBook-Pro://Users/Jatin/Desktop/first-app/introToCommandLine]
$ ls Animals
AwesomeAnimals	SketchyAnimals
(base) [Jatin@Jiamaos-MacBook-Pro://Users/Jatin/Desktop/first-app/introToCommandLine]
$ ls AwesomeAnimals
ls: AwesomeAnimals: No such file or directory
(base) [Jatin@Jiamaos-MacBook-Pro://Users/Jatin/Desktop/first-app/introToCommandLine]
$ ls Animals/AwesomeAnimals
ArticFox.html	Capybara.js
(base) [Jatin@Jiamaos-MacBook-Pro://Users/Jatin/Desktop/first-app/introToCommandLine]
$ ls Animals/SketchyAnimals/
(base) [Jatin@Jiamaos-MacBook-Pro://Users/Jatin/Desktop/first-app/introToCommandLine]
$ touch Animals/AwesomeAnimals/TreeFrog.txt
(base) [Jatin@Jiamaos-MacBook-Pro://Users/Jatin/Desktop/first-app/introToCommandLine]
$ ls Animals/AwesomeAnimals/
ArticFox.html	Capybara.js	TreeFrog.txt
(base) [Jatin@Jiamaos-MacBook-Pro://Users/Jatin/Desktop/first-app/introToCommandLine]
$ touch Animals/SketchyAnimals/BrownRecluse.html
(base) [Jatin@Jiamaos-MacBook-Pro://Users/Jatin/Desktop/first-app/introToCommandLine]
$ touch Animals/SketchyAnimals/BulletAnt.js
(base) [Jatin@Jiamaos-MacBook-Pro://Users/Jatin/Desktop/first-app/introToCommandLine]
$ ls
Animals		cory.txt	exercise.md	hello.html	index.html	message.txt
(base) [Jatin@Jiamaos-MacBook-Pro://Users/Jatin/Desktop/first-app/introToCommandLine]
$ ls Animals
AwesomeAnimals	SketchyAnimals
(base) [Jatin@Jiamaos-MacBook-Pro://Users/Jatin/Desktop/first-app/introToCommandLine]
$ ls Animals/AwesomeAnimals/
ArticFox.html	Capybara.js	TreeFrog.txt
(base) [Jatin@Jiamaos-MacBook-Pro://Users/Jatin/Desktop/first-app/introToCommandLine]
$ ls Animals/SketchyAnimals/
BrownRecluse.html	BulletAnt.js
(base) [Jatin@Jiamaos-MacBook-Pro://Users/Jatin/Desktop/first-app/introToCommandLine]
$ mkdir Animals/SketchyAnimals/Snake
(base) [Jatin@Jiamaos-MacBook-Pro://Users/Jatin/Desktop/first-app/introToCommandLine]
$ ls Animals/SketchyAnimals/
BrownRecluse.html	BulletAnt.js		Snake
(base) [Jatin@Jiamaos-MacBook-Pro://Users/Jatin/Desktop/first-app/introToCommandLine]
$ touch Animals/SketchyAnimals/Snake/Cobra.css
(base) [Jatin@Jiamaos-MacBook-Pro://Users/Jatin/Desktop/first-app/introToCommandLine]
$ touch Animals/SketchyAnimals/Snake/ReticulatedPython.js
(base) [Jatin@Jiamaos-MacBook-Pro://Users/Jatin/Desktop/first-app/introToCommandLine]
$ ls
Animals		cory.txt	exercise.md	hello.html	index.html	message.txt
(base) [Jatin@Jiamaos-MacBook-Pro://Users/Jatin/Desktop/first-app/introToCommandLine]
$ rm Animals/SketchyAnimals/BulletAnt.js
(base) [Jatin@Jiamaos-MacBook-Pro://Users/Jatin/Desktop/first-app/introToCommandLine]
$ ls Animals/SketchyAnimals/
BrownRecluse.html	Snake
(base) [Jatin@Jiamaos-MacBook-Pro://Users/Jatin/Desktop/first-app/introToCommandLine]
$ ls Animals/AwesomeAnimals/
ArticFox.html	Capybara.js	TreeFrog.txt
(base) [Jatin@Jiamaos-MacBook-Pro://Users/Jatin/Desktop/first-app/introToCommandLine]
$ rm -rf Animals
(base) [Jatin@Jiamaos-MacBook-Pro://Users/Jatin/Desktop/first-app/introToCommandLine]
$ ls
cory.txt	exercise.md	hello.html	index.html	message.txt
(base) [Jatin@Jiamaos-MacBook-Pro://Users/Jatin/Desktop/first-app/introToCommandLine]
$


```

```javascript

console.log("deed"); 

```