**Arch Based**
  ```
  sudo pacman -S python-pillow python-wand python3
  ```  
**Gentoo**
  ```
  sudo emerge --ask dev-python/wand dev-python/pillow dev-lang/python
  ```
**Install**
  ```
  git clone https://github.com/JustCoww/videoimagecreator ~/.local/bin/vic && chmod +x ~/.local/bin/vic/vic.py && sudo ln -s ~/local/bin/vic/vic.py /usr/bin/vic
  ```
**Uninstall**
  ```
  rm -rf ~/.local/bin/vic && sudo rm /usr/bin/vic
  ```
