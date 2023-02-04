# Changing the .vim,.vimrc default file paths in linux terminal(bash)
-  In ~/.bashrc file, insert below lines

> export VIMINIT='source $MYVIMRC'  # make sure you have empty ~/.vimrc file.
>
>  export MYVIMRC='<your_folder_path>/VIM/.vim/.vimrc' 
