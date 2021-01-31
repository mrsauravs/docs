---
description: 'Saurabh Sugandh, 2 May 2020'
---

# Deduplicate your data

![](../.gitbook/assets/deduplicate.jpg)

There was a time when tape backups were used to store enterprise-level data. Many enterprises had used that backup technology and remained in the business. With the advent and the changing dynamics of new technologies, the old-fashioned data backup solution is not helpful. Enterprises now work more with the remote sites and cloud-based storage is a way to move forward. To reduce the data recovery time, data deduplication or dedupe is now a popular term used in the industries.

Data deduplication is often referred to as intelligent compression as this method allows datasets to be stored for only one-instance. This drastically reduces the redundant data and allows to achieve the desired level of data compression. It is a form of incremental backup that allows only the changed copies to backup. Depending on the backup environment, data deduplication techniques are of two types. Inline deduplication and Post-processing dedupe. Inline dedupe removes data redundancies when the data is written and stored. It is a form of synchronous dedupe. In a way, it reduces the amount of required backup storage but can also create bottlenecks. Some data storage vendors often asks their customers to turn-off Inline dedupe for primary storage. The other technique, post-processing dedupe, is a asynchronous process that removes redundant data after it has been written and stored. It gives the flexibility to dedupe only those workloads that are required. But it also demands a larger data storage.

The dedupe operation could be on file-level and block-level. The file-level operation checks for the attributes of file against an index. Only the unique files are stored \(or backed up\) and copies are replaced with a pointer to the original \(stub or a subroutine to a program\). The block-level dedupe operation goes beyond and creates chunks within a file. Each chunk is then parsed with a hash algorithm such as SHA-1, SHA-2, or, SHA-256. Even a smallest update modifies the hash. The hash is stored against an index. In rare cases, a problem known as hash collision arises. This is a situation where two blocks have produced the same hash. In this case, data loss happens and the situation is termed as false-positive.

Data dedupe happens either at the source or at the target. Dedupe at source reduces cost on additional hardware and target-based dedupe demands additional costs. However, dedupe at target has a higher performance advantage for large datasets. Depending on the cost and other business factors, source-dedupe or target-dedupe can be used.

The advantages that data deduplication provides are not only confined to a reduced data footprint or tape backups. It extends to the modern-day style of cloud-based computing. There is a growing need and demand for data governance. Data analysis for a small dataset is more practical and easy to maintain for multi-user scenarios.

