全局配置
路径: ~/.gitconfig
直接编辑文件或git config --global

repository配置
路径: <当前仓库>/.git/config
直接编辑文件或git config --local
在仓库内设置GitHub的username和mail之后再push

执行的hook也在.git/hooks路径下，直接把他们全部删掉就不执行了
