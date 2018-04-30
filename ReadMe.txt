#使用说明
该包只是化简了对solr的配置

#附带功能
1）log日志组建
2）官方smartcn中文分词器配置
	创建field时指定type为text_cn即可
3）IKAnalyze中文分词器配置
	创建field时指定type为text_ik即可

#使用步骤（前提搭好了集群或者单机模式,并且有实例core）
1）将classes文件夹放在webapps/WEB-INF/下即可
	IK分词器的词库如果有自己的词库请覆盖，词库格式：一行一个词汇
2）将lib_extra文件夹下的jar包都放在webapps/WEB-INF/lib下
3）将conf文件夹覆盖到每个实例core的conf文件夹


