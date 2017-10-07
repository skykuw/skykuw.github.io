#Initial Setup
##Setting up the VIM editor
```
curl http://j.mp/spf13-vim3 -L -o - | sh
```
###Update the VIM Bundles
```
cd $HOME/to/spf13-vim/
git pull
vim +BundleInstall! +BundleClean +q
```

