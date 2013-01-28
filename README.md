Based on the stackoverflow snippet by Mykola Golubyev:
http://stackoverflow.com/questions/741814/move-entire-line-up-and-down-in-vim/741819#741819

Example keymapping you can put in your ~/.vimrc


noremap <silent> <c-s-up> :call <SID>swap_up()<CR>                                                                                                                                              noremap <silent> <c-s-down> :call <SID>swap_down()<CR>

