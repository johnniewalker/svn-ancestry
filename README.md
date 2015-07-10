[TOC]

# svn-ancestry
Trace the ancestry of a versioned file in a Subversion® repository and return a list of filenames that represent its various incarnations, across svn-copies, since its oldest ancestor was first svn-added.

# Business Case

As a software developer, I have a large project whose code is stored in a [Subversion®](https://subversion.apache.org/) repository. Over the years I have refactored the code many times and teased it into a modular architecture made up of various components. One component has matured to the extent that it really ought to be a standalone project in itself. 

I want that component's code to reside in a new, standalone, Subversion® repository. But, I also want to retain the version history of all the files in that component so that I can read the log and commit messages that explain how and why it came to be in its current form.

# Research Search Missions

I have tried to find a tool that helps this process. In order to understand my thought process (and therefore those of the potential users of the tool that I am making), here are the queries for some search  that I have done whilst trying to solve this problem:

* static analyse some php that you want to hive off into a different project 
* static analysis some php that you want to hive off into a different project
* clone subversion repository for just one component 
* cut sub project out of subversion repo
* svn dump only specific files
* svn log
* extracting component pattern 
* extracting component
* detect leaf php scripts
* php dependency management
* how does php dependency fit in 
* how does composer it in
* svn filter out all but one directory
* cutting project out of repository svndumpfilter 
* --preserve-revprops 
* "--preserve-revprops" git 
* You'll need to make sure that any directories that the new dump stream expects to exist actually do exist in the target repository before trying to load the stream into that repository. 
* svn filter create the parent directories 
* svn log command
* dos sort lines in fiel unique 
* svn get complete history of a directory
* svn get complete history of a directory copies from other parts of the repo
* svn get complete history of a directory copies from other parts of the repo 
* svn copy
* svn copy and rename
* seeing history of svn copy and renames
* svn log 
* svn log machine readable changed paths 
* svn historian
* svn trace the history of a file copyfrom-path
* svn trace the history of a file "copyfrom-path"
* xml processor svn trace thehistory of a file "copyfrom-path"
* xml processor svn trace the history of a file "copy from-path"
* linked list php
* doubly linked list 
* svn migration tools 
* svn migration tools to git 
* xml stream processing
* php xml stream processing 
* php xml stream processing zend framework
* framework for writing php cli applications 
* streaming to php cli application
* streaming to php cli application symphony
* svn incarnation
* use of subversion in project names
* svn history
* svn trace 
* svn ancestry 
* ancestry
* Subversion 
 





