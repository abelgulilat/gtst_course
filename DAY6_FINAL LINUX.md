## Script Installation
- git clone [Link from git hub]
- for python installation  (pip install -r requirements.txt)
- for go installation (go install [github.com/ module name])
- for ruby installation (gem install [module name])
## Error Handle
- [sudo apt edit-resource]
## Help About Command
- man (manual) [command]--- full information about command
- [command -h,-help,--help--- some command have option
## Linux processes and Service
- ps --- only running on the shell
- ps -A ---- All running shell
- ps -u [username] ----view users process
pid process ID
- kill [option] (pid)   -- option -19(stop), -18(resume),-9(immediately stop) -----etc ----   
#### HTOP
- f3(search),f9(kill),f10(quit)
## Foreground/background
- we use "&" operator to run at background
- "fg" to get background process to foreground
## Null Device
- command  1> /dev/null
- command  2> /dev/null
## Symbolic Linking
- ln -s "directory" [shortcut name]
## alias
alias shortcut_name ="command"
- "sh" -- [~/.shrc]
- "zsh" --[ ~/.zshrc]
- "Fish" -- [~/.config/fish/config.fish]
 you have to save their as a comment
 
 ####  tmux
- [ /.tmux.conf]
- ctrl+A ,o  horizontal
- Ctrl+A,e   vertical
- ctrl+A,x    exit
- ctrl+A,c    tab
- ctrl+A   ,   rename
- ctrl+A+number (arrow)

 