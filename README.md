### Setup Steps After installed Nvim and deps
- `nvim` and `:PlugInstall`
- if you want to use telescope-fzf-native
   - go to `~/.local/share/nvim/site/pack/packer/start/telescope-fzf-native.nvim
`
   - run `cmake -S. -Bbuild -DCMAKE_BUILD_TYPE=Release && cmake --build build --config Release && cmake --install build --prefix build`
