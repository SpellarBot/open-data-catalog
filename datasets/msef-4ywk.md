# Maryland African American Heritage Preservation Program Grants, FY2012 and FYTD2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/maryland-african-american-heritage-preservation-program-grants-fy2012-and-fytd2013-57e00) |
| Metadata | [Link](https://data.maryland.gov/api/views/msef-4ywk) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/msef-4ywk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/msef-4ywk/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | msef-4ywk |
| Name | Maryland African American Heritage Preservation Program Grants, FY2012 and FYTD2013 |
| Attribution | Maryland Department of Planning |
| Category | Administrative |
| Tags | african, american, heritage, mht, mdp, planning |
| Created | 2013-01-03T20:15:06Z |
| Publication Date | 2013-01-03T20:19:40Z |

## Description

Maryland African American Heritage Preservation Programs Grants for the fiscal year of 2012 and 2013. The data includes the area location and the amount of the grant that was awarded.

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type | Render Type |
| ======== | ============== | ================ | ================ | ========= | =========== |
| Yes      | time           | fiscal_year      | Fiscal Year      | number    | number      |
| Yes      | series tag     | county           | County           | text      | text        |
| Yes      | series tag     | property_name    | Property Name    | text      | text        |
| No       |                | property_address | Property Address | text      | text        |
| Yes      | series tag     | property_city    | Property City    | text      | text        |
| Yes      | series tag     | property_state   | Property State   | text      | text        |
| Yes      | series tag     | property_zipcode | Property Zipcode | text      | number      |
| Yes      | numeric metric | amount_awarded   | Amount Awarded   | money     | money       |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = property_address
```

## Data Commands

```ls
series e:msef-4ywk d:2012-01-01T00:00:00.000Z t:property_name="Kunta Kinte - Alex Haley Memorial" t:county="Anne Arundel" t:property_zipcode=21401 t:property_state=MD t:property_city=Annapolis m:amount_awarded=36000

series e:msef-4ywk d:2012-01-01T00:00:00.000Z t:property_name="Maynard-Burgess House" t:county="Anne Arundel" t:property_zipcode=21401 t:property_state=MD t:property_city=Annapolis m:amount_awarded=100000

series e:msef-4ywk d:2012-01-01T00:00:00.000Z t:property_name="""Bodies & Souls"" Exhibit" t:county="Baltimore City" t:property_zipcode=21202 t:property_state=MD t:property_city=Baltimore m:amount_awarded=13000
```

## Meta Commands

```ls
metric m:amount_awarded p:double l:"Amount Awarded" t:dataTypeName=money

entity e:msef-4ywk l:"Maryland African American Heritage Preservation Program Grants, FY2012 and FYTD2013" t:attribution="Maryland Department of Planning" t:url=https://data.maryland.gov/api/views/msef-4ywk

property e:msef-4ywk t:meta.view v:id=msef-4ywk v:category=Administrative v:attributionLink=http://planning.maryland.gov/ v:averageRating=0 v:name="Maryland African American Heritage Preservation Program Grants, FY2012 and FYTD2013" v:attribution="Maryland Department of Planning"

property e:msef-4ywk t:meta.view.license v:name="Public Domain"

property e:msef-4ywk t:meta.view.owner v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:displayName=MDP

property e:msef-4ywk t:meta.view.tableauthor v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:roleName=editor v:displayName=MDP
```

## Top Records

```ls
| fiscal_year | county           | property_name                     | property_address                           | property_city | property_state | property_zipcode | amount_awarded | 
| =========== | ================ | ================================= | ========================================== | ============= | ============== | ================ | ============== | 
| 2012        | Anne Arundel     | Kunta Kinte - Alex Haley Memorial | Market Space, foot of Main Street          | Annapolis     | MD             | 21401            | 36000.00       | 
| 2012        | Anne Arundel     | Maynard-Burgess House             | 163 Duke of Gloucester Street              | Annapolis     | MD             | 21401            | 100000.00      | 
| 2012        | Baltimore City   | "Bodies & Souls" Exhibit          | Reginald Lewis Museum, 830 E. Pratt Street | Baltimore     | MD             | 21202            | 13000.00       | 
| 2012        | Baltimore City   | Bauernschmidt Mansion             | 1649 East North Avenue                     | Baltimore     | MD             | 21213            | 53000.00       | 
| 2012        | Baltimore County | Mt. Gilboa A.M.E. Church          | 2312 Westchester Avenue                    | Catonsville   | MD             | 21228            | 35000.00       | 
| 2012        | Baltimore County | Sphinx Club                       | 2101-2111 Pennsylvania Avenue              | Baltimore     | MD             | 21217            | 100000.00      | 
| 2012        | Charles          | Old Pomonkey High School          | 3395 Metropolitan Church Road              | Bryans Road   | MD             | 20616            | 35000.00       | 
| 2012        | Dorchester       | Christ Rock M.E. Church           | 2403 Rock Drive                            | Cambridge     | MD             | 21613            | 100000.00      | 
| 2012        | Frederick        | Laboring Sons Memorial Ground     | 121 East Fifth Street                      | Frederick     | MD             | 21701            | 57000.00       | 
| 2012        | Harford          | Hosanna School                    | 2424 Castleton Road                        | Darlington    | MD             | 21034            | 28000.00       | 
```