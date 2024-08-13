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
1. Arguments    