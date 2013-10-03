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

### 2. Package Managers

Because who wants to ``./configure && make && sudo make install`` all the time?


Lots of them, most have a GUI version (e.g. Synaptic for aptitude).

--

### 3. grep

Search through files.

``grep "search" file.txt``

Can also add lots of other options like case insensitivity.

``grep -i "search" file.txt``

--

### 3. grep

Uses regular expressions.

``grep "s.*h" file.txt``

Can be used recursively.

``grep -R "s.*h" dir/``

--

### 4. The humble pipe.

The pipe operator ``|`` (as well as redirects ``>``, ``>>``, etc.) are some very
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
