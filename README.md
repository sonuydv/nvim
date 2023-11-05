# nvim
Configuration file for nvim

## Note :
###### configuration file will work for both vim and neovim/nvim but some plugins may not be available for vim , so neovim/nvim is recommended
## Steps : -----

### Step 1 : Install either vim or neovim/nvim;

### Step 2 : Install the plugin manage ; 
###### source : https://github.com/junegunn/vim-plug

```sh
curl -fLo ~/.vim/autoload/plug.vim --create-dirs \
    https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
```
### Step 3 : Now either clone or copy the content of init.vim file from the repo and paste it in inside the following file
~/.config/nvim/init.vim

### Step 4 : Now either re-source or reload the config file in nvim and run the following command in vim command mode
```
:PlugInstall
```

### You are good to go now
