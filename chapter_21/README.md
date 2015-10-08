1) What is your shell set to?

when i run `$ env` it returns

    rvm_bin_path=/Users/Apple/.rvm/bin
    TERM_PROGRAM=iTerm.app
    GEM_HOME=/Users/Apple/.rvm/gems/ruby-2.2.3
    TERM=xterm-256color
    SHELL=/bin/bash
    
So, shell is set to /bin/bash

2) What directory are you in (don't use pwd this time)?

again `env` shows that i'm in

    rvm_bin_path=/Users/Apple/.rvm/bin

3) What is your home directory set to?

Home directory is set to /Users/Apple

4) Can you set your environment to have DEBUG set to true?

Need help on this... ask in meeting tonite

 - How to change my PATH on your computer:

I would open my bash profile with `~/.bash_profile` in text edit.
Then i would add the line `export PATH="$HOME/.new_directory_here/bin:$PATH"`
at the end of the file and save it. The new directory will then exist in your file path.
Then i run `source ~/.bash_profile` to force the new bash profile values to execute.
An `echo $PATH` will reveal the new values for you in your terminal.
