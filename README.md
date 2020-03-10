# Config
configuration for useful software

# tmux
高版本tmux>=2.9
启动命令：tmux -f .tmux.conf
参考链接:
* [配置说明](https://gist.github.com/hexiaoting/61763a42120b9115b7819002fe4baabd)
* [amosbird config](https://github.com/amosbird/tmuxconfig/blob/master/.tmux.conf)

# vim
要使用YouCompleteMe插件，则需要 Vim 7.4.1578+.
1. 先install vim with python3
    * ./configure --prefix=/opt/vimpython36 --with-features=huge --enable-cscope --enable-multibyte --enable-python3interp --with-python3-config-dir={python3-config --configdir}
2. 通过vimrc会自动下载YouCompleteMe插件，但是要执行install.py的话需要先安装好cmake等
3. 设置环境变量:
    * PATH=...
    * VIMRUNTIME=/root/opt/vimpython36/share/vim/vim82
    * VIM=/root/.vim
