# Toolbox CLI
This CLI is made using golang and cobra library. It contains 2 subpalettes :- info and net

1. The info subpalette is used to show the disk usage of the current directory in which the command is run.
2. The net subpallete is used to ping a given url and return a HTTP response code.

Commands :-

1. toolbox info disk-usage - Tells the disk usage of the current directory in which command is run.
2. toolbox net -u "<url-of-a-website>" - Pings the given website inside double quotes and returns its http status code. 
                                         Ex- toolbox net -u "www.google.com"
