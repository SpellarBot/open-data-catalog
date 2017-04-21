# Viatical Brokers

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/viatical-brokers) |
| Metadata | [Link](https://data.iowa.gov/api/views/feh3-5evi) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/feh3-5evi/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/feh3-5evi/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | feh3-5evi |
| Name | Viatical Brokers |
| Attribution | Iowa Insurance Division, Iowa Department of Commerce |
| Category | Economy |
| Tags | viatical broker, ife insurance, catastrophic, life threatening illness |
| Created | 2016-06-14T20:17:34Z |
| Publication Date | 2017-03-09T21:45:03Z |

## Description

This dataset is a listing of viatical brokers that are licensed to do business in Iowa.

## Columns

```ls
| Included | Schema Type    | Field Name    | Name           | Data Type | Render Type |
| ======== | ============== | ============= | ============== | ========= | =========== |
| No       | time           | :updated_at   | updated_at     | meta_data | meta_data   |
| Yes      | series tag     | name          | Name           | text      | text        |
| No       |                | address       | Address        | text      | text        |
| Yes      | series tag     | city          | City           | text      | text        |
| Yes      | series tag     | state         | State          | text      | text        |
| Yes      | series tag     | zip_code      | Zip Code       | text      | text        |
| Yes      | numeric metric | businessphone | Business Phone | number    | text        |
| Yes      | series tag     | businessemail | Business Email | email     | email       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address
```

## Data Commands

```ls
series e:feh3-5evi d:2017-03-08T16:56:35.000Z t:zip_code=33131 t:name="BARBA, CARLOS" t:businessemail=abarba@lifeforcefinancial.com t:state=FL t:city=MIAMI m:businessphone=7329213755

series e:feh3-5evi d:2017-03-08T16:56:35.000Z t:zip_code=50266 t:name="KARKIAINEN, DAVID" t:businessemail=dave@concentricinsurance.com t:state=IA t:city="WEST DES MOINES" m:businessphone=5152254838

series e:feh3-5evi d:2017-03-08T16:56:35.000Z t:zip_code=32810-6374 t:name="MENDELSOHN, JASON" t:businessemail=jason@ashargroup.com t:state=FL t:city=ORLANDO m:businessphone=4077721818
```

## Meta Commands

```ls
metric m:businessphone p:long l:"Business Phone" t:dataTypeName=number

entity e:feh3-5evi l:"Viatical Brokers" t:attribution="Iowa Insurance Division, Iowa Department of Commerce" t:url=https://data.iowa.gov/api/views/feh3-5evi

property e:feh3-5evi t:meta.view v:id=feh3-5evi v:category=Economy v:averageRating=0 v:name="Viatical Brokers" v:attribution="Iowa Insurance Division, Iowa Department of Commerce"

property e:feh3-5evi t:meta.view.license v:name="Public Domain"

property e:feh3-5evi t:meta.view.owner v:id=ym8t-nug5 v:profileImageUrlMedium=/api/users/ym8t-nug5/profile_images/THUMB v:profileImageUrlLarge=/api/users/ym8t-nug5/profile_images/LARGE v:screenName="Iowa Insurance Division (Commerce)" v:profileImageUrlSmall=/api/users/ym8t-nug5/profile_images/TINY v:displayName="Iowa Insurance Division (Commerce)"

property e:feh3-5evi t:meta.view.tableauthor v:id=ym8t-nug5 v:profileImageUrlMedium=/api/users/ym8t-nug5/profile_images/THUMB v:profileImageUrlLarge=/api/users/ym8t-nug5/profile_images/LARGE v:screenName="Iowa Insurance Division (Commerce)" v:profileImageUrlSmall=/api/users/ym8t-nug5/profile_images/TINY v:roleName=publisher v:displayName="Iowa Insurance Division (Commerce)"
```

## Top Records

```ls
| :updated_at | name                  | address                         | city            | state | zip_code   | businessphone | businessemail                 | 
| =========== | ===================== | =============================== | =============== | ===== | ========== | ============= | ============================= | 
| 1488992195  | BARBA, CARLOS         | 601 BRICKELL KEY DRIVESUITE 700 | MIAMI           | FL    | 33131      | 7329213755    | abarba@lifeforcefinancial.com | 
| 1488992195  | KARKIAINEN, DAVID     | 3636 WESTOWN PARKWAYSUITE 250   | WEST DES MOINES | IA    | 50266      | 5152254838    | dave@concentricinsurance.com  | 
| 1488992195  | MENDELSOHN, JASON     | 1800 PEMBROOK DRIVESUITE 240    | ORLANDO         | FL    | 32810-6374 | 4077721818    | jason@ashargroup.com          | 
| 1488992195  | PERMISON, PAUL        | 111 ST JOSEPHS TERRACE          | WOODBRIDGE      | NJ    | 07095      | 7328550670    | paul@ardangroup.com           | 
| 1488992195  | SCHILLIG, RICHARD     | 2535 TECH DRIVE310              | BETTENDORF      | IA    | 52722      | 5633322200    | rjsandassoc@att.net           | 
| 1488992215  | HEIL, JEANNE M        | 500 1ST ST SE                   | CEDAR RAPIDS    | IA    | 52401      | 3193645193    | jheil@truenorthcompanies.com  | 
| 1488992215  | HULSTEIN JR, TONY     | 3192 MCKINLEY AVENUE            | SHELDON         | IA    | 51201      | 7123249742    | hulsteinins2@msn.com          | 
| 1488992215  | STARK, ROBERT         | 3255 NW 94TH AVE #8532          | CORAL SPRINGS   | FL    | 33075      | 2123804277    | rstark@melvillecapital.com    | 
| 1488992215  | BRONSON, MICHAEL      | 2512 10TH AVENUE SW             | CEDAR RAPIDS    | IA    | 52408      | 3193968030    | mbronson@bronsonbrokerage.com | 
| 1488992215  | GAYNOR, PETER MICHAEL | 6860 LONGLEAF DR                | PARKLAND        | FL    | 33076      | 8663265433    | lore@lisettlements.com        | 
```