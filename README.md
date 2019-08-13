# mysqlbackup
mysql 备份与恢复


RDS for MySQL 物理备份文件恢复到自建数据库

https://help.aliyun.com/knowledge_detail/41817.html?spm=a2c4g.11186623.4.1.7ecb7feaKEKMaa

常见问题解决

InnoDB: Error: log file ./ib_logfile0 is of different size 0


解决办法：移除原有ib_logfile

#mv ib_logfile0 ib_logfile0.bak

#mv ib_logfile1 ib_logfile1.bak
