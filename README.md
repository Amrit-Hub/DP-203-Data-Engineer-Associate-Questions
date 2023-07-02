These are memory based questions for the assessment conducted on Jul 2023. Multiple questions mentioned here can be a part of one question. I have noted the questions best possible.

## Suggestions

- Read this [DP203 Notes1](/files/Dp203DEnotes.pdf)
- Read this [DP203 Notes2](/files/Dp203notes.pdf)
- Practice this [github by Microsoft](https://microsoftlearning.github.io/dp-203-azure-data-engineer/)
- Udemy [course](https://www.udemy.com/course/data-engineering-on-microsoft-azure/)[I personally opted this which includes practice questions too]

## Questions

1. hot vs cold vs archive tiers- days/when to choose
2. When to switch from databricks standard cluster to premium based on limitations.
3. Read databricks cluster config json based questions
4. Table with clustered column, hash distribution- which columns - id col/date col
5. Dim table with star schema- which is SK
6. When to choose SHIR
7. Azure HD Insight based question- basic functionality
8. Synapse life cycle management vs soft delete vs retention vs delete from event hub
9. Event hub - reference input and Stream input
10. Is there data skewness in given table
11. Monitor activities of adf + adb containing jar/notebook/copy
12. Is the table of type SCD 2
13. Date dim table and Transactions on fact table
14. Dim table- type- replicated
15. SCD 2 update using - MERGE/UPDATE/INSERT
16. IoT folder structure when engineers from multiple region access the data - raw/regionid/yyyy/mm/dd/devideid.csv
17. find the SK- identity col
18. Remove old data - switch partiton or delete-where
19. Clustered index usage
20. Copy from sql to synapse using R language- MDF/Copu into/databricks
21. storage format preferred for IoT with high compressibility - csv/txt/avro
22. Repo - collab branch/publish branch/root folder - where is ARM located & where is ARM of xyz located
23. Realtime data in ADLS - autoloader or copy data
24. Rentention setting in Event hub??
25. Log analytics montitor - KQL or adf monitor based
26. Count of tweet every 10 sec- query
27. Count of tweet every 10 sec in last sec - query- hop/window
28. Read ADLS based on given situation - SAS/MIdent/AKeys
29. CLS based Q
30. RLS based Q
31. ADF log for 180 days- how?
32. Data flow debug based- delay
33. Which pipeline failed from given image
34. Read json synapse query - filedquote?
35. cross apply - openjson/opendataset/openrowset
36. txt file has list of table name. read thos tables in adf - filter/lookup
37. %%scala, scala_df.write.______(db) - load/saveastable/synapsesql
38. synapse spark pool measuting unit - monitor?
39. Trigger type from given scenario
40. data>10000? from the shown table, dbcc pdw_showspace....
41. streaming data in adls - how to read in databricks
42. transaction if failed should rollback - begin tran/rollback tran in catch statement/commit tran - query
43. sql pool/spark pool when to use based on situation
44. append or update based on situation
45. json- flatten/expand/explode- query synapse
46. SAS key least maintenance based on situation
47. Transparent data encryption based question
48. Case study on contoso- partition col?, distribution type for transaction?, table or ext table?, range right for right boundaries?

## Lessons Learned

> No matter what, please read the following topics carefully

1. [data-lake-storage-access-control](https://learn.microsoft.com/en-us/azure/storage/blobs/data-lake-storage-access-control)
2. [analytic-functions-azure-stream-analytics](https://learn.microsoft.com/en-us/stream-analytics-query/analytic-functions-azure-stream-analytics)
3. [workspaces-encryption](https://learn.microsoft.com/en-us/azure/synapse-analytics/security/workspaces-encryption)
4. [sql-data-warehouse-tables-index](https://learn.microsoft.com/en-us/azure/synapse-analytics/sql-data-warehouse/sql-data-warehouse-tables-index)
5. [sql-data-warehouse-tables-partition](https://learn.microsoft.com/en-us/azure/synapse-analytics/sql-data-warehouse/sql-data-warehouse-tables-partition)
6. [sql-data-warehouse-tables-distribute](https://learn.microsoft.com/en-us/azure/synapse-analytics/sql-data-warehouse/sql-data-warehouse-tables-distribute)
7. [lifecycle-management-overview](https://learn.microsoft.com/en-us/azure/storage/blobs/lifecycle-management-overview)
8. [security-white-paper-access-control](https://learn.microsoft.com/en-us/azure/synapse-analytics/guidance/security-white-paper-access-control)
9. [stream-analytics-use-reference-data](https://learn.microsoft.com/en-us/azure/stream-analytics/stream-analytics-use-reference-data)
10. [stream-analytics-define-inputs](https://learn.microsoft.com/en-us/azure/stream-analytics/stream-analytics-define-inputs)
11. [stream-analytics-stream-analytics-query-patterns](https://learn.microsoft.com/en-us/azure/stream-analytics/stream-analytics-stream-analytics-query-patterns)
12. [stream-analytics-window-functions](https://learn.microsoft.com/en-us/azure/stream-analytics/stream-analytics-window-functions)
13. [query-json-files](https://learn.microsoft.com/en-us/azure/synapse-analytics/sql/query-json-files)
14. [sql-data-warehouse-load-from-azure-blob-storage-with-polybase](https://learn.microsoft.com/en-us/azure/synapse-analytics/sql-data-warehouse/sql-data-warehouse-load-from-azure-blob-storage-with-polybase)
15. [load-data-from-azure-blob-storage-using-copy](https://learn.microsoft.com/en-us/azure/synapse-analytics/sql-data-warehouse/load-data-from-azure-blob-storage-using-copy)
16. [source-control](https://learn.microsoft.com/en-us/azure/data-factory/source-control)
17. [concepts-pipeline-execution-triggers](https://learn.microsoft.com/en-us/azure/data-factory/concepts-pipeline-execution-triggers)
18. [access-tiers-overview](https://learn.microsoft.com/en-us/azure/storage/blobs/access-tiers-overview?tabs=azure-portal)
19. [monitor-using-azure-monitor](https://learn.microsoft.com/en-us/azure/data-factory/monitor-using-azure-monitor)
20. [synapse-analytics](https://learn.microsoft.com/en-us/azure/databricks/external-data/synapse-analytics)
