# PaperReading
To learn a technology in architecture level, one of the best way is to read the research paper. Here is a paper reading list for big data area (data lake, data warehouse and database).

## Big data Computing/Storage/Orchestration
### Hadoop

- 2003 Google File System [Ghemawat, Sanjay, Howard Gobioff, and Shun-Tak Leung. "The Google file system." Proceedings of the nineteenth ACM symposium on Operating systems principles. 2003.](https://static.googleusercontent.com/media/research.google.com/en//archive/gfs-sosp2003.pdf)
- 2004 MapReduce [Dean, Jeffrey, and Sanjay Ghemawat. "MapReduce: simplified data processing on large clusters." Communications of the ACM 51.1 (2008): 107-113.](https://static.googleusercontent.com/media/research.google.com/en//archive/mapreduce-osdi04.pdf)
- 2010 HDFS [Shvachko, Konstantin, et al. "The hadoop distributed file system." 2010 IEEE 26th symposium on mass storage systems and technologies (MSST). Ieee, 2010.](https://storageconference.us/2010/Papers/MSST/Shvachko.pdf)
- 2013 YARN [Vavilapalli, Vinod Kumar, et al. "Apache hadoop yarn: Yet another resource negotiator." Proceedings of the 4th annual Symposium on Cloud Computing. 2013.](http://www1.ece.neu.edu/~ningfang/SimPaper/a5-vavilapalli.pdf)


### Spark
- 2012 RDD [Zaharia, Matei, et al. "Resilient distributed datasets: A {Fault-Tolerant} abstraction for {In-Memory} cluster computing." 9th USENIX Symposium on Networked Systems Design and Implementation (NSDI 12). 2012.](https://www.usenix.org/system/files/conference/nsdi12/nsdi12-final138.pdf)
- 2015 Spark SQL [Armbrust, Michael, et al. "Spark sql: Relational data processing in spark." Proceedings of the 2015 ACM SIGMOD international conference on management of data. 2015.](https://dl.acm.org/doi/pdf/10.1145/2723372.2742797)
- 2016 Spark [Zaharia, Matei, et al. "Apache spark: a unified engine for big data processing." Communications of the ACM 59.11 (2016): 56-65.](https://people.eecs.berkeley.edu/~alig/papers/spark-cacm.pdf)
- 2016 Mlib [Meng, Xiangrui, et al. "Mllib: Machine learning in apache spark." The journal of machine learning research 17.1 (2016): 1235-1241.](https://www.jmlr.org/papers/volume17/15-237/15-237.pdf)
- 2018 Structured streaming [Armbrust, Michael, et al. "Structured streaming: A declarative api for real-time applications in apache spark." Proceedings of the 2018 International Conference on Management of Data. 2018.](https://dl.acm.org/doi/abs/10.1145/3183713.3190664)

### Presto
- 2019 Presto [Sethi, Raghav, et al. "Presto: SQL on everything." 2019 IEEE 35th International Conference on Data Engineering (ICDE). IEEE, 2019.](https://trino.io/Presto_SQL_on_Everything.pdf)

### Kubernets
- 2015 Borg [Verma, Abhishek, et al. "Large-scale cluster management at Google with Borg." Proceedings of the tenth european conference on computer systems. 2015.](https://pages.cs.wisc.edu/~shivaram/cs744-readings/borg.pdf)
- 2016 Borg, Omega, and Kubernetes [Burns, Brendan, et al. "Borg, omega, and kubernetes." Communications of the ACM 59.5 (2016): 50-57.](https://storage.googleapis.com/pub-tools-public-publication-data/pdf/44843.pdf)


### Open Data Lake format
- 2020 Delta lake [Armbrust, Michael, et al. "Delta lake: high-performance ACID table storage over cloud object stores." Proceedings of the VLDB Endowment 13.12 (2020): 3411-3424.](https://www.vldb.org/pvldb/vol13/p3411-armbrust.pdf)


## Data Warehouse
### Snowflake
- 2016 Snowflake [Dageville, Benoit, et al. "The snowflake elastic data warehouse." Proceedings of the 2016 International Conference on Management of Data. 2016.](https://event.cwi.nl/lsde/papers/p215-dageville-snowflake.pdf)


### Bigquery
- 2010 Dremel [Melnik, Sergey, et al. "Dremel: interactive analysis of web-scale datasets." Proceedings of the VLDB Endowment 3.1-2 (2010): 330-339.](https://storage.googleapis.com/pub-tools-public-publication-data/pdf/36632.pdf)


### Redshift
- 2022 Redshift [Armenatzoglou, Nikos, et al. "Amazon Redshift re-invented." Proceedings of the 2022 International Conference on Management of Data. 2022.](https://assets.amazon.science/4b/37/223ac61e450898244a31bed53734/amazon-redshift-re-invented.pdf)

### azure synapse
- 2020 POLARIS [Aguilar-Saborit, Josep, et al. "POLARIS: the distributed SQL engine in azure synapse." Proceedings of the VLDB Endowment 13.12 (2020): 3204-3216.](http://www.vldb.org/pvldb/vol13/p3204-saborit.pdf)

## Database
### Aurora
- 2017 Aurora [Verbitski, Alexandre, et al. "Amazon aurora: Design considerations for high throughput cloud-native relational databases." Proceedings of the 2017 ACM International Conference on Management of Data. 2017.](https://assets.amazon.science/dc/2b/4ef2b89649f9a393d37d3e042f4e/amazon-aurora-design-considerations-for-high-throughput-cloud-native-relational-databases.pdf)

### Spanner
- 2013 Spanner [Corbett, James C., et al. "Spanner: Google’s globally distributed database." ACM Transactions on Computer Systems (TOCS) 31.3 (2013): 1-22.](http://static.googleusercontent.com/media/research.google.com/en//archive/spanner-osdi2012.pdf)

### POLARDB

- 2020 POLARDB [Cao, Wei, et al. "{POLARDB} Meets Computational Storage: Efficiently Support Analytical Workloads in {Cloud-Native} Relational Database." 18th USENIX conference on file and storage technologies (FAST 20). 2020.](https://www.usenix.org/system/files/fast20-cao_wei.pdf)

### openGause
- 2021 openGauss [Li, Guoliang, et al. "opengauss: An autonomous database system." Proceedings of the VLDB Endowment 14.12 (2021): 3028-3042.](https://dbgroup.cs.tsinghua.edu.cn/ligl/papers/vldb21-opengauss.pdf)

### DynamoDB
- 2007 Dynamo [DeCandia, Giuseppe, et al. "Dynamo: Amazon's highly available key-value store." ACM SIGOPS operating systems review 41.6 (2007): 205-220.](https://assets.amazon.science/ac/1d/eb50c4064c538c8ac440ce6a1d91/dynamo-amazons-highly-available-key-value-store.pdf)
- 2012 DynamoDB [Sivasubramanian, Swaminathan. "Amazon dynamoDB: a seamlessly scalable non-relational database service." Proceedings of the 2012 ACM SIGMOD International Conference on Management of Data. 2012.](https://dl.acm.org/doi/abs/10.1145/2213836.2213945)
- 2022 DynamoDB [Elhemali, Mostafa, et al. "Amazon {DynamoDB}: A Scalable, Predictably Performant, and Fully Managed {NoSQL} Database Service." 2022 USENIX Annual Technical Conference (USENIX ATC 22). 2022.](https://assets.amazon.science/33/9d/b77f13fe49a798ece85cf3f9be6d/amazon-dynamodb-a-scalable-predictably-performant-and-fully-managed-nosql-database-service.pdf)

### Firestore
- 2023 Firestore [Kesavan, Ram, et al. "Firestore: The NoSQL Serverless Database for the Application Developer." (2023).](https://storage.googleapis.com/pub-tools-public-publication-data/pdf/d647cb73166040a82b7e5569574451be517f5c59.pdf)
