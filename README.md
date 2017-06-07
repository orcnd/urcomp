# urcomp
ur/web compile and run shortcut for editor

### dont expect mad bash skills and perfect grammar 

this app add a command to your linux for compile and run ur/web code.
this way you can assign this command as build command for editors like geany

# how is it works

- compiles your code by using codes directory name. 
so you have to name your *.ur file same as director name

example directory listing 
urdemo/urdemo.ur
urdemo/urdemo.urs
urdemo/urdemo.urp

- checks *.exe file exists. this way we know compile end succesfully. 


- finds who uses 8080 port in ipv6 and kills it liam style.because urweb projects runs on that port in default. 


- runs compiled *.exe file in background. 
it does that in background because compiled app runs like server and never stops unless you do
this doesn't work for editors build command feature. 
because for editors perspective building never ends and you can't start new build before last one ends


# how to install
- copy urcomp file to /usr/bin directory
- set permissions like this: 
```sh
sudo chmod +x /usr/bin/urcomp
```

# how to use 
- you just need to enter your ur/web code directory and use urcomp command
- your code must name same as directory name 
- you can add this command to editors like geany as build command 
