# Sanekits

It was long ago, and the defaults for `bash` were making me crazy.  Like all intrepid shell warriors, I started modifying my `~/.bashrc` to make things better: more efficient, more uniform, more sane.

Weeks turned into years, and years turned into decades.  The thing I had started to make me sane was making me crazy with complexity and layers and coupling.   There's so much the shell **can** do to help us, and yet it's so easy to get it all tangled up that it can make one crazy.

So what's needed here is the same thing needed in any software system: design principles, idioms, and practices.  Build components. Manage the dependencies of components.  Test them.  Deploy them automatically.  That's what `sanekits` are about.

A sanekit can be self-installed or installed with `shpm` -- the "shellkit package manager".  These are not mutually exclusive approaches -- `shpm` recognizes kits that were installed manually just fine, and manually installing kits works fine too.  Kits know their dependencies and behave themselves.

And each kit has some coherent theme, with shell aids and scripts tuned to some useful purpose.
