# Toolbox CLI
This CLI is made using golang and cobra library. It contains 2 subpalettes :- info and net

1. The info subpalette is used to show the disk usage of the current directory in which the command is run.
2. The net subpallete is used to ping a given url and return a HTTP response code.

## Commands :-

1. toolbox info disk-usage - Tells the disk usage of the current directory in which command is run.
2. toolbox net -u "<url-of-a-website>" - Pings the given website inside double quotes and returns its http status code. 
                                         Ex- toolbox net -u "www.google.com"

## Settin up the CLI App on Local Machine :-
1. Download and install the go package in your local machine and set up the path.
2. Move to the directory of toolbox using cd command and then run go install.
3. Then run the above given command on windows or "$GOPATH/<above-given-command>" on linux or mac.
