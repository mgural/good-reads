## MySQL

- https://dba.stackexchange.com/a/73249 (enforce SSL / TLS for specific DB users)
- https://forums.mysql.com/read.php?10,190408,190613#msg-190613 (Get all possible enum values for a column)
- https://www.oreilly.com/library/view/mysql-reference-manual/0596002653/ch05s03.html (Locking)
- https://www.mysqltutorial.org/mysql-json/ (JSON columns)
- https://dev.mysql.com/doc/refman/5.7/en/create-table-secondary-indexes.html (index on JSON column using generated column and an index on it)
- https://www.techbeamers.com/mysql-upsert/ (Upsert)
- https://www.mysqltutorial.org/mysql-left-join.aspx (Look at the `LEFT JOIN clause to find unmatched rows`)
- https://askubuntu.com/a/784347 (Change MySQL root password)


## Redis

- https://scalegrid.io/blog/top-redis-use-cases-by-core-data-structure-types/
- https://www.infoworld.com/article/3230455/how-to-use-redis-for-real-time-metering-applications.html?page=2 (Rate limiting examples)
- https://scalegrid.io/blog/introduction-to-redis-data-structures-hashes/ (Similar to the instagram engineering post on memory savings using hashes. Touches a bit on `list-max-ziplist-entries` and `list-max-ziplist-value`)
- https://scalegrid.io/blog/introduction-to-redis-data-structure-bitmaps/
- https://cloudplatform.googleblog.com/2015/04/a-guy-walks-into-a-NoSQL-bar-and-asks-how-many-servers-to-get-1Mil-ops-a-second.html (Performance: 1 million ops / s)
- https://redis.io/topics/lru-cache
- https://redis.io/topics/data-types-intro
- https://redis.io/topics/transactions

### Redis Optimization

- https://instagram-engineering.com/storing-hundreds-of-millions-of-simple-key-value-pairs-in-redis-1091ae80f74c (save memory using Hash instead of strings)
- https://redis.io/topics/memory-optimization

### Advanced

- https://redis.io/topics/indexes


## PostgreSQL

- https://robots.thoughtbot.com/reading-an-explain-analyze-query-plan
- https://robots.thoughtbot.com/why-postgres-wont-always-use-an-index
- https://robots.thoughtbot.com/advanced-postgres-performance-tips
- https://www.postgresql.org/docs/9.4/static/explicit-locking.html
- http://engineering.harrys.com/2017/06/28/atomic-operations-in-sql.html
- https://stackoverflow.com/a/30417601 (List all values in enum type)
- https://stackoverflow.com/a/5331571 (Save results of SQL command to a file on your own machine)
- https://stackoverflow.com/a/1611680 (Get all sequences)
- https://stackoverflow.com/a/9428353 (Run SQL file in psql)
- https://stackoverflow.com/a/31376017 (Dump 1 table to a file using `pg_dump`)
- https://www.postgresqltutorial.com/postgresql-sum-function/ (Using the SUM function)
- https://stackoverflow.com/a/59938852 (PostgreSQL Helm chart stores password in PV; need to delete those on uninstall so that new password can be used on new install)


## SQL

- https://dev.to/abdisalan_js/1-sql-query-you-should-stop-using-1e5k (Don't use OFFSET for pagination)
- https://dev.to/ivoecpereira/why-you-shouldn-t-use-offset-and-limit-for-your-pagination-610
- https://searchoracle.techtarget.com/answer/LEFT-OUTER-JOIN-with-ON-condition-or-WHERE-condition (`JOIN` with condition on another table)
