This is a quine program, which means that when it runs, it prints its own 
source code, character for character. The important thing is that it does 
this *logically*, that is, it doesn't just read its source code from disk, 
rather, it does it on its own. There are much shorter ways to accomplish 
this, but it's instructive to write your own quine. 

If you do: 

gcc quine.c > output 
diff quine.c output  

the diff is empty. 
