# Official Repositoy of BengalBoot
# How to use on Other Arch Based OS:- 
Edit your pacman.conf using your favourite text editor. I am have used gedit and my command was "sudo gedit /etc/pacman.conf".

Add this to you pacma.conf file:-
                                      
                                      [bengali_repo]
                                      SigLevel = Optional TrustAll
                                      Server = https://bcw52.github.io/bengali_repo/$arch
