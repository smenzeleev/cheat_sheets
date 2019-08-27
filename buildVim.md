# Build Vim from sources

1. clone [github](https://github.com/vim/vim)
2. `sudo apt-get build-essential`
3. `cd vim`
	 `./configure --with-features=huge --enable-python3-interp=yes`
	 `sudo make distclean //if built before`
	 `sudo make && sudo make install`

> If something is not working:
`sudo rm which vim and repeat step 3`

> Check configuration in 
`/vim/src/auto/config.h`
