## BASH Script
- Bourne Again Shell 
- Script is a file that contain shell commands in a simple and clear algorithm.
	- uses to bash - Script Development, *Automatic Task, Simplifying your linux ability,                                       developing hacking script.*
- Bash file can have ".sh" extension.
- file need executable permissions.
- you can you any text editor(vim, nano, VScode).
- **tmux** can support you.
- shebang(hashbang)  -- #! /bin/bash      ----->this indicate script should execute using bash shell. using this you can run from command line.
### Variables
- name="GTST" ----- echo $name ------echo ${name}
- BASH variables String by default.
- **set** malaf tufi  ---- echo $1 $2.        ------> it is string type.
- **System variable** $BASH $USER $PWD $HOME $PATH $MAIL.
- **Array** - var=("malf" "tufi" "leo")  ------ echo ${var[0]}---------echo ${var[@]}
				- echo ${#var[@]}---- var[4]="abel"-----unset var[4] 
## Bash Input
1. Read Function  ---- read accept input while script running 
			- read -p "Enter" var  ---- read -sp "password" var------read -a  var----->
			- echo "enter ${var[0]}"
2. Arguments    --this help accept input before script start
				-- echo "hello $1"
				-echo "hello $2" 
#### Comment 
- #  ---for single line
## Sleep
			 -for good waiting on our script   ----------1s
### Operation
- $((a+b))
- let a+=1
- -gt, -lt, -eq, -le, -ge, -ne  (>, <, =, <=, >=, !=)
### if else condition
- if[2 -gt 1]
- then
- echo "Good1"
- else
- echo "Not well"
- fi
