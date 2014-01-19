Paper for probable publication in Add Con Japan Control System Conference 2014.

Packages required to compile this paper:

sudo apt-get install texlive-base


Trick:
vimrc modification

map <buffer> <F2> :<Esc>:w<CR>:!clear<CR>:!pdflatex % <CR>:!evince paper.pdf 2>/dev/null &<CR>: <Ins> <CR>
