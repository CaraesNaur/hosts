hosts
=====

This is my hosts file that I run on all my machines (expect my Win7 laptop,
see below).  It maps 131,570 hostnames to 0.0.0.0.  Several years ago I
merged three hosts blacklists, and have been adding to it since.

If you insist on using Facebook, remove the section at the end.

**IMPORTANT: DO NOT REPLACE YOUR HOSTS FILE WITH THIS FILE.**

Add this at the end of your existing hosts file.  Under Windows, it is at
C:\[WINDIR]\system32\drivers\etc\hosts and it will need to be opened as
Administrator.

Note: In my experience, Windows 7 (and probably Vista and 8) cannot handle
a hosts file this big (3.6MB): it will cause a cascade of silent errors which
result in the desktop not loading, forcing you to go back to a previous
restore point.  My research indicates that the maximum Win7 problem-free hosts
file size is somewhere between 384kB and 768kB.  Pre-Vista Windows does not
have this problem.
