# medicalKG
基于neo4j图数据库的医疗领域问答程序。将医疗领域专业词汇爬取本地，以RDF模型存至图数据库中，完成知识图谱的构建。根据对问句中关键词的匹配，对来问句做语义分类，根据分类关键词使用自动机Ahocorasick做模式串匹配，对得到的匹配结果在图谱中做相应的cql查询，最终拼接为完整回答。
