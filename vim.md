# Vim

### Insert

- a : 光标后插入
- o : 行后插入新行
- O : 行前插入新行
- cw : 删除从光标所在位置后到一个单词结尾的字符

### Move

- 0 : 行头
- $ : 行末
- ^ : 到本行第一个不是blank字符的位置
- g_ : 到本行最后一个不是blank字符的位置
- w : 下一个单词开头
- e : 下一个单词结尾
- W : 下一个blank开头
- E : 下一个blank结尾
- /pattern : 搜索 pattern 的字符串（如果搜索出多个匹配，可按n键到下一个）

### Funcation

- . : 重复上一个操作
- N<command> : 重复某个命令N次
- P : 粘帖
- yy : 拷贝当前行
- u : undo
- <C-r> : redo

### File

- saveas <path/to/file> : 另存为

