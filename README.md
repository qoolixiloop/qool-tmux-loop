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
* because you want to start a pairprogramming session
  * but have no idea on how to do that
* found anything?
* :dizzy:


### How qoolixiloop intends to make his friends productive
* you will get my tmux startup script written in shell code
  * this will startup a multiwindow session in a second 
  * you can and will of course adapt it to your individual needs.     
    But be aware that the script is sent as a one liner to your shell. <br/> 
    Therefore even small syntax errors like e.g. lagging spaces or even <br/>
    trying to comment the code will not work out.  
* you will get links to pair programming tools (use tmate, or wemux)
  * this will protect you from insecure solutions you may find on the internet
* you will get links to a simple less secure pairprogramming solution
  * this will give you an idea on how it works in principle,     
    and how you can mess around with your own ssh server.
* like christmas!
* :sparkling_heart:


# Download my tmux startup script
> available in my repository folder: **src/tmux-startup**


# Instructions for using tmux (and vim)
* download tmux (on Ubuntu)   
    $ sudo apt install tmux   
* put my downloaded tmux startup script into a folder in your user home      
  directory (~/) or equivalently (/home/your_user_name/)   
    * copy/paste to: ~/myfolder/tmux-startup   
* move to the directory myfolder   
    $ cd ~/myfolder/tmux-startup   
* run the script with your desired session name mySession   
  (dont forget the dot)   
    $ . tmux-startup mySession   
    $ . ~/myfolder/tmux-startup mySession   # in case you don't like the cd step
* now you can start additional teminal applications   
  (you will already have some vim's)    
    $ vim    # for another vim  
    $ mc     # for another  mc (if you don't have it: $ sudo apt install mc)   
    $ htop   # if you need htop (if you don't have it: $ sudo apt install htop)   
* to stop the tmux session go to any shell   
    $ tmux -ls   
    $ tmux kill-session -t mySession   

## Other useful tmux commands
* if you are in a multipane window and want your pane to fill the whole screen  
  you can toogle with the following key strokes   
    * Ctrl-B z  
* in case you accidentally hit Ctrl-z and it shows your shell promt   
  you can goback to the foreground by entering   
    $ fg  

# Instruction using tmate (and tmux and vim)
* download tmate (on Ubuntu)   
      $ sudo apt install tmate   


## Links for secure pairprograming solutions
> * [tmate](https://tmate.io/)
> * [wemux](https://github.com/zolrath/wemux)
>
## Links for simple less secure solutions
> * [simple but less secure ssh solution tutorial](https://www.hamvocke.com/blog/remote-pair-programming-with-tmux/)
> * [simple but less secure ssh solution](https://gist.github.com/shrayasr/9778db8aabac59eba6b5)


# Screenshots of tmux
> * ![image of tmux with some python code](pictures/tmux_showing_py.png)
>
> * ![image of tmux with filemanager mc](pictures/tmux_showing_mc.png)


------------------------
qoolixiloop, 7. Nov. 2018
