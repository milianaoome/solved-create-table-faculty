Download Link: https://assignmentchef.com/product/solved-create-table-faculty
<br>
CREATE TABLE Faculty (Faculty_ID INT PRIMARY KEY IDENTITY, LastName VARCHAR (20) NOT NULL, FirstName VARCHAR (20) NOT NULL, Department VARCHAR (10)

1.     Write a transaction that inserts three records into the Faculty table.

2.     Write a transaction that deletes one of the newly inserted records.

3.     Delete all C term courses. If the total enrollment for those courses is greater than 50, roll back the transaction

4.     Use BEGIN TRAN and COMMIT TRAN to delete all records from your Faculty database. Use ROLLBACK TRAN to reverse all deletions.

5.     Delete all records from your Faculty table. Use save point in such a way that you can rollback transactions to leave the original Faculty database. Display the current table following each row restoration.