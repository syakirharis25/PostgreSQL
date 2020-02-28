# PostgreSQL
My works related to PostgreSQL, an open-source relational database management system (RDBMS) emphasizing extensibility and technical standards compliance.

## Table of Contents
1. [Introduction.](#introduction)
2. [Official references websites.](#references)
3. [pgAdmin.](#pgadmin)
4. [Running PostgreSQL on Windows PowerShell.](#windowscommand)
5. [GitHub notes.](#github)
6. [GitHub repository calculation.](#calculation)

<a name="introduction"></a>
## 1. Introduction.
<img src="postgresql.png" height="150"> 
PostgreSQL, also known as Postgres, is a free and open-source relational database management system (RDBMS) emphasizing extensibility and technical standards compliance. It is designed to handle a range of workloads, from single machines to data warehouses or Web services with many concurrent users. It is the default database for macOS Server, and is also available for Linux, FreeBSD, OpenBSD, and Windows.
<br /> <br />
PostgreSQL features transactions with Atomicity, Consistency, Isolation, Durability (ACID) properties, automatically updatable views, materialized views, triggers, foreign keys, and stored procedures. PostgreSQL is developed by the PostgreSQL Global Development Group, a diverse group of many companies and individual contributors.
<br /> <br />
PostgreSQL evolved from the Ingres project at the University of California, Berkeley. In 1982, the leader of the Ingres team, Michael Stonebraker, left Berkeley to make a proprietary version of Ingres. He returned to Berkeley in 1985, and began a post-Ingres project to address the problems with contemporary database systems that had become increasingly clear during the early 1980s. He won the Turing Award in 2014 for these and other projects, and techniques pioneered in them.
<br /> <br />
In 1996, the project was renamed to PostgreSQL to reflect its support for SQL. The online presence at the website PostgreSQL.org began on October 22, 1996. The first PostgreSQL release formed version 6.0 on January 29, 1997. Since then developers and volunteers around the world have maintained the software as The PostgreSQL Global Development Group.
<br /> <br />
The project continues to make releases available under its free and open-source software PostgreSQL License. Code comes from contributions from proprietary vendors, support companies, and open-source programmers.

<a name="references"></a>
## 2. Official references websites.
PostgreSQL official website : https://www.postgresql.org <br />
PostgreSQL official download page : https://www.postgresql.org/download/ <br />
PostgreSQL official documentation :https://www.postgresql.org/docs/ <br />

**_PostgreSQL documentation by postgresql.org_** <br />
Chapter 8. Data Types by postgresql.org : https://www.postgresql.org/docs/9.5/datatype.html <br />
DROP TABLE by postgresql.org : https://www.postgresql.org/docs/8.2/sql-droptable.html <br />
DELETE by postgresql.org : https://www.postgresql.org/docs/8.2/sql-delete.html <br />
SELECT by postgresql.org : https://www.postgresql.org/docs/8.2/sql-select.html <br />

**_PostgreSQL questions and answers_** <br />
Stack Overflow questions and answers website : https://stackoverflow.com/ <br />

**_PostgreSQL related technologies_** <br />
DataGrip : https://www.jetbrains.com/datagrip/ <br />
pgAdmin : https://www.pgadmin.org <br />
Mockaroo data generator : https://mockaroo.com <br />

**_PostgreSQL questions and answers by Stack Overflow_** <br />
pgadmin4 : postgresql application server could not be contacted. by Stack Overflow : https://stackoverflow.com/questions/43211296/pgadmin4-postgresql-application-server-could-not-be-contacted
keystroke to clear screen in psql? by Stack Overflow : https://stackoverflow.com/questions/26065426/keystroke-to-clear-screen-in-psql <br />

**_PostgreSQL related articles_** <br />
pgAdmin by DataOne : https://www.dataone.org/software-tools/pgadmin <br />

PostgreSQL was created by Michael Stonebraker : https://github.com/mstonebraker <br />

<a name="pgadmin"></a>
## 3. pgAdmin.
pgAdmin is a design and management interface for the PostgreSQL database (open source object-relational database system). It is an open source administration and development platform. For database administrators, pgAdmin provides a graphical interface to all the PostgreSQL features. The program supports multiple versions of the PostgreSQL database.

By Default pgAdmin in Microsoft Windows environment will try to find and use the previous data located in `C:\Users\username\AppData\Roaming\pgAdmin`, if the pgAdmin encounter any problem, try to clear all the data in `C:\Users\username\AppData\Roaming\pgAdmin` and then start again the pgAdmin with administrator access.

<a name="windowscommand"></a>
## 4. Running PostgreSQL on Windows PowerShell.
To run PosgreSQL on Microsoft Windows PowerShell, press **[ ⊞ ]** + **[ X ]**, **[ A ]**, **[ ← ]**, **[ Enter ]**, the Windows PowerShell will appear on your screen, then change into your working directory by using the **cd** command, `cd C:\Users\username\Desktop\PostgreSQL` and press **[ Enter ]**. After that type `psql -U postgres -h localhost` and press **[ Enter ]** on your keyboard. When it ask the question `Password for user postgres:`, just type your password when you first installed the PostgreSQL on your system and then press **[ Enter ]**, this will open the command line version of PostgreSQL on Windows PowerShell.
 
<a name="github"></a>
## 5. GitHub notes.
Clone the current GitHub remote repository contents into local machine.
```
$ git clone https://github.com/syakirharis25/PostgreSQL.git
$ cd PostgreSQL/
$ git remote -v
$ git status
```

<a name="calculation"></a>
## 6. GitHub repository calculation.
```
-------------------------------------------------------------------------------
Language                     files          blank        comment           code
-------------------------------------------------------------------------------
Markdown                         1              5              0             37
-------------------------------------------------------------------------------
```
Refer to : https://github.com/syakirharis25/cloc
