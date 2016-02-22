# Hed: The Hexadecimal Editor #

<b>Hed</b> is a free hexadecimal editor
for POSIX systems
designed to efficiently handle
infinitely large files
in conjunction with operations like inserting
in the middle of the file.

Hed is maintained by Petr Baudis
<<a href='mailto:pasky@ucw.cz'>pasky@ucw.cz</a>>
and distributed as free software under GPLv2.

## Features ##

  * Very fast on very large files (keeps only necessary portion of the file in memory)
  * Fast inserting anywhere in the file
  * Fast saving of intermediate changes
  * <tt>vim</tt>-like controls (and exmode)
  * Powerful <em>expressions</em> concept for flexible searching and transformation operations on the file or a selected region

## Development ##

Hed is developed using <a href='http://git.or.cz/'>Git</a>
development version control system. You can get details on
how to grab the latest version at
<a href='http://repo.or.cz/w/hed.git'>its gitweb page</a>
(use `git clone URL`).
Click on the <tt>snapshot</tt> link to get a tarball with the
snapshost of the current version.

You are encouraged to send patches to
<a href='mailto:pasky@ucw.cz'>the maintainer</a>.
Also, you can freely push to the <tt>mob</tt> branch of
the repository - see
<a href='http://repo.or.cz/mob.html'>details</a>.

## Download ##

The latest release is <a href='http://hed.googlecode.com/files/hed-0.4.tar.gz'>hed-0.4</a> (2009-02-03).

You can also
<a href='http://repo.or.cz/w/hed.git/?a=snapshot;h=HEAD'>grab a tarball</a> of the latest development
version. See above for the details.

Hed is currently beta-quality software. It should be well
usable but not very well tested - and only you can help with that!
Please do not use it on critical data without backups, though.