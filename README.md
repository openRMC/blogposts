openRMC Blogposts
==================

This is an area where openRMC blogposts are created, edited and made ready before being posted to the openRMC.org site.

All documents for the project are written in [Asciidoc](http://www.methods.co.nz/asciidoc). This staging area brings in other openRMC written documents via a git submodule in the resources directory. If you clone this project for the first time given that the resources directory has git submodules in it, for example resources/webrtc-docs, then in a fresh clone you will see the directory webrtc-docs, but none of the subdirectories. You must run two commands: 

   $ git submodule init 

to initialise your local configuration file, and 

   $ git submodule update 

to fetch all the data from that project and check out the files.

Each new directory in this root directory of the repository is a blogpost which in most cases will make reference to text created in the orignial documents of the project and will thus have a link to the resources directory.

Once a blogpost has been created it is built and submitted as a blogpost to the openRMC site with the tool [blogpost](http://srackham.wordpress.com/blogpost-readme/).
