# 一、基本操作
## 增
i insert 光标前插入  
I        在行的最前插入  
a append 光标后插入  
A        在行的最后插入  
o open in line 行的下方插入  
O              行的上方插入  
## 删
diw delete inner word 删除一个单词不进入编辑模式  
daw delete around word 删除单词及周围的空格  
x 删除光标处的字母
## 查
fs 查找并跳转到当前行第一个s，按;到下一个  
F 往回查找  
/ 查找单词并高亮显示  
？往回查找单词并高亮显示  
## 改
ciw change inner word 删除一个单词并进入编辑模式    
ct) change total () 删除括号内容并进入编辑模式  
ci" change inner "" 删除双引号内容并。。。  
ctrl+w insert模式下删除引号内容  
## 移动光标
hjkl 命令模式下分别向左下上右移动  
14G 移动到14行    
0 移动到行首  
$ 移动到行尾  
g 移动到开头   
GG 移动到结尾  
## 复制
yy：复制当前行  
nyy：n表示大于1的数字，复制n行  
yw：从光标处复制至一个单子/单词的末尾，包括空格  
ye：从光标处复制至一个单子/单词的末尾，不包括空格  
y$：从当前光标复制到行末  
y0：从当前光标位置（不包括光标位置）复制之行首  
y3l：从光标位置（包括光标位置）向右复制3个字符  
y5G：将当前行（包括当前行）至第5行（不包括它）复制  
y3B：从当前光标位置（不包括光标位置）反向复制3个单词  
## 剪切  
dd：剪切当前行  
ndd：n表示大于1的数字，剪切n行  
dw：从光标处剪切至一个单子/单词的末尾，包括空格  
de：从光标处剪切至一个单子/单词的末尾，不包括空格  
d$：从当前光标剪切到行末  
d0：从当前光标位置（不包括光标位置）剪切至行首  
d3l：从光标位置（包括光标位置）向右剪切3个字符  
d5G：将当前行（包括当前行）至第5行（不包括它）剪切  
d3B：从当前光标位置（不包括光标位置）反向剪切3个单词ss      
dH：剪切从当前行至所显示屏幕顶行的全部行    
dM：剪切从当前行至命令M所指定行的全部行    
dL：剪切从当前行至所显示屏幕底的全部行
## 粘贴
p paste
# 二、进阶操作
撤销 u  
恢复撤销 ctrl+r  
向上翻页 Ctrl+u upward  
向下翻页 Ctrl+f forward  
