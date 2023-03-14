##Shell, init files, variables and expansions##

###SCRIPT DEFINITIONS###

* `alias ls="rm *"` - Create a script that creates an alias.

* `echo "hello $USER"` - Create a script that prints `hello` user

* `PATH=$PATH:/action` - Add `/action` to the `PATH`. `/action` should be the last directory the shell looks into when looking for a program

* `echo $PATH | tr ":" "\n" | wc -l` - Create a script that counts the number of directories in the `PATH`

* `printenv` - Create a script that lists environment variables

* `set` - Create a script that lists all local variables and environment variables, and functions.

* `BEST=School` - Create a script that creates a new local variable.

* `export BEST=School` - Create a script that creates a new global variable.

* `echo $(($TRUEKNOWLEDGE+128))` - Write a script that prints the result of the addition of 128 with the value stored in the environment variable `TRUEKNOWLEDGE`, followed by a new line.

* `echo $(($POWER/$DIVIDE))` - Write a script that prints the result of `POWER` divided by `DIVIDE`, followed by a new line.

* `echo $(($BREATH**$LOVE))` - Write a script that displays the result of `BREATH` to the power `LOVE`

* `echo $((2#$BINARY))` - Write a script that converts a number from base 2 to base 10.

* `echo {a..z}{a..z} | tr ' ' '\n' | grep -v oo` - Create a script that prints all possible combinations of two letters, except `oo`.

* `printf "%.2f" $NUM | sort` - Write a script that prints a number with two decimal places, followed by a new line.

The number will be stored in the environment variable `NUM`.

* `printf "%x\n" $DECIMAL` - Write a script that converts a number from base 10 to base 16.

* `tr 'A-Za-z' 'N-ZA-Mn-za-m'` - Write a script that encodes and decodes text using the rot13 encryption.

* `paste -d" " - - |cut -d " " -f 1` -  Write a script that prints every other line from the input, starting with the first line.

* `echo $(printf %o $(($((5#$(echo $WATER | tr 'water' '01234'))) + $((5#$(echo $STIR | tr 'stir.' '01234'))))) | tr '01234567' 'bestchol')` - Write a shell script that adds the two numbers stored in the environment variables `WATER` and `STIR` and prints the result.



##**THANK YOU**##
