.vim
====
.vim

deyunanhai sanの.vim/をまるっとforkしてきたもの。
deyunanhai sanはPerl使わないので、自分用にPerlの設定を追加したものを自分のrepositoryで管理。(あとカラースキームも自分の好みにした)

NeoBundleに関しては、新しくcloneするときは、下記のようにbundle/を掘って、必要なものを一旦cloneし、
```
mkdir -p ~/.vim/bundle
cd ~/.vim/bundle
git clone git@github.com:Shougo/vimproc.git ~/.vim/bundle/neobundle.vim
git clone git@github.com:Shougo/neobundle.vim.git ~/.vim/bundle/neobundle.vim
```
最後、vim開いて、:NeoBundleInstall でインストール。
