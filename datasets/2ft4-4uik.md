# Lobbyist Data - Historical - Lobbyist Registry - 2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/lobbyist-data-lobbyist-registry-2010-1f33b) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/2ft4-4uik) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/2ft4-4uik/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/2ft4-4uik/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | 2ft4-4uik |
| Name | Lobbyist Data - Historical - Lobbyist Registry - 2010 |
| Attribution | City of Chicago |
| Category | Ethics |
| Tags | lobbyists, historical |
| Created | 2011-06-07T17:30:57Z |
| Publication Date | 2011-06-07T17:30:57Z |

## Description

All lobbyist registration fillings submitted to the Board of Ethics during the 2010 reporting period. / All lobbyists must register with the City of Chicago Board of Ethics by filing a Statement of Registration within five business days of engaging in lobbying activity and annually thereafter by January 20th. 
Lobbyist registration information is submitted to the Board of Ethics in paper form and is available in its entirety in the Board's offices. The Board has, since 2000, compiled and posted static lists of all lobbyists and their clients online. Data for the 2010 reporting period is limited because previous policy did not require the Board of Ethics to prioritize the reporting of all data available from paper filings. 
Moving forward, the Board of Ethics will compile and report more data about lobbyists and their activities, and make that additional information publicly available in machine-readable format. /  
Data Owner:  Board of Ethics 
[http://j.mp/mbH9BN] /

Time Period: January 1, 2010 to December 31, 2010 /
Related Applications:  Registered Lobbyist List [http://j.mp/l8LwAq], 
2011 Lobbyist Registry  [http://j.mp/ifigjs]

## Columns

```ls
| Included | Schema Type | Field Name                 | Name                       | Data Type | Render Type |
| ======== | =========== | ========================== | ========================== | ========= | =========== |
| Yes      | series tag  | lobbyist_last_name         | LOBBYIST LAST NAME         | text      | text        |
| Yes      | series tag  | lobbyist_first_name        | LOBBYIST FIRST NAME        | text      | text        |
| No       |             | lobbyist_address           | LOBBYIST ADDRESS           | text      | text        |
| Yes      | series tag  | lobbyist_city              | LOBBYIST CITY              | text      | text        |
| Yes      | series tag  | lobbyist_zip               | LOBBYIST ZIP               | text      | number      |
| Yes      | series tag  | registered_employers_names | REGISTERED EMPLOYERS NAMES | text      | text        |
| Yes      | series tag  | lobbying_clients_names     | LOBBYING CLIENTS NAMES     | text      | text        |
```

## Time Field

```ls
Value = 2010
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = lobbyist_address
```

## Data Commands

```ls
series e:2ft4-4uik d:2010-01-01T00:00:00.000Z t:registered_employers_names="Diageo NA" t:lobbyist_zip=60606 t:lobbyist_first_name=Anthony t:lobbying_clients_names="Diageo NA" t:lobbyist_city=Chicago t:lobbyist_last_name=Abbinante m:row_number.2ft4-4uik=1

series e:2ft4-4uik d:2010-01-01T00:00:00.000Z t:registered_employers_names="William Blair and Co." t:lobbyist_zip=60606 t:lobbyist_first_name=David t:lobbying_clients_names="William Blair & Co., LLC" t:lobbyist_city=Chicago t:lobbyist_last_name=Abel m:row_number.2ft4-4uik=2

series e:2ft4-4uik d:2010-01-01T00:00:00.000Z t:registered_employers_names="Rolando Acosta" t:lobbyist_zip=60625 t:lobbyist_first_name=Rolando t:lobbying_clients_names="Cooper Venture One, LLC" t:lobbyist_city=Chicago t:lobbyist_last_name=Acosta m:row_number.2ft4-4uik=3
```

## Meta Commands

```ls
metric m:row_number.2ft4-4uik p:long l:"Row Number"

entity e:2ft4-4uik l:"Lobbyist Data - Historical - Lobbyist Registry - 2010" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/2ft4-4uik

property e:2ft4-4uik t:meta.view v:id=2ft4-4uik v:category=Ethics v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="Lobbyist Data - Historical - Lobbyist Registry - 2010" v:attribution="City of Chicago"

property e:2ft4-4uik t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:2ft4-4uik t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| lobbyist_last_name | lobbyist_first_name | lobbyist_address                | lobbyist_city | lobbyist_zip | registered_employers_names | lobbying_clients_names     | 
| ================== | =================== | =============================== | ============= | ============ | ========================== | ========================== | 
| Abbinante          | Anthony             | 333 W. Wacker Drive, Suite 1100 | Chicago       | 60606        | Diageo NA                  | Diageo NA                  | 
| Abel               | David               | 222 W. Adams St.                | Chicago       | 60606        | William Blair and Co.      | William Blair & Co., LLC   | 
| Acosta             | Rolando             | 2949 W. Gregory St.             | Chicago       | 60625        | Rolando Acosta             | Cooper Venture One, LLC    | 
| Acosta             | Rolando             | 2949 W. Gregory St.             | Chicago       | 60625        | Rolando Acosta             | Elston Center, LLC         | 
| Acosta             | Rolando             | 2949 W. Gregory St.             | Chicago       | 60625        | Rolando Acosta             | Hispanic Hospitality Group | 
| Acosta             | Rolando             | 2949 W. Gregory St.             | Chicago       | 60625        | Rolando Acosta             | Lawrence Fisheries         | 
| Acosta             | Rolando             | 2949 W. Gregory St.             | Chicago       | 60625        | Rolando Acosta             | Wabash Development Group   | 
| Acosta             | Rolando             | 2949 W. Gregory St.             | Chicago       | 60625        | Rolando Acosta             | Resurrection Project       | 
| Acosta             | Rolando             | 2949 W. Gregory St.             | Chicago       | 60625        | Rolando Acosta             | Kargil Development         | 
| Acosta             | Rolando             | 2949 W. Gregory St.             | Chicago       | 60625        | Rolando Acosta             | Logan Square Kitchen       | 
```