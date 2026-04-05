# 文档摘要生成器

就是我自己练手的一个小脚本。  
能读 txt 文件，然后调用通义千问的 API 自动写个摘要出来。

## 现在已经能做的
- 读指定 txt 文件
- 如果文件不存在会报错，不会崩
- 有日志，能看运行过程
- 调用通义千问 API，返回真的摘要

## 怎么用
```bash
python summary_generator.py sample.txt
