These are memory based questions for the assessment conducted on Jul 2023. Multiple questions mentioned here can be a part of one question. I have noted the questions best possible.

## Suggestions

- Read this [DP-203 Notes1](/files/Dp-203 DE notes.pdf)
- Read this [DP-203 Notes2](/files/Dp-203 notes.pdf)
- Practice this [github by Microsoft](https://microsoftlearning.github.io/dp-203-azure-data-engineer/)
- Udemy [course ](https://www.udemy.com/course/data-engineering-on-microsoft-azure/)[I personally opted this which includes practice questions too]

## Questions

1. hot vs cold vs archive tiers- days/when to choose
2. When to swicth from databricks standard cluster to premium based on limitations.
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
48. Case study- partition col?, distribution type for transaction?, table or ext table?, range right for right boundaries?

## Lessons Learned

No matter what, please read the following topics carefully

1. Storage Tiers
2. Partition Tables
3. Indexing
4. Event hub
5. Synapse read json complete query with param and values
6. Window query
7.
