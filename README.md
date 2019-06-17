# SQLCDC-SSIS-Event-Hub

This SSIS package captures change logs for a table from SQL Server and pushes them to azure event hub

1. SSISCDC -- Package to push initial data from table to event hub
2. CDCIncrementalLoad -- Package for  to push subsequent changes (Insert/Update/Delete) to event hub

#Assumptions
1. CDC is enabled for the table
2. Azure Event Hub is created in azure portal

#Useful Links

https://www.red-gate.com/simple-talk/sql/learn-sql-server/introduction-to-change-data-capture-cdc-in-sql-server-2008/

https://docs.microsoft.com/en-us/azure/event-hubs/event-hubs-create

https://www.mattmasson.com/2011/12/cdc-in-ssis-for-sql-server-2012-2/
