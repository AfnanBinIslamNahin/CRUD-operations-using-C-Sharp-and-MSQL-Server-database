# CRUD-operations-using-C-Sharp-and-MSSQL-Server-database
Desktop CRUD App Written In C#(.NET Framework)

## Screenshot
<img width="404" alt="curd" src="https://github.com/user-attachments/assets/44107845-a0a8-4091-947c-ed67d18f7e2b">




### Bulit With
- C#(.Net Framework)
- Microsoft Sql
- Microsoft Visual Studio

- ## Features

- Insert Data
- Delete Data
- Update Data
- Search Data

- ## SQL Query
#### Design Table
```bash
CREATE TABLE [dbo].[CURDForm] (
    [Id]     INT          NOT NULL,
    [Name]   VARCHAR (50) NULL,
    [salary] VARCHAR (50) NULL,
    [city]   VARCHAR (50) NULL,
    PRIMARY KEY CLUSTERED ([Id] ASC)
);
```
#### Insert Data
```bash
insert into CURDForm values (@id,@name,@salary,@city)
```
#### Delete Data
```bash
delete CURDForm where id=@id
```
#### Update Data
```bash
update CURDForm set name=@name,salary=@salary,city=@city where id=@id
```
#### Search Data
```bash
select * from CURDForm where id = @id
```
## Tech Stack

**Programming Language:** C# <br><br>
**Database:** SQL Server<br><br>
**Framework:** Windows Forms<br><br>
**UI Components:** <br>
    -Text Box for entering data.<br>
    - Button for response.<br>
    - Data Grid View for displaying and managing data


## 🛠 Skills
C#, .NET, SQL 

