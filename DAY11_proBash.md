### Regular Expressions
- Filter validation by regex. it is pattern used to filter text, Tab, Space, Symbol .
- filter links, filter bad words.
- used on linux tools called grep, awk, sed.
#### Metacharacters
- . ^ $ * + ? {} [] ()  |  \
- {\\w \W  \s \S \d \D
#### Meta Character on BASH
- if [ "Hp" =~ [0-9] ]     - $pattern = " [a-z].*@gmail.*com$"
- then                           - read -p "Enter your Email " email
- echo "Number"          -if [ $email =~ $pattern] 
- else                            - then
- echo "letter"             - echo "Valid Email"
- fi                               - else
-                                    - echo "invalid email"
-                                  - fi
#### elif
#### loop on BASH
- **for loop    for i in {1..10}
- do
- echo $i
- done
- **while [[expression]]
- do
- echo
- done
- **until [expression]
#### Function 
- function function_name(){
- return $(( $1 + $2 ))
- }
- function_name $one $two
- echo $?
#### BASH and Linux
- we can run Linux command on bash.
- I can write code on single line.  for i in {1..3}; do echo $i; done
- echo *   
- you can access file in current directory on bash. `echo *`
- you can print on `echo $PWD`
- you can write for loop on terminal.  for i in *; do echo $i; done
- you can write for loop on terminal rename. for i in *; do echo mv $i new_$i ; done

 
