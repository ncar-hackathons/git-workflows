<img align="right" height=40 src="../images/git-logo.png">

# What is Git? 

First and foremost, Git is a Version Control System (VCS).  That is, it is something that
tracks _changes_ in files (or directory structures) incrementally.  The files (and directories)
that get tracked are contained in a _repository_, and each change that you _commit_ to the 
repository gets saved, allowing you to go back to a previous state of the files in your
repository.  This is the basic definition of a VCS.

Git, specifically, is a _distributed_ VCS, as opposed to a _centralized_ VCS.  What the
difference?  A centralized VCS is typified by a _single_, _central_ _server_ that hosts your
repository.  With a centralized VCS, changes made by one person on their personal computer
(for example) must be _pushed_ to the central server in order to be saved in the repository.
Hence, there is always one, and only one, _true_ repository, which is sitting on the server.

Distributed VCSes, on the other hand, don't have a central server.  That means, as in the
case of Git, that changes made by one person on their personal computer get saved to _their
own copy_ of the "true" repository.  ...But then which repository is the "true" repository?
If there are multiple copies of the same repository floating around the interwebs, which one
is the one that can be _trusted_?  Well...  They _all_ can be trusted, because each copy
of the repository is a self-consistent, stand-alone repository in its own right.  And you can
always bring multiple copies of the same repository together by _merging_ them.

We'll talk a little about what is Git and how to use it in the following examples.  I encourage
you to walk through these steps on your own.
