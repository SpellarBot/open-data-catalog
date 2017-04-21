# DOI Insurance Companies

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/doi-insurance-companies) |
| Metadata | [Link](https://data.illinois.gov/api/views/srab-f9cm) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/srab-f9cm/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/srab-f9cm/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | srab-f9cm |
| Name | DOI Insurance Companies |
| Category | Social/Healthcare |
| Tags | doi companies |
| Created | 2017-01-03T19:17:21Z |
| Publication Date | 2017-01-03T19:20:06Z |

## Description

as of 1/1/2017

## Columns

```ls
| Included | Schema Type | Field Name    | Name          | Data Type     | Render Type   |
| ======== | =========== | ============= | ============= | ============= | ============= |
| Yes      | series tag  | companyname   | CompanyName   | text          | text          |
| No       |             | address_line1 | Address Line1 | text          | text          |
| No       |             | address_line2 | Address Line2 | text          | text          |
| Yes      | series tag  | city          | City          | text          | text          |
| Yes      | series tag  | state         | State         | text          | text          |
| Yes      | series tag  | zipcode       | zipcode       | text          | text          |
| Yes      | series tag  | country       | Country       | text          | text          |
| Yes      | time        | licensedate   | LicenseDate   | calendar_date | calendar_date |
| Yes      | series tag  | type          | Type          | text          | text          |
| Yes      | series tag  | class1        | Class1        | text          | text          |
| Yes      | series tag  | class2        | Class2        | text          | text          |
```

## Time Field

```ls
Value = licensedate
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = address_line1,address_line2
```

## Data Commands

```ls
series e:srab-f9cm d:1949-11-17T00:00:00.000Z t:class1=AB t:zipcode=60181 t:state=IL t:type=11 t:companyname="4 Ever Life Insurance Company" t:city="Oakbrook Terrace" m:row_number.srab-f9cm=1

series e:srab-f9cm d:1975-11-01T00:00:00.000Z t:class1=A t:zipcode=60062-7127 t:state=IL t:type=11 t:companyname="Allstate Assurance Company" t:city=Northbrook m:row_number.srab-f9cm=2

series e:srab-f9cm d:1957-04-09T00:00:00.000Z t:class1=ABC t:zipcode=60062-7127 t:state=IL t:type=11 t:companyname="Allstate Life Insurance Company" t:city=Northbrook m:row_number.srab-f9cm=3
```

## Meta Commands

```ls
metric m:row_number.srab-f9cm p:long l:"Row Number"

entity e:srab-f9cm l:"DOI Insurance Companies" t:url=https://data.illinois.gov/api/views/srab-f9cm

property e:srab-f9cm t:meta.view v:id=srab-f9cm v:category=Social/Healthcare v:averageRating=0 v:name="DOI Insurance Companies"

property e:srab-f9cm t:meta.view.owner v:id=aauq-aa8g v:screenName="Suzann Rhodes" v:displayName="Suzann Rhodes"

property e:srab-f9cm t:meta.view.tableauthor v:id=aauq-aa8g v:screenName="Suzann Rhodes" v:roleName=publisher v:displayName="Suzann Rhodes"
```

## Top Records

```ls
| companyname                            | address_line1                     | address_line2 | city             | state | zipcode    | country | licensedate         | type | class1 | class2 | 
| ====================================== | ================================= | ============= | ================ | ===== | ========== | ======= | =================== | ==== | ====== | ====== | 
| 4 Ever Life Insurance Company          | 2 Mid America Plaza Suite 200     |               | Oakbrook Terrace | IL    | 60181      |         | 1949-11-17T00:00:00 | 11   | AB     |        | 
| Allstate Assurance Company             | 3075 Sanders Rd                   |               | Northbrook       | IL    | 60062-7127 |         | 1975-11-01T00:00:00 | 11   | A      |        | 
| Allstate Life Insurance Company        | 3075 Sanders Rd                   | Suite H1E     | Northbrook       | IL    | 60062-7127 |         | 1957-04-09T00:00:00 | 11   | ABC    |        | 
| Amalgamated Life & Health Insurance Co | 333 S Ashland Blvd                |               | Chicago          | IL    | 60607      |         | 1940-03-16T00:00:00 | 11   | AB     |        | 
| American Specialty Health Insurance Co | 10221 Wateridge Circle            |               | San Diego        | CA    | 92121      |         | 1974-07-24T00:00:00 | 11   | AB     |        | 
| Bankers Life & Casualty Company        | 111 East Wacker Drive, Suite 2100 |               | Chicago          | IL    | 60601-4508 |         | 1942-11-30T00:00:00 | 11   | ABC    |        | 
| BCBSIL GP Insurance Company            | 300 East Randolph Street          |               | Chicago          | IL    | 60601-5099 |         | 2016-08-11T00:00:00 | 11   | B      |        | 
| Celtic Insurance Company               | 77 West Wacker Drive              | Suite 1200    | Chicago          | IL    | 60601      |         | 1958-04-10T00:00:00 | 11   | AB     |        | 
| Columbian Life Insurance Company       | 4704 Vestal Pkwy East             | P O Box 1381  | Binghamton       | NY    | 13902-1381 |         | 1988-05-04T00:00:00 | 11   | ABC    |        | 
| Combined Insurance Company of America  | 1000 N Milwaukee Ave              |               | Glenview         | IL    | 60025-2423 |         | 1949-10-19T00:00:00 | 11   | AB     |        | 
```