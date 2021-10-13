可能是要在行里面一部分输入这种内容，例如：
```python
my_list = ["one","two","three","four","five","six"]
```
可以考虑先直接输入
```python
val my_list = ["one,two,three,four,five,six"]
```
里面的第一对引号一般自动补齐了。
最后直接一遍再执行```:s/,/","/g```即可，是否逗号来分割可以自己看着选

