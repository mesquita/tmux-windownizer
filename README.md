# tmux-windownizer

Easy tmux window creation using fuzzy finder in specific dirs. Inspired by Primeagen's [tmux-sessionizer](https://github.com/ThePrimeagen/.dotfiles/blob/master/bin/.local/scripts/tmux-sessionizer), but instead of a new session it creates a new window (if already not created).

Make sure fzf is installed.

Change in the script the list of directories where to look for your projects.

## Usage
What I usually do is create an alias like this in my config:
`alias tw='abc/.dotfiles/tmux-windownizer'`, use the `tw` to open the fuzzy finder and search for the folder I want.
