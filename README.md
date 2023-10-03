#NerdFont
https://www.nerdfonts.com/font-downloads

Font: MesoloLG

## Installing a Nerd Font on Ubuntu involves a few steps. Below is a guide on how to do it.

Use `font-manager`
install it by using `sudo apt-get install font-manager`

 **Set the Font in Your Terminal**: Open the preferences/settings of your terminal and set the newly installed font as the default.

#install Neovim

#install NVChad
```bash
git clone https://github.com/NvChad/NvChad ~./.config/nvim -depth 1
```

we need version 0.8 and above

nvim --version


# Remove old version
sudo apt remove neovim

# Add new PPA (if not added)
sudo add-apt-repository ppa:neovim-ppa/unstable

# Update package list
sudo apt update

# Install new version
sudo apt install neovim


in nvChad change theme by using `SPACE t h` command

use :TSInstall <language> to add new langauges
TSInstallInfo to find available languages

`ctrl+n` for navigation tree

in navigation tree - press `a` to start creating a new file
press `c` to copy a file and `r` to paste a file


to find a file `SPACE f f`

to search in files that are open `SPACE f b`

to bring up cheetsheet `SPACE c h`

press `SPACE` and wait to get suggestions

open new panes with `:vsp` vertical split or `:sp` for split. navigate using j,k,l,i keys

use 'space h'  or 'space v' to open terminal window


In Neovim (and Vim), you start in Normal Mode by default. To enter Edit Mode, you have several options, each placing you in a slightly different editing context:

### Insert Mode

1. **Insert Before Cursor (`i`)**: Press `i` to start inserting text before the cursor.
2. **Insert at the Beginning of the Line (`I`)**: Press `I` to start inserting text at the beginning of the line.
3. **Insert After Cursor (`a`)**: Press `a` to start inserting text after the cursor.
4. **Insert at the End of the Line (`A`)**: Press `A` to start inserting text at the end of the line.
5. **Insert on a New Line Below (`o`)**: Press `o` to open a new line below the current line and start inserting.
6. **Insert on a New Line Above (`O`)**: Press `O` to open a new line above the current line and start inserting.

### Replace Mode

1. **Replace Single Character (`r`)**: Press `r` followed by any character to replace the character under the cursor.
2. **Replace Mode (`R`)**: Press `R` to enter Replace Mode. This will overwrite characters in the line as you type.

### Visual Mode

1. **Visual Mode (`v`)**: Press `v` to start selecting text character by character.
2. **Visual Line Mode (`V`)**: Press `V` to select entire lines.
3. **Visual Block Mode (`Ctrl-v`)**: Press `Ctrl-v` to select text in a rectangular block.

Once you're in Visual Mode, you can move the cursor to select text. After that, you can press `c` to change the selected text, effectively entering Edit Mode for the selected block of text.

### Command-Line Mode

1. **Command-Line Mode (`:`)**: Press `:` to enter Command-Line Mode, where you can enter commands like `:w` to save, `:q` to quit, etc.

### Exiting Edit Mode

To exit any of the Edit Modes and go back to Normal Mode, press `Esc`.

Each of these modes serves a specific purpose and allows you to interact with the text in a particular way. As you become more familiar with Neovim, you'll find yourself switching between these modes seamlessly.
