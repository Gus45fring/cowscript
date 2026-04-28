# cowscript
a compilation of 100 phrases for fortune | cowsay


Short tutorial for people who don't know how to do it:
1. download cowsay and fortune
2. download the `cow` file from this repo
3. move said file to the fortune folder with sudo (normally on `/usr/share/fortune`)
4. cd into the fortune folder
5. run `sudo strfile cow`
6. done! if you want to see your cow, write `fortune cow | cowsay`.
7. you can also run `fortune cow | cowsay | lolcat` if you have lolcat installed to get a rainbow cow
## if you want to run it at the opening of the terminal
after doing the steps above, put on your .bashrc  (usually in your $HOME) `fortune cow | cowsay`.

someone had to do it.
