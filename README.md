# runtime_components

Personal runtime configuration files for a new machine.

## Contents

- `.bashrc` — bash configuration: prompt, history, aliases, environment
- `.zshrc` — zsh configuration (macOS default shell), oh-my-zsh setup
- `.vimrc` — vim configuration: display, indentation, search settings
- `.gdbinit` — gdb configuration: history, pretty printing, pagination
- `.gitconfig` — git configuration: aliases, defaults
- `install.sh` — installs all of the above into `$HOME`, backing up
  anything already in place rather than overwriting it

## Usage

```
git clone git@github.com:vvasantarao/runtime-components.git
cd runtime-components
./install.sh
```

Run `./install.sh --dry-run` first to see what would change without
changing anything, or `./install.sh --no-omz` to skip installing
oh-my-zsh.
