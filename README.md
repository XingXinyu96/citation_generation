# citation_generation
Download data here: https://pan.baidu.com/s/1BUz-VTxukC3t_Vs3O-dFhQ. Extraction code:1zbw

文件的每一行是一个json格式的数据，其属性如下：（Each line of the file is a json data with the following attributes） \
+ src_paper_id: 引用论文id（the id of the citing paper）
+ tgt_paper_id: 被引用论文id（the id of the cited paper）
+ src_abstract: 引用论文摘要（the abstract of the citing paper）
+ tgt_abstract: 被引用论文摘要（the abstract of the cited paper）
+ explicit_citation: 显式引文（the explicit citation）
+ text_before_explicit_citation: 显式引文前的部分文本（the text before explicit citation）
+ text_after_explicit_citation: 显式引文后的部分文本（the text after explicit citation）
+ implicit_citation_0.1: 使用\alpha=0.1的隐式引文抽取模型得到的引文文本（the citation extracted by our implicit citation extraction model with \alpha=0.1）
+ text_before_implicit_citation_0.1: implicit_citation_0.1前的部分文本（the text before implicit_citation_0.1）
+ text_before_implicit_citation_0.1: implicit_citation_0.1后的部分文本（the text after implicit_citation_0.1）
+ implicit_citation_0.9: 使用\alpha=0.9的隐式引文抽取模型得到的引文文本（the citation extracted by our implicit citation extraction model with \alpha=0.9）
+ text_before_implicit_citation_0.9: implicit_citation_0.9前的部分文本（the text before implicit_citation_0.9）
+ text_before_implicit_citation_0.9: implicit_citation_0.9后的部分文本（the text after implicit_citation_0.9）
+ human_labeled: 1或者0，1表示是人工标注的（1 or 0, 1 means the citation text is annotated by human）
+ train_or_test: train或者test，train表示用于训练，test表示用于测试（train or test, train means the data is used to train while test means the data is used to test）
