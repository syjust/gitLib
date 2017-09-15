```
       _ _   _     _ _     
  __ _(_) |_| |   (_) |__  
 / _` | | __| |   | | '_ \ 
| (_| | | |_| |___| | |_) |
 \__, |_|\__|_____|_|_.__/ 
 |___/                     

```

# Projet Initialisation

 ```
 git clone <repo> ~/.gitLib
 echo  "export PATH=$PATH:~/.gitLib/bin" >> ~/.bashrc
 [ -e ~/.gitconfig ] && mv ~/.gitconfig{,.bak}
 ln -s ~/.gitLib/gitconfig ~/.gitconfig
 git config --global user.name <firstname lastname / organisation>
 git config --global user.email <email@email.com>
 ```

Then verify differences between your old gitconfig (if you want reimport it) and the new one.
