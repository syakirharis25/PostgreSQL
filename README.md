# PostgreSQL
My works related to PostgreSQL, an open-source relational database management system (RDBMS) emphasizing extensibility and technical standards compliance.

## Table of Contents
1. [Introduction.](#introduction)
2. [Official references websites.](#references)
3. [PostgreSQL industry users.](#industry)
4. [PostgreSQL open source projects.](#opensource)
5. [pgAdmin.](#pgadmin)
6. [Running PostgreSQL on Windows PowerShell.](#windowscommand)
7. [GitHub notes.](#github)
8. [GitHub repository calculation.](#calculation)

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
PostgreSQL Core Distribution : https://www.postgresql.org/download/ <br />
pgAdmin official website : https://www.pgadmin.org <br />
pgAdmin official documentation : https://www.pgadmin.org/docs <br />

**_PostgreSQL school_** <br />
PostgreSQL Tutorial : https://www.postgresqltutorial.com <br />

**_PostgreSQL documentation by postgresql.org_** <br />
Chapter 8. Data Types by postgresql.org : https://www.postgresql.org/docs/9.5/datatype.html <br />
DROP TABLE by postgresql.org : https://www.postgresql.org/docs/8.2/sql-droptable.html <br />
DELETE by postgresql.org : https://www.postgresql.org/docs/8.2/sql-delete.html <br />
SELECT by postgresql.org : https://www.postgresql.org/docs/8.2/sql-select.html <br />
CREATE TABLE by postgresql.org : https://www.postgresql.org/docs/8.2/sql-createtable.html <br />
UPDATE TABLE by postgresql.org : https://www.postgresql.org/docs/8.2/sql-update.html <br />
UPDATE by postgresql.org : https://www.postgresql.org/docs/9.1/sql-update.html <br />
SET by postgresql.org : https://www.postgresql.org/docs/9.1/sql-set.html <br />
ALTER TABLE by postgresql.org : https://www.postgresql.org/docs/9.1/sql-altertable.html <br />
TRUNCATE by postgresql.org : https://www.postgresql.org/docs/9.1/sql-truncate.html <br />

**_PostgreSQL documentation by PostgreSQL Tutorial_** <br />
PostgreSQL SUM Function : https://www.postgresqltutorial.com/postgresql-sum-function/ <br /> 
PostgreSQL AVG Function : https://www.postgresqltutorial.com/postgresql-avg-function/ <br />
PostgreSQL COUNT Function : https://www.postgresqltutorial.com/postgresql-count-function/ <br />
PostgreSQL MIN Function : https://www.postgresqltutorial.com/postgresql-min-function/ <br />
PostgreSQL MAX Function : https://www.postgresqltutorial.com/postgresql-max-function/ <br />
PostgreSQL Foreign Key : https://www.postgresqltutorial.com/postgresql-foreign-key/ <br />
PostgreSQL Joins : https://www.postgresqltutorial.com/postgresql-joins/ <br />
PostgreSQL NATURAL JOIN Explained By Examples : https://www.postgresqltutorial.com/postgresql-natural-join/ <br />
PostgreSQL UNION : https://www.postgresqltutorial.com/postgresql-union/ <br />
PL/pgSQL Loop Statements : https://www.postgresqltutorial.com/plpgsql-loop-statements <br />

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

<a name="industry"></a>
## 3. PostgreSQL industry users.
Thousands of companies out there have PostgreSQL for countless business critical and non-critical applications. PostgreSQL is not just used in one industry – it is pretty much everywhere. From automotive to water management. From archaeology to weather services. PostgreSQL is everywhere these days and the number of deployment is growing all over the world.

**_PostgreSQL in BioPharm_** <br />
American Chemical Society : https://www.acs.org <br />
BASF Corporation : https://www.basf.com <br />
Institut de Biologie et Chimie des Protéines : https://www.ibcp.fr <br />
Genentech : https://www.gene.com <br />

**_PostgreSQL in e-Commerce_** <br />
CD Baby : https://cdbaby.com <br />
Champion : https://www.champion.com <br />
Endpoint Corporation : https://www.endpoint.com <br />
Etsy : https://www.etsy.com <br />
FlightAware : https://flightaware.com <br />
FlightStats : https://www.flightstats.com <br />
Whitepages : https://www.whitepages.com <br />

**_PostgreSQL in education_** <br />
The Berkman Klein Center for Internet & Society at Harvard University : https://cyber.harvard.edu <br />
Sternberg Astronomical Institute : http://www.sai.msu.su <br />
The University of Alabama : https://www.ua.edu <br />
The University of California : https://www.universityofcalifornia.edu/ <br />
The University of New South Wales : https://www.unsw.edu.au <br />
The University of Oslo : https://www.uio.no <br />
The University of Sydney : https://sydney.edu.au <br />
Western Sydney University : https://www.westernsydney.edu.au/ <br />
The University of Jyväskylä : https://www.jyu.fi <br />
Charles University : https://cuni.cz <br />
Saint Joseph University : https://www.usj.edu.lb <br />

**_PostgreSQL in finance_** <br />
Journyx : https://journyx.com <br />
TrustCommerce : https://www.trustcommerce.com <br />

**_PostgreSQL in gaming_** <br />
MobyGames : https://www.mobygames.com <br />

**_PostgreSQL in government_** <br />
Garden Grove : https://ggcity.org <br />
National Physical Laboratory of India : http://www.nplindia.in <br />
The National Weather Service : https://www.weather.gov <br />
Registre Français des émissions polluantes : https://www.data.gouv.fr/fr/datasets/registre-francais-des-emissions-polluantes/ <br />
The United Nations Children's Fund (UNICEF) : https://www.unicef.org <br />
The United States Agency for International Development : https://www.usaid.gov <br />
The Centers for Disease Control and Prevention (CDC) : https://www.cdc.gov <br />
The United States Department of Labor : https://www.dol.gov <br />
The General Services Administration : https://www.gsa.gov <br />
The United States Department of State : https://www.state.gov <br />

**_PostgreSQL in health care_** <br />
CalorieKing : https://www.calorieking.com <br />
GNUmed : http://www.gnumed.org <br />
Shannon Medical Center : https://www.shannonhealth.com <br />

**_PostgreSQL in media_** <br />
Creative Commons : https://creativecommons.org <br />
Greenpeace : https://www.greenpeace.org <br />
IMDb : https://www.imdb.com <br />
Macworld : https://www.macworld.com <br />
Penny Arcade : https://www.penny-arcade.com/ <br />

**_PostgreSQL in retail_** <br />
The Rockport Group : https://www.rockport.com <br />

**_PostgreSQL in technology_** <br />
Apple : https://www.apple.com <br />
Fujitsu : https://www.fujitsu.com <br />
Credativ : https://www.credativ.com <br />
Red Hat : https://www.redhat.com <br />
Sun Microsystems : https://www.oracle.com/sun <br />

**_PostgreSQL in technology_** <br />
Cisco : https://www.cisco.com <br />
Juniper Networks : https://www.juniper.net <br />
NTT DATA Corporation : https://www.nttdata.com <br />
Singtel Optus Pty : https://www.optus.com.au/ <br />
Skype : https://www.skype.com <br />
Telstra : https://www.telstra.com.au <br />

<a name="opensource"></a>
## 4. PostgreSQL open source projects.
Bricolage : http://bricolagecms.org <br />
Debian : https://www.debian.org <br />
GForge : https://gforge.com <br />
OpenACS : https://openacs.org <br />
PostGIS : https://postgis.net <br />
SourceForge : https://sourceforge.net/ <br />

<a name="pgadmin"></a>
## 5. pgAdmin.
pgAdmin is a design and management interface for the PostgreSQL database (open source object-relational database system). It is an open source administration and development platform. For database administrators, pgAdmin provides a graphical interface to all the PostgreSQL features. The program supports multiple versions of the PostgreSQL database.

By Default pgAdmin in Microsoft Windows environment will try to find and use the previous data located in `C:\Users\username\AppData\Roaming\pgAdmin`, if the pgAdmin encounter any problem, try to clear all the data in `C:\Users\username\AppData\Roaming\pgAdmin` and then start again the pgAdmin with administrator access.

<a name="windowscommand"></a>
## 6. Running PostgreSQL on Windows PowerShell.
To run PosgreSQL on Microsoft Windows PowerShell, press **[ ⊞ ]** + **[ X ]**, **[ A ]**, **[ ← ]**, **[ Enter ]**, the Windows PowerShell will appear on your screen, then change into your working directory by using the **cd** command, `cd C:\Users\username\Desktop\PostgreSQL` and press **[ Enter ]**. After that type `psql -U postgres -h localhost` and press **[ Enter ]** on your keyboard. When it ask the question `Password for user postgres:`, just type your password when you first installed the PostgreSQL on your system and then press **[ Enter ]**, this will open the command line version of PostgreSQL on Windows PowerShell.
 
<a name="github"></a>
## 7. GitHub notes.
Clone the current GitHub remote repository contents into local machine.
```
$ git clone https://github.com/syakirharis25/PostgreSQL.git
$ cd PostgreSQL/
$ git remote -v
$ git status
```

<a name="calculation"></a>
## 8. GitHub repository calculation.
```
-------------------------------------------------------------------------------
Language                     files          blank        comment           code
-------------------------------------------------------------------------------
SQL                              2              0              0           1011
Markdown                         1             14              0             71
-------------------------------------------------------------------------------
SUM:                             3             14              0           1082
-------------------------------------------------------------------------------
```
Refer to : https://github.com/syakirharis25/cloc
