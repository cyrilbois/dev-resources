---
title: Bash

key_links:
  homepage: https://www.gnu.org/software/bash/
  wikipedia: "https://en.wikipedia.org/wiki/Bash_%28Unix_shell%29"
  repo_nwo: gitGNU/gnu_bash
  devhints: https://devhints.io/bash
  learn_x: https://learnxinyminutes.com/docs/bash/
  
      
documentation:
  - title: Bash reference manual (PDF)
    url: https://www.gnu.org/software/bash/manual/bash.pdf
    description: Official guide on the GNU site
    
  - title: Bash reference manual (PDF)
    url: https://devdocs.io/bash/
    description: On DevDocs
 
  - title: Bash man page
    url: https://linux.die.net/man/1/bash
    description: On Linux Die 
 
tutorials:
  - title: Bash Guide
    url: http://mywiki.wooledge.org/BashGuide
    description: |
      Covers an intro and links to topics.
      
      It also links to a more modern but possibly incomplete rewrite [here](https://github.com/lhunath/bash.academy).
      
  - title: The Bash Guide
    url: https://guide.bash.academy/
    description: |
       > A quality-driven guide through the shell's many features.
  - title: Learn Shell
    url: https://www.learnshell.org/
    description: Includes basic and advanced sections.
    
  - title: Linux Shell Scripting Tutorial
    url: https://bash.cyberciti.biz/guide/Main_Page
---



### About


Bash is the shell (command-line interpreter) for the GNU operating system. The name is an acronym for the "Bourne-Again SHell" and is a pun on Stephen Bourne's name. [source](https://devdocs.io/bash/html_node/what-is-bash_003f#What-is-Bash_003f).

Bash is not the operating system itself - an operating system can be built on Bash, which in turn is built on C. 

It is commonly used on Linux operating systems. It was the default shell for macOS, until Catalina made [ZSH](../ZSH/README.md) the default. Bash is what your system boots and logs in with. It is what you configure and run other programs on top of. You can also do programming/scripting in bash, as commands in the console or bash scripts (typically `.sh`)

In the terminal, you execute Bash interactively or to execute other languages. Bash is great for high-level tasks like running a few scripts or applications in a sequence, using output from one as input of another. 

Bash can be used to write short or long scripts. If you look around system, you will see a lot of Bash files. You will also see some C (.c or .h) files. And also some executables which have no extension and look garbled when you read them - these are compiled binaries which might be written in C or another language and are used in Bash. For example, `view $(which ls)` will show the contents of the `ls` executable.

Wikipedia definition:

> GNU Bash or simply Bash is a Unix shell and command language written by Brian Fox for the GNU Project as a free software replacement for the Bourne shell. First released in 1989, it has been used widely as the default login shell for most Linux distributions and Apple's macOS Mojave and earlier versions. [source](https://en.wikipedia.org/wiki/Bash_(Unix_shell))

Bash can be powerful and elegant to do fancy stuff in a one-line command or handling text or CSV succinctly without writing a Node or Python etc. I use it every day and the more I know about it and use it, the more I can do and the faster I get at it.

But, Bash has some things which are not so intuitive - variables are global by default, a script will keep executing commands even if one of them has an error code, there are no data types as everything is text. So think carefully before choosing to write a Bash script to solve your problem - perhaps write it in another language that can make development, debugging and maintenance a lot easier.

