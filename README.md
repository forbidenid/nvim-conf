WELCOME TO THE NVIM CONFIG

first i use nv chad you will need to install it 
this is a linux instalation
so fire up the terminal
lets code!!
I USE Arch BTW
lets install neovim
```
sudo pacman -Syu neovim
```
set up alias
```
alias vim=nvim
```
Load the alias at startup
```
echo "alias vim=nvim" >> .zshrc
```
Back up your configs if you have any
```
mv ~/.config/nvim ~/.config/nvim/backup
```
Delete local neovim cache
```
rm -rf ~/.local/share/nvim
```
clone NVCHAD then remember to type n
```
 git clone https://github.com/NvChad/NvChad ~/.config/nvim --depth 1 && nvim
```
