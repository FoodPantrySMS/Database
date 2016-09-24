 ---- Schema and data is built Sql Server in mind.


How to install on Sql Server Db - 

1.Run sms_service.sql to create all the tables and have them loaded with data.
2.Try the SampleQuery.sql to verify if Step 1 went well.

How to install on Postgres (untested) - 

1.Find the Geography datatype column in postgres and replace it in all instances of Geography in sms_service.sql
2.Replace the TOP 10 in SampleQuery.sql with LIMIT 10.
http://stackoverflow.com/questions/13674031/how-to-get-the-top-10-values-in-postgresql


Will update with more details soon.
