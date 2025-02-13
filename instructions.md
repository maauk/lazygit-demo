# Lazygit Demo

Demo for using lazygit <https://github.com/jesseduffield/lazygit>

mac user: `brew install lazygit`
linux users: see repo README.md for distro specific instructions
windows: same as above

Attribution: demo basically copied from lazygit devs youtube video: <https://www.youtube.com/watch?v=CPLdltN7wgE>

## 1. Stage files

1. Files tab
2. `space` files
3. `esc` back to files tab
4. `c` to commit

## 2. Stage lines

1. Files tab
2. `enter` a file
3. `space` lines
4. `esc`, `esc` back to files tab
5. `c` to commit

## 3. Cherry pick

1. `Tab` to local branches
2. `Enter` a branch
3. `Shift-c` to stage a commit for copying
4. `Esc` `Tab` to commit panel
5. `Shift-v` to add the copied commits to branch

Can also be done with in reverse.

## 4. Discard

`d` and `shift-D` in files panel

## 5. Interactive rebase

Press `e` on a commit in the commits panel. Do the p,s,f,d etc. stuff to commits above. press `m` for rebase options inc. continue rebase
use `^j` and `^k` to move commits up and down to reorder commits (can also be done outside of active rebase, will quick rebase only reorder)

## 6. Amend and fixups

stage something files panel. Press `Shift-A` in commits panel on a commit to append to it. Alternatively, press `f` to create a fixup a commit for the commit.
Fixup commits can be autosquashed with the commit they are fixing up with `Shift-S`.

Bonus feature. Find the likely commit you want to fixup or ammend with `^f` :)

## 7. Open a PR

press `o` in branch section.

## 8 revert a commit

press `t` in commits panel

## 9 partial stash

Stage files or lines, press `s` in files panel and select stash staged.
