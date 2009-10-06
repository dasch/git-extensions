
Git Extensions
==============

A library of handy Git commands that makes working with your repositories
easier.


`git-ignore`
------------

Adds file patterns to your `.gitignore` file.

Usage:
    $ git ignore "*.o" tags "*.sqlite3"
    $ cat .gitignore
    *.o
    tags
    *.sqlite3


`git-export`
------------

Exports a Git repository.


`git-pending`
-------------

Display a list of commits waiting to be pushed to a remote
branch.


`git-track`
-----------

Track a remote branch.

Usage:
    $ git status
    # On branch foo
    $ git remote add example git@example.com/example.git
    $ git track example bar
    Tracking example/bar


`git-ls-ignored`
----------------

List files that are currently being ignored.


Contributors
------------

 * Daniel Schierbeck
 * Abhishek Mukherjee


License
-------
Copyright (C) 2009 Daniel Schierbeck <daniel.schierbeck@gmail.com>

This program is free software; you can redistribute it and/or
modify it under the terms of the GNU General Public License
as published by the Free Software Foundation; either version 2
of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program; if not, write to the Free Software
Foundation, Inc., 51 Franklin Street, Fifth Floor, Boston, MA  02110-1301, USA.
