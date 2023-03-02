# HYF-Module-HTMLCSSGIT

# CLI-CHALLENGE

## 1-How do I create a hidden file or folder? How do I display it in the CLI?

To create a hidden file or folder, we just need to add adot at the beginning of the file name using touch command, for example:
We want to creat a hidden file named ( HiddenFlie.tex), we can use the following command in the terminal:
touch .HiddenFile.text.
And if we want to creat a hidden folder we can use the command:
mkdir .myhiddenfolder
To display hidden file we can use:
ls -a

## 2-How do I create multiple nested directories, like /c/Users/myusername/these/folders/are/just/for/fun?

For that we can use the command:
mkdir -p /c/users/myusername/...etc.

## 3-Write more than one command that will create a file that looks like the following (you are not allowed to use the newline character (\n))?

We can use many commands in order to do that

- echo first > ddd.text ; echo second >> ddd.text
- The command ( nano file.text) will opens the file in the Nano text editor, where we can manually type in the two messages.
- .Vscode .

## Here are the commands I used to create the CLI challenge text file:

dsham@Diaa MINGW64 ~
$ cd desktop

dsham@Diaa MINGW64 ~/desktop
$ mkdir hyf-html-exercises

dsham@Diaa MINGW64 ~/desktop
$ cd hyf-html-exercises/

dsham@Diaa MINGW64 ~/desktop/hyf-html-exercises
$ mkdir Week1

dsham@Diaa MINGW64 ~/desktop/hyf-html-exercises
$ cd Week1/

dsham@Diaa MINGW64 ~/desktop/hyf-html-exercises/Week1
$ toch CLI-Challenge.text
bash: toch: command not found

dsham@Diaa MINGW64 ~/desktop/hyf-html-exercises/Week1
$ touch CLI-Challenge.text

dsham@Diaa MINGW64 ~/desktop/hyf-html-exercises/Week1
$ ls
CLI-Challenge.text

dsham@Diaa MINGW64 ~/desktop/hyf-html-exercises/Week1
$ echo "1-How do I create a hidden file or folder? How do I display it in the CLI?" > CLI-Challenge.text

dsham@Diaa MINGW64 ~/desktop/hyf-html-exercises/Week1
$ cat CLI-Challenge.text
1-How do I create a hidden file or folder? How do I display it in the CLI?

dsham@Diaa MINGW64 ~/desktop/hyf-html-exercises/Week1
$ echo "To create a hidden file or folder, we just need to add adot at the beginning of the file name using touch command, for example:" >> CLI-Challenge.text

dsham@Diaa MINGW64 ~/desktop/hyf-html-exercises/Week1
$ cat CLI-Challenge.text
1-How do I create a hidden file or folder? How do I display it in the CLI?
To create a hidden file or folder, we just need to add adot at the beginning of the file name using touch command, for example:

dsham@Diaa MINGW64 ~/desktop/hyf-html-exercises/Week1
$ echo "We want to creat a hidden file named ( HiddenFlie.tex), we can use the following command in the terminal:" >> CLI-Challenge.text

dsham@Diaa MINGW64 ~/desktop/hyf-html-exercises/Week1
$ cat CLI-Challenge.text
1-How do I create a hidden file or folder? How do I display it in the CLI?
To create a hidden file or folder, we just need to add adot at the beginning of the file name using touch command, for example:
We want to creat a hidden file named ( HiddenFlie.tex), we can use the following command in the terminal:

dsham@Diaa MINGW64 ~/desktop/hyf-html-exercises/Week1
$ echo "touch .HiddenFile.text." >> CLI-Challenge.text

dsham@Diaa MINGW64 ~/desktop/hyf-html-exercises/Week1
$ cat CLI-Challenge.text
1-How do I create a hidden file or folder? How do I display it in the CLI?
To create a hidden file or folder, we just need to add adot at the beginning of the file name using touch command, for example:
We want to creat a hidden file named ( HiddenFlie.tex), we can use the following command in the terminal:
touch .HiddenFile.text.

dsham@Diaa MINGW64 ~/desktop/hyf-html-exercises/Week1
$ echo "And if we want to creat a hidden folder we can use the command:" >> CLI-Challenge.text

dsham@Diaa MINGW64 ~/desktop/hyf-html-exercises/Week1
$ cat CLI-Challenge.text
1-How do I create a hidden file or folder? How do I display it in the CLI?
To create a hidden file or folder, we just need to add adot at the beginning of the file name using touch command, for example:
We want to creat a hidden file named ( HiddenFlie.tex), we can use the following command in the terminal:
touch .HiddenFile.text.
And if we want to creat a hidden folder we can use the command:

dsham@Diaa MINGW64 ~/desktop/hyf-html-exercises/Week1
$ touch "mkdir .myhiddenfolder" >> CLI-Challenge.text

dsham@Diaa MINGW64 ~/desktop/hyf-html-exercises/Week1
$ cat CLI-Challenge.text
1-How do I create a hidden file or folder? How do I display it in the CLI?
To create a hidden file or folder, we just need to add adot at the beginning of the file name using touch command, for example:
We want to creat a hidden file named ( HiddenFlie.tex), we can use the following command in the terminal:
touch .HiddenFile.text.
And if we want to creat a hidden folder we can use the command:

dsham@Diaa MINGW64 ~/desktop/hyf-html-exercises/Week1
$ rm mkdir\ .myhiddenfolder

dsham@Diaa MINGW64 ~/desktop/hyf-html-exercises/Week1
$ cat CLI-Challenge.text
1-How do I create a hidden file or folder? How do I display it in the CLI?
To create a hidden file or folder, we just need to add adot at the beginning of the file name using touch command, for example:
We want to creat a hidden file named ( HiddenFlie.tex), we can use the following command in the terminal:
touch .HiddenFile.text.
And if we want to creat a hidden folder we can use the command:

dsham@Diaa MINGW64 ~/desktop/hyf-html-exercises/Week1
$ echo "mkdir .myhiddenfolder" >> CLI-Challenge.text

dsham@Diaa MINGW64 ~/desktop/hyf-html-exercises/Week1
$ cat CLI-Challenge.text
1-How do I create a hidden file or folder? How do I display it in the CLI?
To create a hidden file or folder, we just need to add adot at the beginning of the file name using touch command, for example:
We want to creat a hidden file named ( HiddenFlie.tex), we can use the following command in the terminal:
touch .HiddenFile.text.
And if we want to creat a hidden folder we can use the command:
mkdir .myhiddenfolder

dsham@Diaa MINGW64 ~/desktop/hyf-html-exercises/Week1
$ echo "To display hidden file we can use:" >> CLI-Challenge.text

dsham@Diaa MINGW64 ~/desktop/hyf-html-exercises/Week1
$ cat CLI-Challenge.text
1-How do I create a hidden file or folder? How do I display it in the CLI?
To create a hidden file or folder, we just need to add adot at the beginning of the file name using touch command, for example:
We want to creat a hidden file named ( HiddenFlie.tex), we can use the following command in the terminal:
touch .HiddenFile.text.
And if we want to creat a hidden folder we can use the command:
mkdir .myhiddenfolder
To display hidden file we can use:

dsham@Diaa MINGW64 ~/desktop/hyf-html-exercises/Week1
$ echo " ls -a " >> CLI-Challenge.text

dsham@Diaa MINGW64 ~/desktop/hyf-html-exercises/Week1
$ cat CLI-Challenge.text
1-How do I create a hidden file or folder? How do I display it in the CLI?
To create a hidden file or folder, we just need to add adot at the beginning of the file name using touch command, for example:
We want to creat a hidden file named ( HiddenFlie.tex), we can use the following command in the terminal:
touch .HiddenFile.text.
And if we want to creat a hidden folder we can use the command:
mkdir .myhiddenfolder
To display hidden file we can use:
ls -a

dsham@Diaa MINGW64 ~/desktop/hyf-html-exercises/Week1
$ cat CLI-Challenge.text
1-How do I create a hidden file or folder? How do I display it in the CLI?
To create a hidden file or folder, we just need to add adot at the beginning of the file name using touch command, for example:
We want to creat a hidden file named ( HiddenFlie.tex), we can use the following command in the terminal:
touch .HiddenFile.text.
And if we want to creat a hidden folder we can use the command:
mkdir .myhiddenfolder
To display hidden file we can use:
ls -a

dsham@Diaa MINGW64 ~/desktop/hyf-html-exercises/Week1
$ echo >> CLI-Challenge.text

dsham@Diaa MINGW64 ~/desktop/hyf-html-exercises/Week1
$ echo "2-How do I create multiple nested directories, like /c/Users/myusername/these/folders/are/just/for/fun?" >> CLI-Challenge.text

dsham@Diaa MINGW64 ~/desktop/hyf-html-exercises/Week1
$ cat CLI-Challenge.text
1-How do I create a hidden file or folder? How do I display it in the CLI?
To create a hidden file or folder, we just need to add adot at the beginning of the file name using touch command, for example:
We want to creat a hidden file named ( HiddenFlie.tex), we can use the following command in the terminal:
touch .HiddenFile.text.
And if we want to creat a hidden folder we can use the command:
mkdir .myhiddenfolder
To display hidden file we can use:
ls -a

2-How do I create multiple nested directories, like /c/Users/myusername/these/folders/are/just/for/fun?

dsham@Diaa MINGW64 ~/desktop/hyf-html-exercises/Week1
$ echo "For that we can use the command:" >> CLI-Challenge.text

dsham@Diaa MINGW64 ~/desktop/hyf-html-exercises/Week1
$ echo " mkdir -p /c/users/myusername/...etc." CLI-Challenge.text
mkdir -p /c/users/myusername/...etc. CLI-Challenge.text

dsham@Diaa MINGW64 ~/desktop/hyf-html-exercises/Week1
$ cat CLI-Challenge.text
1-How do I create a hidden file or folder? How do I display it in the CLI?
To create a hidden file or folder, we just need to add adot at the beginning of the file name using touch command, for example:
We want to creat a hidden file named ( HiddenFlie.tex), we can use the following command in the terminal:
touch .HiddenFile.text.
And if we want to creat a hidden folder we can use the command:
mkdir .myhiddenfolder
To display hidden file we can use:
ls -a

2-How do I create multiple nested directories, like /c/Users/myusername/these/folders/are/just/for/fun?
For that we can use the command:

dsham@Diaa MINGW64 ~/desktop/hyf-html-exercises/Week1
$ ^C

dsham@Diaa MINGW64 ~/desktop/hyf-html-exercises/Week1
$ echo " mkdir -p /c/users/myusername/...etc." CLI-Challenge.text
mkdir -p /c/users/myusername/...etc. CLI-Challenge.text

dsham@Diaa MINGW64 ~/desktop/hyf-html-exercises/Week1
$ cat CLI-Challenge.text
1-How do I create a hidden file or folder? How do I display it in the CLI?
To create a hidden file or folder, we just need to add adot at the beginning of the file name using touch command, for example:
We want to creat a hidden file named ( HiddenFlie.tex), we can use the following command in the terminal:
touch .HiddenFile.text.
And if we want to creat a hidden folder we can use the command:
mkdir .myhiddenfolder
To display hidden file we can use:
ls -a

2-How do I create multiple nested directories, like /c/Users/myusername/these/folders/are/just/for/fun?
For that we can use the command:

dsham@Diaa MINGW64 ~/desktop/hyf-html-exercises/Week1
$ echo " mkdir -p /c/users/myusername/...etc." >> CLI-Challenge.text

dsham@Diaa MINGW64 ~/desktop/hyf-html-exercises/Week1
$ cat CLI-Challenge.text
1-How do I create a hidden file or folder? How do I display it in the CLI?
To create a hidden file or folder, we just need to add adot at the beginning of the file name using touch command, for example:
We want to creat a hidden file named ( HiddenFlie.tex), we can use the following command in the terminal:
touch .HiddenFile.text.
And if we want to creat a hidden folder we can use the command:
mkdir .myhiddenfolder
To display hidden file we can use:
ls -a

2-How do I create multiple nested directories, like /c/Users/myusername/these/folders/are/just/for/fun?
For that we can use the command:
mkdir -p /c/users/myusername/...etc.

dsham@Diaa MINGW64 ~/desktop/hyf-html-exercises/Week1
$ echo >> CLI-Challenge.text

dsham@Diaa MINGW64 ~/desktop/hyf-html-exercises/Week1
$ echo "3-Write more than one command that will create a file that looks like the following (you are not allowed to use the newline character (\n)):" >> CLI-Challenge.text

dsham@Diaa MINGW64 ~/desktop/hyf-html-exercises/Week1
$ cat CLI-Challenge.text
1-How do I create a hidden file or folder? How do I display it in the CLI?
To create a hidden file or folder, we just need to add adot at the beginning of the file name using touch command, for example:
We want to creat a hidden file named ( HiddenFlie.tex), we can use the following command in the terminal:
touch .HiddenFile.text.
And if we want to creat a hidden folder we can use the command:
mkdir .myhiddenfolder
To display hidden file we can use:
ls -a

2-How do I create multiple nested directories, like /c/Users/myusername/these/folders/are/just/for/fun?
For that we can use the command:
mkdir -p /c/users/myusername/...etc.

3-Write more than one command that will create a file that looks like the following (you are not allowed to use the newline character (\n)):

dsham@Diaa MINGW64 ~/desktop/hyf-html-exercises/Week1
$ echo "We can use many commands in order to do that" >> CLI-Challenge.text

dsham@Diaa MINGW64 ~/desktop/hyf-html-exercises/Week1
$ echo " \* echo " first" > ddd.text ; echo "second" >> ddd.text" >> CLI-Challenge.text

dsham@Diaa MINGW64 ~/desktop/hyf-html-exercises/Week1
$ cat CLI-Challenge.text
1-How do I create a hidden file or folder? How do I display it in the CLI?
To create a hidden file or folder, we just need to add adot at the beginning of the file name using touch command, for example:
We want to creat a hidden file named ( HiddenFlie.tex), we can use the following command in the terminal:
touch .HiddenFile.text.
And if we want to creat a hidden folder we can use the command:
mkdir .myhiddenfolder
To display hidden file we can use:
ls -a

2-How do I create multiple nested directories, like /c/Users/myusername/these/folders/are/just/for/fun?
For that we can use the command:
mkdir -p /c/users/myusername/...etc.

3-Write more than one command that will create a file that looks like the following (you are not allowed to use the newline character (\n)):
We can use many commands in order to do that

- echo first > ddd.text ; echo second >> ddd.text

dsham@Diaa MINGW64 ~/desktop/hyf-html-exercises/Week1
$ echo " \* The command ( nano file.text) will opens the file in the Nano text editor, where we can manually type in the two messages." >> CLI-Challenge.text

dsham@Diaa MINGW64 ~/desktop/hyf-html-exercises/Week1
$ cat CLI-Challenge.text
1-How do I create a hidden file or folder? How do I display it in the CLI?
To create a hidden file or folder, we just need to add adot at the beginning of the file name using touch command, for example:
We want to creat a hidden file named ( HiddenFlie.tex), we can use the following command in the terminal:
touch .HiddenFile.text.
And if we want to creat a hidden folder we can use the command:
mkdir .myhiddenfolder
To display hidden file we can use:
ls -a

2-How do I create multiple nested directories, like /c/Users/myusername/these/folders/are/just/for/fun?
For that we can use the command:
mkdir -p /c/users/myusername/...etc.

3-Write more than one command that will create a file that looks like the following (you are not allowed to use the newline character (\n)):
We can use many commands in order to do that

- echo first > ddd.text ; echo second >> ddd.text
- The command ( nano file.text) will opens the file in the Nano text editor, where we can manually type in the two messages.

dsham@Diaa MINGW64 ~/desktop/hyf-html-exercises/Week1
$ echo " \* .Vscode . " >> CLI-Challenge.text

dsham@Diaa MINGW64 ~/desktop/hyf-html-exercises/Week1
$ echo >> CLI-Challenge.text

dsham@Diaa MINGW64 ~/desktop/hyf-html-exercises/Week1
$ cat CLI-Challenge.text
1-How do I create a hidden file or folder? How do I display it in the CLI?
To create a hidden file or folder, we just need to add adot at the beginning of the file name using touch command, for example:
We want to creat a hidden file named ( HiddenFlie.tex), we can use the following command in the terminal:
touch .HiddenFile.text.
And if we want to creat a hidden folder we can use the command:
mkdir .myhiddenfolder
To display hidden file we can use:
ls -a

2-How do I create multiple nested directories, like /c/Users/myusername/these/folders/are/just/for/fun?
For that we can use the command:
mkdir -p /c/users/myusername/...etc.

3-Write more than one command that will create a file that looks like the following (you are not allowed to use the newline character (\n)):
We can use many commands in order to do that

- echo first > ddd.text ; echo second >> ddd.text
- The command ( nano file.text) will opens the file in the Nano text editor, where we can manually type in the two messages.
- .Vscode .

dsham@Diaa MINGW64 ~/desktop/hyf-html-exercises/Week1
$ echo " Here are the commands I used to create the CLI challenge text file:" >> CLI-Challenge.text
