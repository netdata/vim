Installation:

    git clone git@github.com:netdata/vim.git ~/.vim

Create symlinks:

    ln -s ~/.vim/vimrc ~/.vimrc

Switch to the `~/.vim` directory, and fetch submodules:

    cd ~/.vim
    git submodule init
    git submodule update

Now build the vim-command-t switch to dir `~/.vim/bundle/vim-command-t/ruby/`

	cd ~/.vim/bundle/vim-command-t/ruby/
	ruby extconf.rb
	make
