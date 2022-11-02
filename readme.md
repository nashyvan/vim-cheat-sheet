# Vim Cheat Sheet

https://neovim.io

VS Code extensions:  
VSCode Neovim

h - Left  
j - Down  
k - Up  
l - Right

i - Insert at cursor  
I - Insert at beginning of line  
a - Append at cursor  
A - Append at end of line

d - Delete  
dw - Delete word  
D or d$ - Delete to end of line  
w - Next word  
$ - Go to end of text on current line  
^ - Go to beginning of text on current line  
0 - Go to beginning of current line  
2w - Go two words forward  
3e - Go to end of third word ahead  
d2e - Delete two words  
dd - Delete entire line  
2dd - Delete two lines  
u - Undo last change  
U - Undo changes on entire line  
ctrl + r - Redo changes

p - Paste after cursor  
P - Paste before cursor  
r - Replace character under cursor  
cw - Change word  
c$ or C - Change to end of line  
c2w - Change two words

50G or :50 - Go to line 50  
G - Go to last line in file  
gg - Go to first line in file

/test42 - Search for "test42"  
n - Go to next search result  
N - Go to previous search result  
?test42 - Search backwards for "test42"  
ctrl + 0 - Jump to previous location (jump back)  
ctrl + i - Jump to next location (jump forward)  
% - Go to matching parentheses or brackets  
:%s/bad/good - Replace bad with good in current line  
:%s/hi/bye/g - Replace hi with bye in entire file  
:%s/x/y/gc - Replace x with y in entire file, prompt for changes
