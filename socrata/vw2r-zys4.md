# Cook County Directory of Elected Officials

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cook-county-directory-of-elected-officials-1a3e3) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/vw2r-zys4) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/vw2r-zys4/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/vw2r-zys4/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | vw2r-zys4 |
| Name | Cook County Directory of Elected Officials |
| Attribution | Cook County Clerk |
| Created | 2011-10-06T15:02:05Z |
| Publication Date | 2014-10-09T22:39:12Z |

## Description

Directory of elected officials covering Cook County as of May 2014.

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
| Yes      | series tag     | election_id  | Election ID  | text      | number      |
| No       |                | address      | Address      | text      | text        |
| Yes      | series tag     | city         | City         | text      | text        |
| Yes      | series tag     | state        | State        | text      | text        |
| Yes      | series tag     | zip          | Zip          | text      | text        |
| Yes      | series tag     | phone        | Phone        | phone     | phone       |
| Yes      | series tag     | fax          | Fax          | phone     | phone       |
| Yes      | series tag     | website      | Website      | url       | url         |
| Yes      | series tag     | email        | Email        | email     | email       |
| No       |                | address2     | Address2     | text      | text        |
| Yes      | series tag     | city2        | City2        | text      | text        |
| Yes      | series tag     | state2       | State2       | text      | text        |
| Yes      | series tag     | zip2         | Zip2         | text      | text        |
| Yes      | series tag     | phone2       | Phone2       | phone     | phone       |
| Yes      | series tag     | fax2         | Fax2         | phone     | phone       |
| Yes      | series tag     | website2     | Website2     | url       | url         |
| Yes      | series tag     | email2       | Email2       | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address,address2
```

## Data Commands

```ls
series e:vw2r-zys4 d:2014-06-06T12:50:44.000Z t:office=Supervisor t:first_name=Gary t:zip=60202 t:phone_number="(847) 475-4481" t:last_name=Gaspard t:election_id=40913 t:state=IL t:jurisdiction="Evanston Township" t:city=Evanston m:term=4

series e:vw2r-zys4 d:2014-06-06T12:50:46.000Z t:office=Trustee t:first_name=G.T. t:zip=60411 t:phone_number="(708) 757-0551" t:last_name=Coleman t:election_id=40511 t:state=IL t:jurisdiction="Ford Heights Public Library District" t:city="Ford Heights" m:term=4

series e:vw2r-zys4 d:2014-06-06T12:50:46.000Z t:office=Trustee t:first_name=Ilonka t:zip=60077 t:phone_number="(847) 933-8203" t:website=http://skokie.org t:last_name=Ulrich t:election_id=40913 t:state=IL t:jurisdiction="Village of Skokie" t:city=Skokie m:term=4
```

## Meta Commands

```ls
metric m:term p:integer l:Term t:dataTypeName=number

entity e:vw2r-zys4 l:"Cook County Directory of Elected Officials" t:attribution="Cook County Clerk" t:url=https://datacatalog.cookcountyil.gov/api/views/vw2r-zys4

property e:vw2r-zys4 t:meta.view v:id=vw2r-zys4 v:attributionLink=http://www.cookcountyclerk.com v:averageRating=0 v:name="Cook County Directory of Elected Officials" v:attribution="Cook County Clerk"

property e:vw2r-zys4 t:meta.view.license v:name="Public Domain"

property e:vw2r-zys4 t:meta.view.owner v:id=d4g2-kc7i v:screenName="Cook County Webmaster" v:displayName="Cook County Webmaster"

property e:vw2r-zys4 t:meta.view.tableauthor v:id=d4g2-kc7i v:screenName="Cook County Webmaster" v:roleName=administrator v:displayName="Cook County Webmaster"
```

## Top Records

```ls
| :updated_at | office                                  | jurisdiction                         | first_name | middle_name | last_name | term | election_id | address                            | city         | state | zip   | phone                  | fax                    | website                          | email              | address2                    | city2   | state2 | zip2  | phone2                 | fax2                   | website2     | email2 | 
| =========== | ======================================= | ==================================== | ========== | =========== | ========= | ==== | =========== | ================================== | ============ | ===== | ===== | ====================== | ====================== | ================================ | ================== | =========================== | ======= | ====== | ===== | ====================== | ====================== | ============ | ====== | 
| 1402059044  | Supervisor                              | Evanston Township                    | Gary       |             | Gaspard   | 4    | 40913       | 1910 Main St.                      | Evanston     | IL    | 60202 | [(847) 475-4481, null] | [null, null]           | [null, null]                     |                    |                             |         |        |       | [null, null]           | [null, null]           | [null, null] |        | 
| 1402059046  | Trustee                                 | Ford Heights Public Library District | G.T.       |             | Coleman   | 4    | 40511       | 800 E. 14th St.                    | Ford Heights | IL    | 60411 | [(708) 757-0551, null] | [null, null]           | [null, null]                     |                    |                             |         |        |       | [null, null]           | [null, null]           | [null, null] |        | 
| 1402059046  | Trustee                                 | Village of Skokie                    | Ilonka     |             | Ulrich    | 4    | 40913       | 5127 Oakton St.                    | Skokie       | IL    | 60077 | [(847) 933-8203, null] | [null, null]           | [http://skokie.org, null]        |                    |                             |         |        |       | [null, null]           | [null, null]           | [null, null] |        | 
| 1402059044  | President                               | U.S.                                 | Barack     |             | Obama     | 4    | 110612      | 1600 Pennsylvania Ave.             | Washington   | DC    | 20500 | [(202) 456-1414, null] | [(202) 456-2461, null] | [http://whitehouse.gov, null]    |                    |                             |         |        |       | [null, null]           | [null, null]           | [null, null] |        | 
| 1402059044  | Vice President                          | U.S.                                 | Joe        |             | Biden     | 4    | 110612      | 1600 Pennsylvania Ave.             | Washington   | DC    | 20500 | [(202) 456-1414, null] | [(202) 456-2461, null] | [http://whitehouse.gov, null]    |                    |                             |         |        |       | [null, null]           | [null, null]           | [null, null] |        | 
| 1402059044  | Senator                                 | U.S.                                 | Richard    | J.          | Durbin    | 6    | 110408      | 711 Hart Senate Office Building    | Washington   | DC    | 20510 | [(202) 224-2152, null] | [(202) 228-0400, null] | [http://durbin.senate.gov, null] |                    | 230 S. Dearborn, Suite 3892 | Chicago | IL     | 60604 | [(312) 353-4952, null] | [(312) 353-0150, null] | [null, null] |        | 
| 1402059044  | Senator                                 | U.S.                                 | Mark       |             | Kirk      | 6    | 110210      | 524 Hart Senate Office Building    | Washington   | DC    | 20510 | [(202) 224-2854, null] | [(202) 228-4611, null] | [http://kirk.senate.gov, null]   |                    | 230 S. Dearborn, Suite 3900 | Chicago | IL     | 60604 | [(312) 886-3506, null] | [(312) 886-2117, null] | [null, null] |        | 
| 1402059044  | Representative                          | 1st Congressional District           | Bobby      |             | Rush      | 2    | 110612      | 2268 Rayburn House Office Building | Washington   | DC    | 20515 | [(202) 225-4372, null] | [(202) 226-0333, null] | [http://rush.house.gov, null]    |                    | 700 E. 79th St.             | Chicago | IL     | 60619 | [(773) 224-6500, null] | [(773) 224-9624, null] | [null, null] |        | 
| 1402059044  | Democratic State Central Committeeman   | 1st Congressional District           | Bobby      |             | Rush      | 4    | 31814       | P.O. Box 518                       | Springfield  | IL    | 62705 | [(217) 546-7404, null] | [(217) 546-8847, null] | [http://ildems.com, null]        | contact@ildems.com |                             |         |        |       | [null, null]           | [null, null]           | [null, null] |        | 
| 1402059044  | Democratic State Central Committeewoman | 1st Congressional District           | Michelle   | A.          | Harris    | 4    | 31814       | P.O. Box 518                       | Springfield  | IL    | 62705 | [(217) 546-7404, null] | [(217) 546-8847, null] | [http://ildems.com, null]        | contact@ildems.com |                             |         |        |       | [null, null]           | [null, null]           | [null, null] |        | 
```