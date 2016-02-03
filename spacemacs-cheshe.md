## Useful Spacemacs commands

- `SPC q q` - quit
- `SPC w /` - split window vertically
- `SPC w` - - split window horizontally
- `SPC 1`   - switch to window 1
- `SPC 2`   - switch to window 2
- `SPC w c` - delete current window
- `SPC TAB` - switch to previous buffer
- `SPC b b` - switch buffers
- `SPC f f` - find a file
- `SPC f s` - save a file (:w also works)
- `SPC p p` - open project
- `SPC p h` - find a file in current project
- `SPC b d` - kill current buffer
- `SPC b M` - move buffer to another window
- `SPC v`   - enter expand-region mode
- 
- `SPC b b` - Helm mini; lists buffers & recent files
  - `CTRL SPC` - Mark Items
  - `CTRL z` - Actions
- `SPC b B` - ibuffer

- `SPC f f` - open files
  - `CTRL h` - up a folder
  - `CTRL l` - open a folder
  - `CTRL j` - up
  - `CTRL k` - down

- `SPC p f` - opens root of project
- `SPC p p` - opens projects

- `SPC /` - searches through project
- `SPC s s` - search in a file
- `SPC s l` - find all function definitons in a file

- `SPC v` - expand region
- `SPC V` - contract region
- `s (` - put parens around a region

- `SPC s e` - multiple cursors
  - `n` - jump
  - `N` - jump

- `SPC h d` - help describe
- `SPC h d f` - help describe functions
- `SPC h d v` - help describe variables
- `SPC f e h` - help

- `ALT /` - snippet completion

- `SPC t s` - syntax checking
- `SPC e` - syntax checking options

- `SPC a r` - ranger
- `SPC a d` - deer

## unimpaired

- `[e` - Move line up
- `]e` - Move line down
- `[SPACE` - Insert space above
- `]SPACE` - Insert space below
- `[p` - Paste above current line
- `]p` - Paste below current line

## evil-mc

- `grm` - make-all-cursors
- `gru` - undo-all-cursors
- `grs` - pause-cursors
- `grr` - resume-cursors
- `grf` - make-and-goto-first-cursor
- `grl` - make-and-goto-last-cursor
- `grh` - make-cursor-here
- `M-n` - make-and-goto-next-cursor
- `grN` - skip-and-goto-next-cursor
- `M-p` - make-and-goto-prev-cursor
- `grP` - skip-and-goto-prev-cursor
- `C-n` - make-and-goto-next-match
- `grn` - skip-and-goto-next-match
- `C-t` - skip-and-goto-next-match
- `C-p` - make-and-goto-prev-match
- `grp` - skip-and-goto-prev-match


## Useful Vim key bindings

### movement

- `0` - beginning of line
- `^` - beginning of non-whitespace
- `$` - end of line
- `9j` - move down 9 lines
- `w` - move forward by word
- `b` - move backward by word
- `gg` - first line
- `G` - last line
- `C-u` - up half page
- `C-d` - down half page
- `f/` - move forward to first "/" character
- `t/` - move forward right before the first "/" character
- `;` - repeat that command again
- `H` - head of the screen
- `M` - middle of the screen
- `L` - last of the screen
- `}` - move forward by paragraph or block
- `{` - move backwards by paragraph or block
- `*` - search for word under the cursor
- `n` - search again forward
- `N` - search again backwards
- `#` - search backwards for word under cursor
- `/` - search forward
- `?` - search backward
- `%` - find matching brace, paren, etc
- `ma` - mark a line in a file with marker "a"
- ``a` - after moving around, go back to the exact position of marker "a"
- `'a` - after moving around, go back to line of marker "a"
- `:marks` - view all the marks
- `''` - go to the last place you were

### editing

- `x` - delete char under cursor
- `X` - delete char before cursor
- `A` - add to end of line
- `I` - insert at the beginning of the line
- `dd` - delete line
- `D` - delete from cursor to end of line
- `di'` - delete text inside single quotes
- `yy` - copy line
- `Y` - copy from cursor to end of line
- `cc` - change line
- `C` - change from cursor to end of line
- `cit` - change text inside html tag
- `ci'` - change text inside single quotes
- `ci{` - change text inside curly brackets.
- `ci...` - etc
- `p` - paste after cursor
- `P` - paste before cursor
- `o` - add line below
- `O` - add line above
- `.` = repeat last comment
- `r` - replace character
- `R` - replace. (overwrite) (good for columns of text)
- `J` - join line (cursor can be anywhere on line)

### visual mode

- `v` - visual char mode
- `V` - visual line mode
- `C-v` - block visual mode