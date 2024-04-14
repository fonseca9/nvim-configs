# neovim
just nvim configs, based on nvchad with a few bind modifications. 

nvim 0.9+ on ubuntu:

1) remove the current nvim
  
2)  sudo apt-get install ninja-build gettext cmake unzip curl build-essential

3)  git clone https://github.com/neovim/neovim

4)  cd neovim && make CMAKE_BUILD_TYPE=RelWithDebInfo

5)  git checkout stable

6)  cd build && cpack -G DEB && sudo dpkg -i nvim-linux64.deb
