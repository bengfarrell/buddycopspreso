HTML5 Buddy Cops
================

This is a Polymer + Atom-Shell Presentation powered by Polymer + Atom-Shell

Do normal bower/npm installs, then:

Once finished with that, run:

gulp downloadatomshell

(this assumes you have gulp on your machine - if not npm install -g gulp)


Next you are ready to run the presentation deck. cd to the project root, target the atom-shell executable and pass it a few args:

./binaries/Atom.app/Contents/MacOS/Atom app html:app/preso.html

or to launch with the dev tools open:

./binaries/Atom.app/Contents/MacOS/Atom app html:app/preso.html debug:true


---------------------------------------------------------------------------

Alternately, I'm making/testing out a command line tool. You can:

Do normal bower/npm installs, then:


npm install -g poshery

Then to download atom, type:

posh installatom


Then once installed, you can type:

posh run preso.html


or to launch with the dev tools open:

posh run preso.html -d

