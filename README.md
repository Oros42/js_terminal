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


Commands
========

-```help```  
-```ls [dir]```  
-```cd <dir>[/dir]```  
-```cat <file>```  
-```pwd```  
-```mkdir <dir>[/dir]```  
-```man```  
-```clear```  
-```exit```  
-```echo "<text>"[ >[>] <file>]```  


Write programs
==============

You can write your own programs !  
```
cd /usr/bin
echo "function(a){return 'Hello world!'};">hello
hello
```

Only files in ```/usr/bin``` are interpreted as programs.  
