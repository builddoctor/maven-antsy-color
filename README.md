Output Highlighting for Maven 
==============================

I miss Ant's AnsiColorLogger.  So I found [a blog
post](http://blog.blindgaenger.net/colorize_maven_output.html) and
[another blog
post](http://johannes.jakeapp.com/blog/category/fun-with-linux/200901/maven-colorized),
spent some time messing around, and decided to share the results on GitHub.  It 
works by wrapping your wrapping your Maven command and then inserting ANSI colour
codes in the output.

To Colorize Maven Output
------------------------

* put the file in a handy directory (like _~/scripts_)
* add a link
to it in your .bashrc (or other shell's initialization file)
* example below:

```bash
mkdir -p ${HOME}/scripts # make a place for the script to live  
cp mvn ${HOME}/scripts echo "[[ -s \"${HOME}/scripts/mvn\" ]] &&
source \"${HOME}/scripts/mvn\"" >> ${HOME}/bashrc # add to RC file
. ${HOME}/bashrc # to re-read your bash configuration
  ```

How do you spell 'colour'?
--------------------------
With a _u_ in it.  Until you realise that you're outnumbered by people who 
use the (Georgian-era spelling)[http://en.wikipedia.org/wiki/American_and_British_English_spelling_differences#-our.2C_-or]
