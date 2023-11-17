<h1 align="center">
  [OUTDATED] My dotfiles! They are pretty cool. I used <a href="https://github.com/CodelyTV/dotly">🌚 dotly</a> to help me set them up, it's a fantastic project.
</h1>

## Restore your Dotfiles

- Install git
- Clone your dotfiles repository `git clone [your repository of dotfiles] $HOME/.dotfiles`
- Go to your dotfiles folder `cd $HOME/dev/env/.dotfiles`
- Install git submodules `git submodule update --init --recursive`
- Install your dotfiles `DOTFILES_PATH="$HOME/.dotfiles" DOTLY_PATH="$DOTFILES_PATH/modules/dotly" "$DOTLY_PATH/bin/dot" self install`
- Restart your terminal
- Import your packages `dot package import`
