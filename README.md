Based on the stackoverflow snippet by Mykola Golubyev:
http://stackoverflow.com/questions/741814/move-entire-line-up-and-down-in-vim/741819#741819

Example keymapping you can put in your ~/.vimrc (although the plugin is already configured to map this may not want to force that on people though)

```
noremap <silent> <c-j> :call <SID>swap_up()<CR>
noremap <silent> <c-k> :call <SID>swap_down()<CR>
```
