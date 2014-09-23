linux-learning
==============
REF:-https://www.cs.oberlin.edu/~kuperman/help/vim/markers.html

help

The most import thing to learn about in vim is...

:help
and

:help command
TAB - cycles through possible command completions
CTRL-d - lists possible command completions
For example, try

:help tags (then CTRL-d and TAB)
Do help i_ CTRL-d for insert commands, v_ for visual, etc.

Also, when in the help pages, CTRL-] jumps to subjects between |bars| and CTRL-T jumps back (and, of course, :q to quit).

markers

Use markers to set places you want to quickly get back to, or to specify a block of text you want to copy or cut.
 mk      - mark current position (can use a-z)
 'k      - move to mark k
 d'k     - delete from current position to mark k
 'a-z    - same file
 'A-Z    - beteween files

word & line completion

Typing is a pain! In insert mode, try:

ctrl-n, ctrl-p    - next/previous word completion 
                    (similar word in current file)

ctrl-x ctrl-l (ctrl-n/p)    - line completion

:set dictionary=/usr/share/dict/words
ctrl-x ctrl-k     - dictionary completion
also

ctrl-w      - erases word (insert mode...
ctrl-u      - erases line  ...or on command line)



word & line completion

Typing is a pain! In insert mode, try:

ctrl-n, ctrl-p    - next/previous word completion 
                    (similar word in current file)

ctrl-x ctrl-l (ctrl-n/p)    - line completion

:set dictionary=/usr/share/dict/words
ctrl-x ctrl-k     - dictionary completion
also

ctrl-w      - erases word (insert mode...
ctrl-u      - erases line  ...or on command line)
