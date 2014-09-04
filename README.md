Vim Conf
=======

The configure repo of vim and vimrc is based the plugin bundle adn git .

It is cross-platform , include Windows and *nix , you can deploy it quickly .

It is mainly for C,C++,Java and web language . 

---
###Depend
In *nix and Windows     
    
    depend: 
        astyle 
        cscope 
        ctags 
        libiconv

###Install and Update

**Download**

    git clone http://github.com/turing1988/vimconf.git

**Deploy**

In *nix  , First run it, Enter in the directory vimcomf/ , run 
 
    ./vimupdate.sh 
    
In Windows , First run it , open the `CMD.EXE` , run

    ./vimupate.bat

After it , your configure of vim will be backuped in $HOME.vim.bak and $HOME.vimrc.bak .

After vim cmd `BundleUpdate` runs over , Input `:qa!` to exit vim

Then new conf of vim is comming !


**Update**

In *nix  , Enter in the directory vimcomf/ , run 
 
    ./vimupdate.sh 
    
In Windows , open the `CMD.EXE` , run

    ./vimupate.bat

--- 
#### Plugin 
'gmarik/vundle'

'scrooloose/nerdtree'

'blak3mill3r/c.vim'

'plasticboy/vim-markdown'

'mattn/emmet-vim'

'xptemplate'

'cecutil'

'genutils'

'code_complete'

'Tagbar'

'vimwiki'

'winmanager'

'OmniCppComplete'

'bufexplorer.zip'

'adah1972/fencview'

'surround.vim'

'taglist.vim'

'vimcn/vimwiki.vim.cnx'

'jkeylu/vimdoc_cn'

'Valloric/ListToggle'

'scrooloose/syntastic'

'turing1988/Conque-Shell'

'Auto-Pairs'

###More

  *  [My Vimwiki](http://mturing.com/wiki/wikihtml/Vim%E9%85%8D%E7%BD%AE%E5%A4%87%E6%B3%A8.html)

  *  [My Blog](http://mturing.com)
