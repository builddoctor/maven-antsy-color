Output Highlighting for Maven 
==============================

I miss Ant's AnsiColorLogger.  So I found [a blog post](http://blog.blindgaenger.net/colorize_maven_output.html) and [another blog post](http://johannes.jakeapp.com/blog/category/fun-with-linux/200901/maven-colorized) and decided to share the results on GitHub

To Colorize Maven Output
------------------------

* put the file in a handy directory (like _~/scripts_)
* add a link to it in your .bashrc (or other shell's initialization file):

    [[ -s "${HOME}/scripts/mvn" ]] && source "${HOME}/scripts/mvn"
    . ~/.bashrc # to re-read your bash configuration

