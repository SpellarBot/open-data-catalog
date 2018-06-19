# Cook County Commissioner Information

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cook-county-commissioner-information-b819d) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/jsye-5ha4) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/jsye-5ha4/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/jsye-5ha4/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | jsye-5ha4 |
| Name | Cook County Commissioner Information |
| Attribution | Cook County Board of Commissioners |
| Category | Finance & Administration |
| Tags | commissioners |
| Created | 2013-07-15T14:36:24Z |
| Publication Date | 2015-07-23T16:13:07Z |

## Description

Information updated on July 23, 2015.

## Columns

```ls
| Included | Schema Type    | Field Name    | Name          | Data Type     | Render Type   |
| ======== | ============== | ============= | ============= | ============= | ============= |
| Yes      | series tag     | office        | Office        | text          | text          |
| Yes      | series tag     | district      | District      | text          | text          |
| Yes      | series tag     | jurisdiction  | Jurisdiction  | text          | text          |
| Yes      | series tag     | first_name    | First Name    | text          | text          |
| Yes      | series tag     | middle_name   | Middle Name   | text          | text          |
| Yes      | series tag     | last_name     | Last Name     | text          | text          |
| Yes      | time           | last_elected  | Last Elected  | calendar_date | calendar_date |
| Yes      | numeric metric | next_election | Next Election | number        | number        |
| Yes      | numeric metric | term          | Term          | number        | number        |
| Yes      | series tag     | appointed     | Appointed     | text          | text          |
| Yes      | series tag     | phone1        | Phone1        | text          | text          |
| Yes      | series tag     | fax1          | Fax1          | text          | text          |
| Yes      | series tag     | email1        | Email1        | email         | email         |
| Yes      | series tag     | url1          | Url1          | url           | url           |
| Yes      | series tag     | phone2        | Phone2        | text          | text          |
| Yes      | series tag     | fax2          | Fax2          | text          | text          |
| Yes      | series tag     | email2        | Email2        | email         | email         |
| Yes      | series tag     | url2          | Url2          | url           | url           |
```

## Time Field

```ls
Value = last_elected
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:jsye-5ha4 d:2014-11-04T00:00:00.000Z t:office=Commissioner t:url1=http://www.cookcountyil.gov/robert-steele/ t:url2=http://www.robertsteele.org t:middle_name=B. t:phone2="(773) 722-0140" t:jurisdiction="Cook County Board" t:phone1="(312) 603-3019" t:email1=Robert.Steele@cookcountyil.gov t:appointed=FALSE t:first_name=Robert t:last_name=Steele t:fax2="(773) 722-0145" t:fax1="(312) 603-4055" t:district=2nd m:term=4 m:next_election=2018

series e:jsye-5ha4 d:2014-11-04T00:00:00.000Z t:appointed=FALSE t:office=Commissioner t:first_name=Jerry t:url1=http://www.cookcountyil.gov/jerry-iceman-butler/ t:last_name=Butler t:fax1="(312) 603-5671" t:jurisdiction="Cook County Board" t:district=3rd t:email1=jerry.butler@cookcountyil.gov t:phone1="(312) 603-6391" m:term=4 m:next_election=2018

series e:jsye-5ha4 d:2014-11-04T00:00:00.000Z t:appointed=FALSE t:office=Commissioner t:first_name=Stanley t:url1=http://www.cookcountyil.gov/stanley-moore-4th/ t:url2=http://www.commissionermoore.com/ t:last_name=Moore t:phone2="(773) 783-2412" t:jurisdiction="Cook County Board" t:district=4th t:email1=Stanley.moore2@cookcountyil.gov t:phone1="(312) 603-2065" m:term=4 m:next_election=2018
```

## Meta Commands

```ls
metric m:next_election p:integer l:"Next Election" t:dataTypeName=number

metric m:term p:integer l:Term t:dataTypeName=number

entity e:jsye-5ha4 l:"Cook County Commissioner Information" t:attribution="Cook County Board of Commissioners" t:url=https://datacatalog.cookcountyil.gov/api/views/jsye-5ha4

property e:jsye-5ha4 t:meta.view v:id=jsye-5ha4 v:category="Finance & Administration" v:attributionLink=http://blog.cookcountygov.com/board-of-commissioners/ v:averageRating=0 v:name="Cook County Commissioner Information" v:attribution="Cook County Board of Commissioners"

property e:jsye-5ha4 t:meta.view.license v:name="Public Domain"

property e:jsye-5ha4 t:meta.view.owner v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:jsye-5ha4 t:meta.view.tableauthor v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
```

## Top Records

```ls
| office       | district | jurisdiction      | first_name | middle_name | last_name | last_elected        | next_election | term | appointed | phone1         | fax1           | email1                          | url1                                                          | phone2         | fax2           | email2 | url2                                                                | 
| ============ | ======== | ================= | ========== | =========== | ========= | =================== | ============= | ==== | ========= | ============== | ============== | =============================== | ============================================================= | ============== | ============== | ====== | =================================================================== | 
| Commissioner | 2nd      | Cook County Board | Robert     | B.          | Steele    | 2014-11-04T00:00:00 | 2018          | 4    | FALSE     | (312) 603-3019 | (312) 603-4055 | Robert.Steele@cookcountyil.gov  | [http://www.cookcountyil.gov/robert-steele/, null]            | (773) 722-0140 | (773) 722-0145 |        | [http://www.robertsteele.org, null]                                 | 
| Commissioner | 3rd      | Cook County Board | Jerry      |             | Butler    | 2014-11-04T00:00:00 | 2018          | 4    | FALSE     | (312) 603-6391 | (312) 603-5671 | jerry.butler@cookcountyil.gov   | [http://www.cookcountyil.gov/jerry-iceman-butler/, null]      |                |                |        | [null, null]                                                        | 
| Commissioner | 4th      | Cook County Board | Stanley    |             | Moore     | 2014-11-04T00:00:00 | 2018          | 4    | FALSE     | (312) 603-2065 |                | Stanley.moore2@cookcountyil.gov | [http://www.cookcountyil.gov/stanley-moore-4th/, null]        | (773) 783-2412 |                |        | [http://www.commissionermoore.com/, null]                           | 
| Commissioner | 5th      | Cook County Board | Deborah    |             | Sims      | 2014-11-04T00:00:00 | 2018          | 4    | FALSE     | (312) 603-6381 | (312) 603-2583 | deborah.sims@cookcountyil.gov   | [http://www.cookcountyil.gov/deborah-sims-5th/, null]         | (708) 371-4251 | (708) 371-4376 |        | [null, null]                                                        | 
| Commissioner | 6th      | Cook County Board | Joan       | Patricia    | Murphy    | 2014-11-04T00:00:00 | 2018          | 4    | FALSE     | (312) 603-4216 | (312) 603-3693 | joan.murphy@cookcountyil.gov    | [http://www.cookcountyil.gov/joan-patricia-murphy-6th/, null] | (708) 389-2125 | (708) 389-2240 |        | [null, null]                                                        | 
| Commissioner | 7th      | Cook County Board | Jesus      | G.          | Garcia    | 2014-11-04T00:00:00 | 2018          | 4    | FALSE     | (312) 603-5443 | (312) 603-3759 | jesus.garcia@cookcountyil.gov   | [http://www.cookcountyil.gov/jesus-g-garcia-7th/, null]       | (773) 376-2700 | (773) 376-3320 |        | [null, null]                                                        | 
| Commissioner | 9th      | Cook County Board | Peter      | N.          | Silvestri | 2014-11-04T00:00:00 | 2018          | 4    | FALSE     | (312) 603-4393 | (312) 603-1154 | cookcty9@aol.com                | [http://www.cookcountyil.gov/peter-n-silvestri-9th/, null]    | (773) 444-0346 | (773) 444-0373 |        | [http://www.petersilvestri.com, null]                               | 
| Commissioner | 10th     | Cook County Board | Bridget    |             | Gainer    | 2014-11-04T00:00:00 | 2018          | 4    | FALSE     | (312) 603-4210 | (312) 603-3695 | Bridget@bridgetgainer.com       | [http://www.cookcountyil.gov/bridget-gainer-10th/, null]      | (773) 561-1010 |                |        | [http://bridgetgainer.com/, null]                                   | 
| Commissioner | 11th     | Cook County Board | John       | P.          | Daley     | 2014-11-04T00:00:00 | 2018          | 4    | FALSE     | (312) 603-4400 | (312) 603-6688 | john.daley@cookcountyil.gov     | [http://www.cookcountyil.gov/john-p-daley-11th/, null]        |                |                |        | [https://www.facebook.com/pages/John-P-Daley/169143929764881, null] | 
| Commissioner | 12th     | Cook County Board | John       | A.          | Fritchey  | 2014-11-04T00:00:00 | 2018          | 4    | FALSE     | (312) 603-6380 | (312) 603-1265 | commish@fritchey.com            | [http://www.cookcountyil.gov/john-a-fritchey-12th/, null]     | (773) 871-4000 | (773) 423-0392 |        | [http://www.fritchey.com/, null]                                    | 
```