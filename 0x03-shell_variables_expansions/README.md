 0 alias ls="rm *" - creating an alias script.
 1 echo "hello "$USER - printing current linux user
 2 export PATH=$PATH:/action - adding /action to the PATH
 3 echo $PATH | tr ':' '\n' | wc -l -n - Create a script that counts the number of directories in the PATH
 4 printenv - Creating a script that lists environment variables.
 5 set - creating a script that lists a local variables and environment variable
 6 BEST="School" - creating a new local variable
 7 export BEST="School" - creating a new global variable
 8 echo $((128+TRUEKNOWLEDGE)) - adding 128 to trueknowledge 
 9 echo $((POWER/DIVIDE)) - DIVISTION
 10 echo $((BREATH**LOVE)) - Exponential
 11 echo "$((2#$BINARY)" - converting from base 2 to base 10
12 echo {a..z}{a..z} | tr " " "\n" | grep -v "oo" - possible combinations
13 printf "%.2f\n" $NUM - printing two decimal places follow by a new line.
14 printf '%x\n' $DECIMAL - convert number from base 10 to base 16 
15 tr 'A-Za-z' 'N-ZA-Mn-za-m' - encoding and decoding text using rot13 encryption
