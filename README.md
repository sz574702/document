# document
对 Excel 和 wrod 的基础 操作 

须知:

  1. doc  文档为二进制文档体积小可以直接使用 记事本打开

  2. docx 文档为xml文件的压缩包形式。

  3. Excel 表格以此类推依然是这样的形式。


model01.Main1

    具体实现生成一个 A + B = C 的模式的文档只是简单的拼接上

    A 相当于 WORD1 B 相当于 WORD3 

    关系文件 为 CONTENT 在REGEX 处插入 也就是一开始的地方

mode02.Main2

    实现了对文档的一些替换并且输出到原文档不会另行新建文件格式为 docx 格式
  
model03.Main3
  
      实现了对文档的格式的修改主要是查询标题（匹配正则以数字开头以:结尾中间为任意字符），并且将其加粗。设置字体为arial，字号为5号字，因为只有int类型所以经过我的仔细查看跟五号字跟size=11大小相同。所以我就将其设置为size=11；
