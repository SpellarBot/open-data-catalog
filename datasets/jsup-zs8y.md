# County Clerk -- Directory Of Elected Ofiicials - via Jurisdiction

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/county-clerk-directory-of-elected-ofiicials-via-jurisdiction-caaa6) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/jsup-zs8y) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/jsup-zs8y/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/jsup-zs8y/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | jsup-zs8y |
| Name | County Clerk -- Directory Of Elected Ofiicials - via Jurisdiction |
| Attribution | Cook County Clerk |
| Created | 2011-09-30T21:43:37Z |
| Publication Date | 2014-10-27T15:42:07Z |

## Description

List of Elected Officials via Jurisdiction along with the City they represent

## Columns

```ls
| Included | Schema Type    | Field Name   | Name         | Data Type | Render Type |
| ======== | ============== | ============ | ============ | ========= | =========== |
| No       | time           | :updated_at  | updated_at   | meta_data | meta_data   |
| Yes      | series tag     | office       | Office       | text      | text        |
| Yes      | series tag     | jurisdiction | Jurisdiction | text      | text        |
| Yes      | series tag     | first_name   | First Name   | text      | text        |
| Yes      | series tag     | middle_name  | Middle Name  | text      | text        |
| Yes      | series tag     | last_name    | Last Name    | text      | text        |
| Yes      | numeric metric | term         | Term         | number    | number      |
| Yes      | series tag     | election_id  | Election ID  | text      | text        |
| Yes      | series tag     | phone        | Phone        | text      | text        |
| Yes      | series tag     | fax          | Fax          | text      | number      |
| Yes      | series tag     | website      | Website      | url       | url         |
| Yes      | series tag     | email        | Email        | email     | email       |
| Yes      | numeric metric | phone2       | Phone2       | number    | number      |
| Yes      | numeric metric | fax2         | Fax2         | number    | number      |
| Yes      | series tag     | website2     | Website2     | url       | url         |
| Yes      | series tag     | email2       | Email2       | email     | email       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:jsup-zs8y d:2014-06-06T12:19:28.000Z t:office=President t:first_name=Barack t:phone="(202) 456-1414" t:website=http://whitehouse.gov t:last_name=Obama t:election_id=110612 t:jurisdiction=U.S. m:term=4

series e:jsup-zs8y d:2014-06-06T12:19:28.000Z t:office="Vice President" t:first_name=Joe t:phone="(202) 456-1414" t:website=http://whitehouse.gov t:last_name=Biden t:election_id=110612 t:jurisdiction=U.S. m:term=4

series e:jsup-zs8y d:2014-06-06T12:19:28.000Z t:office=Senator t:first_name=Richard t:phone="(202) 224-2152" t:website=http://durbin.senate.gov t:middle_name=J. t:last_name=Durbin t:election_id=110408 t:jurisdiction=U.S. m:term=6
```

## Meta Commands

```ls
metric m:term p:integer l:Term t:dataTypeName=number

metric m:phone2 p:long l:Phone2 t:dataTypeName=number

metric m:fax2 p:long l:Fax2 t:dataTypeName=number

entity e:jsup-zs8y l:"County Clerk --  Directory Of Elected Ofiicials - via Jurisdiction" t:attribution="Cook County Clerk" t:url=https://datacatalog.cookcountyil.gov/api/views/jsup-zs8y

property e:jsup-zs8y t:meta.view v:id=jsup-zs8y v:averageRating=0 v:name="County Clerk --  Directory Of Elected Ofiicials - via Jurisdiction" v:attribution="Cook County Clerk"

property e:jsup-zs8y t:meta.view.license v:name="Public Domain"

property e:jsup-zs8y t:meta.view.owner v:id=d4g2-kc7i v:screenName="Cook County Webmaster" v:displayName="Cook County Webmaster"

property e:jsup-zs8y t:meta.view.tableauthor v:id=d4g2-kc7i v:screenName="Cook County Webmaster" v:roleName=administrator v:displayName="Cook County Webmaster"
```

## Top Records

```ls
| :updated_at | office                                  | jurisdiction               | first_name | middle_name | last_name | term | election_id | phone          | fax | website                             | email              | phone2 | fax2 | website2     | email2 | 
| =========== | ======================================= | ========================== | ========== | =========== | ========= | ==== | =========== | ============== | === | =================================== | ================== | ====== | ==== | ============ | ====== | 
| 1402057168  | President                               | U.S.                       | Barack     |             | Obama     | 4    | 110612      | (202) 456-1414 |     | [http://whitehouse.gov, null]       |                    |        |      | [null, null] |        | 
| 1402057168  | Vice President                          | U.S.                       | Joe        |             | Biden     | 4    | 110612      | (202) 456-1414 |     | [http://whitehouse.gov, null]       |                    |        |      | [null, null] |        | 
| 1402057168  | Senator                                 | U.S.                       | Richard    | J.          | Durbin    | 6    | 110408      | (202) 224-2152 |     | [http://durbin.senate.gov, null]    |                    |        |      | [null, null] |        | 
| 1402057168  | Senator                                 | U.S.                       | Mark       |             | Kirk      | 6    | 110210      | (202) 224-2854 |     | [http://kirk.senate.gov, null]      |                    |        |      | [null, null] |        | 
| 1402057168  | Representative                          | 1st Congressional District | Bobby      |             | Rush      | 2    | 110612      | (202) 225-4372 |     | [http://rush.house.gov, null]       |                    |        |      | [null, null] |        | 
| 1402057168  | Democratic State Central Committeeman   | 1st Congressional District | Bobby      |             | Rush      | 4    | 31814       | (217) 546-7404 |     | [http://ildems.com, null]           | contact@ildems.com |        |      | [null, null] |        | 
| 1402057168  | Democratic State Central Committeewoman | 1st Congressional District | Michelle   | A.          | Harris    | 4    | 31814       | (217) 546-7404 |     | [http://ildems.com, null]           | contact@ildems.com |        |      | [null, null] |        | 
| 1402057168  | Representative                          | 2nd Congressional District | Robin      |             | Kelly     | 2    | 40913       | (202) 225-0773 |     | [http://robinkelly.house.gov, null] |                    |        |      | [null, null] |        | 
| 1402057168  | Democratic State Central Committeeman   | 2nd Congressional District | Al         |             | Riley     | 4    | 31814       | (217) 546-7404 |     | [http://ildems.com, null]           | contact@ildems.com |        |      | [null, null] |        | 
| 1402057168  | Democratic State Central Committeewoman | 2nd Congressional District | Carrie     |             | Austin    | 4    | 31814       | (217) 546-7404 |     | [http://ildems.com, null]           | contact@ildems.com |        |      | [null, null] |        | 
```