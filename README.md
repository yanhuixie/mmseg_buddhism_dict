# mmseg_buddhism_dict
基于coreseek4.1自带mmseg词典整合搜狗佛教细胞词典的新词典。  
文件说明：  

- buddhism.scel 搜狗细胞词库佛教用语
- buddhism.txt 使用scel2mmseg.py转换buddhism.scel的结果
- merge-mmseg-dict.py 源自 [https://gist.github.com/mawenbao/6280461b04309fcb8bae](https://gist.github.com/mawenbao/6280461b04309fcb8bae)
- scel2mmseg.py 源自 [https://github.com/archerhu/scel2mmseg](https://github.com/archerhu/scel2mmseg)
- uni.lib merge-mmseg-dict.py→mmseg -u之后的最终结果，可直接替代coreseek4.1自带的uni.lib文件

参考资料：[伍哥原创之用搜狗细胞词库制作mmseg词典](http://my.oschina.net/alexwu/blog/71150 "伍哥原创之用搜狗细胞词库制作mmseg词典")
