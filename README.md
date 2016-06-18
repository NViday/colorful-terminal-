# colorful-terminal- how to make the terminal shell more colorful
# to activate ASI coloring for terminal shell

# check this link for more details:
http://osxdaily.com/2013/02/05/improve-terminal-appearance-mac-os-x/

# nano .bash_profile 
# copy - paste the code below in .bash_profile:

export PS1="\[\033[36m\]\u\[\033[m\]@\[\033[32m\]\h:\[\033[33;1m\]\w\[\033[m\]\$ "
export CLICOLOR=1
export LSCOLORS=ExFxBxDxCxegedabagacad
alias ls='ls -GFh'

# customize in terminal preferecences 
# the ANSI colors 

# Done !
