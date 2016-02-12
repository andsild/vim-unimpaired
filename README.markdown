# unimpaired.vim

A fork without the following (breaking) keybindings for people who use single "less-than" or "greater-than" for indenting  


`nnoremap <silent> >P :call <SID>putline('[p', 'Above')<CR>>']  
nnoremap <silent> >p :call <SID>putline(']p', 'Below')<CR>>']  
nnoremap <silent> <P :call <SID>putline('[p', 'Above')<CR><']  
nnoremap <silent> <p :call <SID>putline(']p', 'Below')<CR><']  
`
