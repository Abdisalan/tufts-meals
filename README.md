# tufts-meals:  Meal Swipe and JumboCash balances easier

Instead of trudging over to https://www.jumbocash.net, just check your 
remaining meal swipes and JumboCash balance from the command line. 

## Getting started
- Copy the script into `/usr/local/bin/` (and make sure that 
`/usr/local/bin/` is included in `$PATH`).

- The Bash script expects your Tufts ID and https://www.jumbocash.net 
password as environment variables. The simplest way to do this is to add 
the following lines to your .bashrc file: 
`export TUFTSID="XXXXXXX"` and `export TUFTSPASS="XXXXXXX"`.

## Features
- `-l` flag will open a browser tab to https://www.jumbocash.net 
with your account logged in

- `-d` flag will open a browser tab where you can make a JumboCash deposit