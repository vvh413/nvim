# nvim config

vim-plug
```sh
sh -c 'curl -fLo "${XDG_DATA_HOME:-$HOME/.local/share}"/nvim/site/autoload/plug.vim --create-dirs \
       https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim'
```

CoC
```sh
cd .local/share/nvim/plugged/coc.nvim/
yarn install
yarn build
```

CoC Ext
```vim
:CocInstall coc-json coc-markdownlint coc-rust-analyzer
```

