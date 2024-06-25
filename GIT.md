<!-- Git is not Github.  -->

Git is the version control software, and Github is a git repository hosting service which offers all the source code management provided in git. Github is where you upload your git repository.

<!-- Centralized Version Controlling -->

The systems such as CVS, Subversion, and Perforce have a single server that contains all the versioned files, and a number of clients that check out files from that central place.

<!-- Distributed Version Controlling -->

In a DVCS (such as Git), clients don’t just check out the latest snapshot of the files; rather, they fully mirror the repository,including its full history. Thus, if any server dies, and these systems were collaborating via that server, any of the client repositories can be copied back up to the server to restore it. Every clone is really a full backup of all the data.
