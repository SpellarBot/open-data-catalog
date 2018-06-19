# Viatical Settlement Providers

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/viatical-providers-and-legal-entities) |
| Metadata | [Link](https://data.iowa.gov/api/views/pdbp-h6yh) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/pdbp-h6yh/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/pdbp-h6yh/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | pdbp-h6yh |
| Name | Viatical Settlement Providers |
| Attribution | Iowa Insurance Division, Iowa Department of Commerce |
| Category | Economy |
| Tags | viatical provider, life insurance, catastrophic, life threatening illness |
| Created | 2016-06-14T19:31:24Z |
| Publication Date | 2017-03-08T17:00:09Z |

## Description

This dataset is a listing of viatical settlement providers licensed in the State of Iowa.

## Columns

```ls
| Included | Schema Type    | Field Name    | Name           | Data Type     | Render Type   |
| ======== | ============== | ============= | ============== | ============= | ============= |
| Yes      | series tag     | entityname    | Entity Name    | text          | text          |
| No       |                | address       | Address        | text          | text          |
| Yes      | series tag     | city          | City           | text          | text          |
| Yes      | series tag     | state         | State          | text          | text          |
| Yes      | series tag     | zip_code      | Zip Code       | text          | text          |
| Yes      | numeric metric | businessphone | Business Phone | number        | text          |
| Yes      | series tag     | url           | Provider URL   | url           | url           |
| Yes      | time           | issued        | Issued         | calendar_date | calendar_date |
```

## Time Field

```ls
Value = issued
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = address
```

## Data Commands

```ls
series e:pdbp-h6yh d:2006-03-06T00:00:00.000Z t:zip_code=10010 t:state=NY t:entityname="CREDIT SUISSE LIFE SETTLEMENTS LLC" t:url=http://www.credit-suisse.com t:city="NEW YORK" m:businessphone=2123251772

series e:pdbp-h6yh d:2006-03-06T00:00:00.000Z t:zip_code=30305 t:state=GA t:entityname="HABERSHAM FUNDING LLC" t:url=http://www.habershamfunding.com t:city=ATLANTA m:businessphone=4042338275

series e:pdbp-h6yh d:2007-06-27T00:00:00.000Z t:zip_code=33486 t:state=FL t:entityname="IMPERIAL LIFE SETTLEMENTS, LLC" t:url=http://wwwemergentcapital.com t:city="BOCA RATON" m:businessphone=5619954200
```

## Meta Commands

```ls
metric m:businessphone p:long l:"Business Phone" t:dataTypeName=number

entity e:pdbp-h6yh l:"Viatical Settlement Providers" t:attribution="Iowa Insurance Division, Iowa Department of Commerce" t:url=https://data.iowa.gov/api/views/pdbp-h6yh

property e:pdbp-h6yh t:meta.view v:id=pdbp-h6yh v:category=Economy v:averageRating=0 v:name="Viatical Settlement Providers" v:attribution="Iowa Insurance Division, Iowa Department of Commerce"

property e:pdbp-h6yh t:meta.view.license v:name="Public Domain"

property e:pdbp-h6yh t:meta.view.owner v:id=ym8t-nug5 v:profileImageUrlMedium=/api/users/ym8t-nug5/profile_images/THUMB v:profileImageUrlLarge=/api/users/ym8t-nug5/profile_images/LARGE v:screenName="Iowa Insurance Division (Commerce)" v:profileImageUrlSmall=/api/users/ym8t-nug5/profile_images/TINY v:displayName="Iowa Insurance Division (Commerce)"

property e:pdbp-h6yh t:meta.view.tableauthor v:id=ym8t-nug5 v:profileImageUrlMedium=/api/users/ym8t-nug5/profile_images/THUMB v:profileImageUrlLarge=/api/users/ym8t-nug5/profile_images/LARGE v:screenName="Iowa Insurance Division (Commerce)" v:profileImageUrlSmall=/api/users/ym8t-nug5/profile_images/TINY v:roleName=publisher v:displayName="Iowa Insurance Division (Commerce)"
```

## Top Records

```ls
| entityname                         | address                                            | city            | state | zip_code | businessphone | url                                         | issued              | 
| ================================== | ================================================== | =============== | ===== | ======== | ============= | =========================================== | =================== | 
| CREDIT SUISSE LIFE SETTLEMENTS LLC | ELEVEN MADISON AVE 4TH FLR                         | NEW YORK        | NY    | 10010    | 2123251772    | [http://www.credit-suisse.com, null]        | 2006-03-06T00:00:00 | 
| HABERSHAM FUNDING LLC              | 3495 PIEDMONT RD NE, STE 910, BLG 11, PIEDMONT CTR | ATLANTA         | GA    | 30305    | 4042338275    | [http://www.habershamfunding.com, null]     | 2006-03-06T00:00:00 | 
| IMPERIAL LIFE SETTLEMENTS, LLC     | THE PLAZA 5355 TOWN CTR RD STE 701                 | BOCA RATON      | FL    | 33486    | 5619954200    | [http://wwwemergentcapital.com, null]       | 2007-06-27T00:00:00 | 
| MAPLE LIFE FINANCIAL LLC           | 4350 E WEST HWY STE 900                            | BETHESDA        | MD    | 20814    | 3019512123    | [http://www.maplelifefinancial.com, null]   | 2002-10-11T00:00:00 | 
| COVENTRY FIRST LLC                 | 7111 VALLEY GREEN RD                               | FORT WASHINGTON | PA    | 19034    | 8778368300    | [http://WWW.COVENTRY.COM, null]             | 2002-09-25T00:00:00 | 
| COVENTRY FINANCIAL LLC             | 7111 VALLEY GREEN RD                               | FT WASHINGTON   | PA    | 19034    | 2152335100    | [http://WWW.COVENTRY.COM, null]             | 2011-11-17T00:00:00 | 
| TBS AGENCY INC                     | 1776 PLEASANT PLAIN RD                             | FAIRFIELD       | IA    | 52556    | 6414725100    | [null, null]                                | 2016-02-04T00:00:00 | 
| Q CAPITAL STRATEGIES LLC           | 119 WEST 72ND ST #340                              | NEW YORK        | NY    | 10023    | 2124183270    | [http://www.qcapital.com, null]             | 2014-06-09T00:00:00 | 
| ASSET LIFE SETTLEMENTS LLC         | 1507 PARK CENTER DR #1B                            | ORLANDO         | FL    | 32835    | 8883354769    | [null, null]                                | 2015-02-10T00:00:00 | 
| MAGNA LIFE SETTLEMENTS, INC        | 805 LAS CIMAS PKWY STE 350                         | AUSTIN          | TX    | 78746    | 5129618265    | [http://www.magnalifesettlements.com, null] | 2008-07-18T00:00:00 | 
```