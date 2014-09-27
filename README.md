# Xmonad configuration files

## How to:
* First you should install Xmonad and Xmobar. I sugest following the steps stated in [this](http://www.haskell.org/haskellwiki/Xmonad/Config_archive/John_Goerzen%27s_Configuration) website as a starting point
* user@earth$ cd ~
* Create a .xmonad folder if it doesn't exist already
* user@earth$ git clone https://github.com/bokas/xmonad-configs
* user@earth$ ln -s ~/xmonad-configs/xmonad.hs ~/.xmonad/xmonad.hs
* user@earth$ ln -s ~/xmonad-configs/xmobarrc ~/.xmobarrc
* user@earth$ ln -s ~/xmonad-configs/xessionrc ~/.xessionrc
* Mod-Shift-q to restart your X server
* I changed my Mod key to be the Windows key, if you dont't want this behaviour just remove line 17 from xmonad.hs ou changed it to another combination (check [here](http://hackage.haskell.org/package/X11-1.6.1.2/docs/Graphics-X11-Types.html) for key codes)

## References:
* (http://www.haskell.org/haskellwiki/Xmonad/Config_archive/John_Goerzen%27s_Configuration)[http://www.haskell.org/haskellwiki/Xmonad/Config_archive/John_Goerzen%27s_Configuration]
* (http://projects.haskell.org/xmobar/)[http://projects.haskell.org/xmobar/]
