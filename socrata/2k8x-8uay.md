# Insurance Producer Business Entities

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/insurance-producer-business-entities) |
| Metadata | [Link](https://data.iowa.gov/api/views/2k8x-8uay) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/2k8x-8uay/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/2k8x-8uay/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | 2k8x-8uay |
| Name | Insurance Producer Business Entities |
| Category | Economy |
| Created | 2016-11-17T15:25:47Z |
| Publication Date | 2016-11-17T15:31:24Z |

## Columns

```ls
| Included | Schema Type | Field Name  | Name        | Data Type     | Render Type   |
| ======== | =========== | =========== | =========== | ============= | ============= |
| Yes      | series tag  | entity_name | Entity Name | text          | text          |
| Yes      | series tag  | email       | Email       | text          | text          |
| No       |             | address1    | Address1    | text          | text          |
| No       |             | address2    | Address2    | text          | text          |
| Yes      | series tag  | city        | City        | text          | text          |
| Yes      | series tag  | state       | State       | text          | text          |
| Yes      | series tag  | zip         | ZIP         | text          | text          |
| Yes      | time        | expiry_date | Expiry Date | calendar_date | calendar_date |
```

## Time Field

```ls
Value = expiry_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = address1,address2
```

## Data Commands

```ls
series e:2k8x-8uay d:2017-02-28T00:00:00.000Z t:zip=19803 t:entity_name="21ST CENTURY INSURANCE AND FINANCIAL SERVICES, INC" t:email=jennifer.timm@21st.com t:state=DE t:city=WILMINGTON m:row_number.2k8x-8uay=1

series e:2k8x-8uay d:2019-08-31T00:00:00.000Z t:zip=37901 t:entity_name="21st Mortgage Corporation" t:email=dhickman@21stmortgage.com t:state=TN t:city=KNOXVILLE m:row_number.2k8x-8uay=2

series e:2k8x-8uay d:2018-08-31T00:00:00.000Z t:zip=19482 t:entity_name="A-G ADMINISTRATORS INC" t:email=blinsurance@cscglobal.com t:state=PA t:city="VALLEY FORGE" m:row_number.2k8x-8uay=3
```

## Meta Commands

```ls
metric m:row_number.2k8x-8uay p:long l:"Row Number"

entity e:2k8x-8uay l:"Insurance Producer Business Entities" t:url=https://data.iowa.gov/api/views/2k8x-8uay

property e:2k8x-8uay t:meta.view v:id=2k8x-8uay v:category=Economy v:averageRating=0 v:name="Insurance Producer Business Entities"

property e:2k8x-8uay t:meta.view.owner v:id=ym8t-nug5 v:profileImageUrlMedium=/api/users/ym8t-nug5/profile_images/THUMB v:profileImageUrlLarge=/api/users/ym8t-nug5/profile_images/LARGE v:screenName="Iowa Insurance Division (Commerce)" v:profileImageUrlSmall=/api/users/ym8t-nug5/profile_images/TINY v:displayName="Iowa Insurance Division (Commerce)"

property e:2k8x-8uay t:meta.view.tableauthor v:id=ym8t-nug5 v:profileImageUrlMedium=/api/users/ym8t-nug5/profile_images/THUMB v:profileImageUrlLarge=/api/users/ym8t-nug5/profile_images/LARGE v:screenName="Iowa Insurance Division (Commerce)" v:profileImageUrlSmall=/api/users/ym8t-nug5/profile_images/TINY v:roleName=publisher v:displayName="Iowa Insurance Division (Commerce)"
```

## Top Records

```ls
| entity_name                                        | email                         | address1           | address2              | city           | state | zip   | expiry_date         | 
| ================================================== | ============================= | ================== | ===================== | ============== | ===== | ===== | =================== | 
| 21ST CENTURY INSURANCE AND FINANCIAL SERVICES, INC | jennifer.timm@21st.com        | 21ST CENTURY PLAZA | 3 BEAVER VALLEY RD    | WILMINGTON     | DE    | 19803 | 2017-02-28T00:00:00 | 
| 21st Mortgage Corporation                          | dhickman@21stmortgage.com     | PO BOX 477         |                       | KNOXVILLE      | TN    | 37901 | 2019-08-31T00:00:00 | 
| A-G ADMINISTRATORS INC                             | blinsurance@cscglobal.com     | P. O. BOX 979      |                       | VALLEY FORGE   | PA    | 19482 | 2018-08-31T00:00:00 | 
| ABSOLUTE SURETY LLC                                | bbollinger@absolutesurety.com | PO BOX 547898      |                       | ORLANDO        | FL    | 32854 | 2018-10-31T00:00:00 | 
| ACRISURE LLC                                       | dtauro@acrisure.com           | PO BOX 1788        |                       | GRAND RAPIDS   | MI    | 49316 | 2017-10-31T00:00:00 | 
| ADAIR MACCLELLEN ALEXANDRIA AND ASSOC LLC          | igarza@amaofsa.com            | P O BOX 659570     |                       | SAN ANTONIO    | TX    | 78265 | 2018-06-30T00:00:00 | 
| ADCO GENERAL CORPORATION                           | thomasr@adcogen.com           | PO BOX 40007       |                       | DENVER         | CO    | 80204 | 2017-02-28T00:00:00 | 
| ADVANCED INS SYSTEMS                               | mike.mcguire119@gmail.com     | PO BOX 287         |                       | GENESEO        | IL    | 61254 | 2019-09-30T00:00:00 | 
| AEW INS AGENCY LLC                                 | jmwallace@aew-insurance.com   | JODI WALLACE       | 929 W ADAMS ST        | CHICAGO        | IL    | 60607 | 2018-06-30T00:00:00 | 
| AG PERFORMANCE                                     | pam.yegge@agperformance.com   | AG PERFORMANCE     | 710 NORTH MAIN STREET | BUFFALO CENTER | IA    | 50424 | 2017-01-31T00:00:00 | 
```