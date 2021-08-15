#Random Wallpaper Switcher Made For Personal Use

feel free to redistribute and use at will

#Install
Dependancies
1. feh
2. gcc

#Compiling & Installing 
gcc main.c -o randomwall && mkdir -p ~/.config/randomwallconfig && cp randomwall ~/.config/randomwallconfig && sudo ln -s $HOME/.config/randomwallconfig/randomwall /usr/bin/randomwall
