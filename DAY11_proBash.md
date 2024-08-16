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
- for loop    for i in {1..10}
- do
- echo $i
- done
- while [[expression]]
- do
- echo
- done

