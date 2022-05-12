
[root@prdvarutility01 /root/presto/presto-server-0.272.1]# bin/launcher run
[root@prdvarutility01 presto]# java -jar presto-cli-0.272.1-executable.jar --server 10.11.116.138:8070
select b.col1,b.col2 from elasticsearch.default."es_index-2022-05-11-1" a join oracle.ora_schema.ora_table b on a.key1=cast(b.key2 as varchar);
