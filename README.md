queryanalyzer
=============

Query Analyzer for ABAP with editor. Supports OpenSQL syntax for Select, Insert, Update, and Delete operation.
For SELECT statement, just remove the 'INTO TABLE itab' from normal ABAP SELECT statement 

###Example:
```
SELECT k~ebeln p~ebelp FROM EKKO k JOIN EKPO p ON k~eben = p~ebelp. 
```

###How to Deploy
1. Create report in tcode SE38 with name Z_QUERY_ANALYZER
2. Copy and paste content of Z_QUERY_ANALYZER.ab4 to the report
