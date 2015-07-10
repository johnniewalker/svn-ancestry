# svn-ancestry
Trace the ancestry of a versioned file in a Subversion® repository and return a list of filenames that represent its various incarnations, across svn-copies, since its oldest ancestor was first svn-added.

# Business Case

As a software developer, I have a large project whose code is stored in a [Subversion®](https://subversion.apache.org/) repository. Over the years I have refactored the code many times and teased it into a modular architecture made up of various components. One component has matured to the extent that it really ought to be a standalone project in itself. 

I want that component's code to reside in a new, standalone, Subversion® repository. But, I also want to retain the version history of all the files in that component so that I can read the log and commit messages that explain how and why it came to be in its current form.




