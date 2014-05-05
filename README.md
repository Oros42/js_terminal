js_terminal
===========

A fake javascript terminal


Demo
====

http://oros42.github.io/js_terminal/


Key
===

```Tab``` : autocomplete  
```Up``` : back in history  
```Down``` : forward in history  
```Alt```+```Backspace``` : remove word  
```Ctrl```+```d``` : exit  
```Ctrl```+```v``` : past  


Commands
========

-```help```  
-```ls [dir]```  
-```cd <dir>[/dir]```  
-```cat <file>```  
-```pwd```  
-```mkdir <dir>[/dir]```  
-```man``` (Not finish, only ```man cat``` works)  
-```clear```  
-```exit```  
-```echo "<text>"[ >[>] <file>]```  


Write programs
==============

You can write your own programs in javascript !  
Example 1 :  
```
cd /usr/bin
echo "function(a){return 'Hello world!';};">hello
hello
```

Example 2 :  
```
cd /usr/bin
echo "function(a){return 'Hello '+a;};">say_hello
say_hello Bob
```

Example 3 :  
```
cd /usr/bin
echo "function(a){return 'Hello '+a;};">say_hello
say_hello Bob
```

```fs.pwd``` : return path in array  
```fs.cat(<file name>)``` : return contants of file   
```fs.cd(<path>)``` : return true if change directory succeeds. Path can be a string or an array  
```fs.ls()``` : return an array of directory contants  
```fs.mkdir(<directory name>)``` : make a new directory  
```fs.write(<file name>, <file contants>)``` : write file  
```prs['<program name>']()``` : run a program   


Only files in ```/usr/bin``` are interpreted as programs.  
  
/!\ When you close the terminal, nothing is saved !  
