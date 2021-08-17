# hands-on-data-analysis
第一章复习了python pandas库的基本内容以及数据导入的一些基本操作
主要包括分块读入文本文件：chunker=pd.read_csv('',chunksize=1000)；数据写入文本文件：data.to_csv('',encoding='utf-8')
pandas入门的基本操作，重建索引：data.reindex(columns='')，删除列条目 data.srop(''.axis=1)
pandas读取文本格式数据的函数：逗号为分隔符read_csv，制表符为分隔符read_table，read_excel，读取网页中的表格read_html，参数主要包括header，names，index_col，skiprows，chunksize，encoding，nrows

