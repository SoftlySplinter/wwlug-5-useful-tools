title: 5 Useful Tools
author:
  name: "Alexander Brown"
  twitter: "@SoftlySplinter"
  url: "http://blog.alexanderdbrown.com"
output: basic.html
controls: true

--

# 5 Useful Tools
## 5 GNU/Linux tools that will make your life easy.

--

### 1. sudo

Ever needed to run something in a terminal as an administrator? ``sudo`` is the
tool for you!

For longer sessions you can use ``sudo -s`` for an administrator session until
you exit.

Also ``ctrl+d`` (normally written ``^d``) is a quick way to log out from the 
current shell.

--

### 4. The humble pipe.

The pipe operator ``|`` (as well as redirects ``>``, ``>>``) etc. are some very
useful when you want to take the output from one command into another.

One of my most used ones:

``ps -fe | grep Java``

Which lists all processes which have "Java" somewhere in their name.

--

### 5. man

Stuck with a command?

Forgotten which flag to use.

Just ``man`` that command.

Manual pages can be a bit tricky to read, but do give very good details and 
usually have examples too.
