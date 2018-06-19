# Lead Supervisor Licensees

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/lead-supervisor-licensees) |
| Metadata | [Link](https://data.illinois.gov/api/views/anwm-88cx) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/anwm-88cx/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/anwm-88cx/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | anwm-88cx |
| Name | Lead Supervisor Licensees |
| Attribution | IDPH - Division of Environmental Health |
| Category | Public Health |
| Tags | lead, supervisor |
| Created | 2015-03-04T15:25:34Z |
| Publication Date | 2016-06-28T19:47:49Z |

## Description

This list contains Lead Supervisor licensees with their license expiration date and employer information. last updated June 2016

## Columns

```ls
| Included | Schema Type    | Field Name       | Name               | Data Type     | Render Type   |
| ======== | ============== | ================ | ================== | ============= | ============= |
| Yes      | series tag     | last             | Last Name          | text          | text          |
| Yes      | series tag     | first_mid        | First Mid          | text          | text          |
| No       |                | address          | Address            | text          | text          |
| Yes      | series tag     | homecity         | City               | text          | text          |
| Yes      | series tag     | state            | State              | text          | text          |
| Yes      | series tag     | homezip          | Zip                | text          | text          |
| Yes      | series tag     | homecounty       | County             | text          | text          |
| Yes      | series tag     | phone            | Phone              | text          | text          |
| Yes      | time           | sexpire          | License Expiration | calendar_date | calendar_date |
| Yes      | series tag     | ename            | Employer Name      | text          | text          |
| No       |                | employer_address | Employer Address   | text          | text          |
| Yes      | series tag     | employer_city    | Employer City      | text          | text          |
| Yes      | series tag     | employer_zip     | Employer Zip       | text          | text          |
| Yes      | numeric metric | employer_state   | Employer State     | number        | text          |
| Yes      | series tag     | employer_phone   | Employer Phone     | phone         | phone         |
```

## Time Field

```ls
Value = sexpire
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = address,employer_address
```

## Data Commands

```ls
series e:anwm-88cx d:2017-03-31T00:00:00.000Z t:phone=(773)-203-3318 t:phone_number=NA t:first_mid=Rafael t:employer_zip=IL t:last=Abrego t:ename="Abrego's General Contractors Inc" t:state=IL t:homecity=Chicago t:homecounty=Cook t:homezip=60623 t:employer_city=Chicago m:employer_state=60623

series e:anwm-88cx d:2017-03-31T00:00:00.000Z t:phone="(630) 903-9846" t:phone_number=NA t:first_mid="Jose L" t:employer_zip=IL t:last=Arellano t:ename="The Luse Companies" t:state=IL t:homecity="Oak Forest" t:homecounty=Cook t:homezip=60452 t:employer_city=Aurora m:employer_state=60504

series e:anwm-88cx d:2016-03-31T00:00:00.000Z t:phone=NA t:phone_number=NA t:first_mid="David L" t:employer_zip=IL t:last=Askins t:ename="R & A Construction" t:state=IL t:homecity=Shelbyville t:homecounty=Shelby t:homezip=62565 t:employer_city=Shelbyville m:employer_state=62565
```

## Meta Commands

```ls
metric m:employer_state p:integer l:"Employer State" t:dataTypeName=number

entity e:anwm-88cx l:"Lead Supervisor Licensees" t:attribution="IDPH - Division of Environmental Health" t:url=https://data.illinois.gov/api/views/anwm-88cx

property e:anwm-88cx t:meta.view v:id=anwm-88cx v:category="Public Health" v:attributionLink=http://dph.illinois.gov/topics-services/environmental-health-protection/lead-poisoning-prevention v:averageRating=0 v:name="Lead Supervisor Licensees" v:attribution="IDPH - Division of Environmental Health"

property e:anwm-88cx t:meta.view.license v:name="Public Domain"

property e:anwm-88cx t:meta.view.owner v:id=6dyi-26tm v:screenName="ken mccann" v:displayName="ken mccann"

property e:anwm-88cx t:meta.view.tableauthor v:id=6dyi-26tm v:screenName="ken mccann" v:roleName=publisher v:displayName="ken mccann"
```

## Top Records

```ls
| last     | first_mid     | address               | homecity    | state | homezip | homecounty  | phone          | sexpire             | ename                            | employer_address   | employer_city | employer_zip | employer_state | employer_phone         | 
| ======== | ============= | ===================== | =========== | ===== | ======= | =========== | ============== | =================== | ================================ | ================== | ============= | ============ | ============== | ====================== | 
| Abrego   | Rafael        | 2717 South Keeler Ave | Chicago     | IL    | 60623   | Cook        | (773)-203-3318 | 2017-03-31T00:00:00 | Abrego's General Contractors Inc | NA                 | Chicago       | IL           | 60623          | [NA, null]             | 
| Arellano | Jose L        | 4324 Barry Lane       | Oak Forest  | IL    | 60452   | Cook        | (630) 903-9846 | 2017-03-31T00:00:00 | The Luse Companies               | NA                 | Aurora        | IL           | 60504          | [NA, null]             | 
| Arreguin | Raul          | 2619 17th St.         | East Moline | IL    | 61244   | Rock Island | (309) 738-0493 | 2016-03-31T00:00:00 |                                  | NA                 |               |              |                | [NA, null]             | 
| Askins   | David L       | NA                    | Shelbyville | IL    | 62565   | Shelby      | NA             | 2016-03-31T00:00:00 | R & A Construction               | NA                 | Shelbyville   | IL           | 62565          | [NA, null]             | 
| Aydt     | Symantha C.N. | NA                    | Decatur     | IL    | 62521   | Macon       | NA             | 2017-03-31T00:00:00 | U of I                           | 504 E. Armory Ave. | Champaign     | IL           | 61820          | [(217) 333-0640, null] | 
| Babcock  | Paul W        | NA                    | Chicago     | IL    | 60654   | Cook        | NA             | 2016-03-31T00:00:00 |                                  |                    |               |              |                | [null, null]           | 
| Bailey   | Don P         | NA                    | Dolton      | IL    | 60419   | Cook        | NA             | 2017-03-31T00:00:00 | D.P.B. Abatement Services        | P.O. Box 512       | Dolton        | IL           | 60419          | [7738585170, null]     | 
| Bandy    | William C     | NA                    | Eldred      | IL    | 62027   | Greene      | NA             | 2017-03-31T00:00:00 | General Waste Services, Inc.     | NA                 | Alton         | IL           | 62002          | [NA, null]             | 
| Bangert  | Gary L        | NA                    | Chicago     | IL    | 60631   | Cook        | NA             | 2017-03-31T00:00:00 | Gary Bangert                     | 6213 N. Canfield   | Chicago       | IL           | 60631          | [7734437682, null]     | 
| Barrett  | Wendell L     | NA                    | Decatur     | IL    | 62522   | Macon       | NA             | 2017-03-31T00:00:00 | D & O Contractors Inc            | NA                 | Decatur       | IL           | 62526          | [NA, null]             | 
```