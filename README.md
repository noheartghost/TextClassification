The main aim of this project is text categorization, but it also involves many methods for NLP that can be used. 
Because the data set may have secret issues, it is not given here. So the data preprocessing operation needs to be solved by yourself. 
The following is a brief description of each file function:

1. GetContent.py: Get the data content of the json format file;
2. handle_db.py: database operation, connection, cursor, query, execute, close;
3. K-means.py: Make the data content a simple K-means clustering operation;
4. TextCluster.py: text clustering, including loading text content, loading stop words, word breakers and stemmers, TFIDF and K-means clustering;
5. TextSimilarity.py: Calculate text similarity
6. WebInterface: The WebService interface used by the training model, implemented using Web.py;
7. WebService: The WebService interface used by the training model, implemented using Flask;

Part of the code is a modification made on the existing open source code. If it involves infringement, please contact me.
The above documents have been tested to be able to run normally. If there are any problems during using, please feel free to contact me.

这个项目主要做的是文本分类，但是也涉及到很多用于NLP的方法可以使用。因为数据集可能有保密的问题，所以这里就不给出了，所以数据的预处理操作就需要自己解决了。下面简述各个文件功能：

1. GetContent.py：获取json格式文件的数据内容；
2. handle_db.py：数据库操作，连接，游标，查询，执行，关闭；
3. K-means.py：将数据内容做简单的K-means聚类操作；
4. TextCluster.py：文本聚类，包括载入文本内容，载入停用词，分词器和词干分析器，TFIDF和K-means聚类；
5. TextSimilarity.py：计算文本相似度
6. WebInterface：训练模型使用的WebService接口，使用Web.py实现；
7.  WebService：训练模型使用的WebService接口，使用flask实现；

部分代码是在已有开源代码上做的修改，如果涉及到侵权问题请联系本人处理
上述文件经过测试能够能够正常运行，如果使用过程中有任何问题，欢迎来信讨论。
