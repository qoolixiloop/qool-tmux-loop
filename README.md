# qool-tmux-loop

## Welcome Dear Friend!  
* you are visiting the qoolixiloop tmux repository
* read on if you like to find out how you can profit from it
* enjoy!
* :sparkles:


### Why could you profit from this repository?
* because you want to work simultanueously on different projects
  * but you prefer to have your open files organized 
* because you code in several computer languages
  * but you prefer one single development environment (use vim)
* because you want to start a pairprogram session
  * but have no idea on how to do that


### How qoolixiloop intends to make his friends productive
* you will get my tmux startup script written in shell code
  * this will startup a multiwindow session in a second  
* you will get links to pair programming tools (use tmate, or wemux)
  * this will protect you from insecure solutions you may find on the internet
* you will get links to a simple less secure pairprogramming solution
  * this will give you an idea on how it works in principle, and how you can
    mess around with your own ssh server


# Download my tmux startup script
available repository folder: src/


# Instruction using tmux (and vim)
* download tmux (on Ubuntu)
  * $ sudo apt install tmux
* put my downloaded tmux startup script in a folder (/afolder) 
  * copy/paste to: ~/afolder/tmux-startup
* move to the directory afolder
  * $ cd ~/afolder/tmux-startup
* run the script with your desired session name <mySession>
  * $ . tmux-startup <mySession>
* now you can start several vim's 
  * $ vim
* to stop the tmux session go to any shell
  * $ tmux -ls
  * $ tmux kill-session -t <mySession>


# Instruction using tmate (and tmux and vim)
* download tmate (on Ubuntu)
  * $ sudo apt install tmate


## Links for secure pairprograming solutions
* [tmate](https://tmate.io/)
* [wemux](https://github.com/zolrath/wemux)

## Links for simple less secure solutions
* [simple but less secure ssh solution tutorial](https://www.hamvocke.com/blog/remote-pair-programming-with-tmux/)
* [simple but less secure ssh solution](https://gist.github.com/shrayasr/9778db8aabac59eba6b5)


# Screenshots of tmux
* ![image of tmux with some python code](pictures/tmux_showing_py)

* ![image of tmux with filemanager mc](pictures/tmux_showing_mc)


------------------------
qoolixiloop 7. Nov. 2018
 




























