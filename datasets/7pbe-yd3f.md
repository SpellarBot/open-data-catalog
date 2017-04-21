# King County onsite employee flu vaccination clinics

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/king-county-onsite-employee-flu-vaccination-clinics-095eb) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/7pbe-yd3f) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/7pbe-yd3f/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/7pbe-yd3f/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | 7pbe-yd3f |
| Name | King County onsite employee flu vaccination clinics |
| Attribution | King County Employee Health & Well-Being |
| Category | Employees |
| Tags | shots, flu, influenza |
| Created | 2014-08-19T18:39:34Z |
| Publication Date | 2014-09-10T18:15:14Z |

## Description

King County workplace onsite flu vaccination clinics for King County employees

## Columns

```ls
| Included | Schema Type | Field Name | Name      | Data Type     | Render Type   |
| ======== | =========== | ========== | ========= | ============= | ============= |
| Yes      | series tag  | workplace  | Workplace | text          | text          |
| Yes      | time        | date       | Date      | calendar_date | calendar_date |
| Yes      | series tag  | hours      | Hours     | text          | text          |
| No       |             | address    | Address   | text          | text          |
| Yes      | series tag  | city       | City      | text          | text          |
| Yes      | series tag  | state      | State     | text          | text          |
| Yes      | series tag  | zip        | Zip       | text          | text          |
| Yes      | series tag  | room       | Room      | text          | text          |
| Yes      | series tag  | contact    | Contact   | text          | text          |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = address
```

## Data Commands

```ls
series e:7pbe-yd3f d:2014-10-01T00:00:00.000Z t:zip=98122 t:hours="11 a.m. - 1 p.m." t:state=WA t:workplace="Youth Services Center" t:contact="Crista Johnson
205-9426" t:room="50B in the lower Alder area" t:city=Seattle m:row_number.7pbe-yd3f=1

series e:7pbe-yd3f d:2014-10-02T00:00:00.000Z t:zip=98038 t:hours="1-3 p.m." t:state=WA t:workplace="Cedar Hills" t:contact="Annette Attianese
205-7143" t:room="Conference Rooms" t:city="Maple Valley" m:row_number.7pbe-yd3f=2

series e:7pbe-yd3f d:2014-10-22T00:00:00.000Z t:zip=98134 t:hours="2 - 4:30pm" t:state=WA t:workplace="Atlantic/Central Transit Base" t:contact="Kristy Hampton 684-2701; Lisa Dove 684-2778" t:room="2nd Floor Class Room" t:city=Seattle m:row_number.7pbe-yd3f=3
```

## Meta Commands

```ls
metric m:row_number.7pbe-yd3f p:long l:"Row Number"

entity e:7pbe-yd3f l:"King County onsite employee flu vaccination clinics" t:attribution="King County Employee Health & Well-Being" t:url=https://data.kingcounty.gov/api/views/7pbe-yd3f

property e:7pbe-yd3f t:meta.view v:id=7pbe-yd3f v:category=Employees v:attributionLink=http://www.kingcounty.gov/healthyincentives v:averageRating=0 v:name="King County onsite employee flu vaccination clinics" v:attribution="King County Employee Health & Well-Being"

property e:7pbe-yd3f t:meta.view.license v:name="Public Domain"

property e:7pbe-yd3f t:meta.view.owner v:id=esdd-3pma v:screenName=Caroline v:displayName=Caroline

property e:7pbe-yd3f t:meta.view.tableauthor v:id=esdd-3pma v:screenName=Caroline v:roleName=publisher v:displayName=Caroline
```

## Top Records

```ls
| workplace                     | date                | hours            | address               | city         | state | zip   | room                        | contact                                     | 
| ============================= | =================== | ================ | ===================== | ============ | ===== | ===== | =========================== | =========================================== | 
| Youth Services Center         | 2014-10-01T00:00:00 | 11 a.m. - 1 p.m. | 1211 E. Alder St      | Seattle      | WA    | 98122 | 50B in the lower Alder area | Crista Johnson 205-9426                     | 
| Cedar Hills                   | 2014-10-02T00:00:00 | 1-3 p.m.         | 16645 228th Ave SE    | Maple Valley | WA    | 98038 | Conference Rooms            | Annette Attianese 205-7143                  | 
| Atlantic/Central Transit Base | 2014-10-22T00:00:00 | 2 - 4:30pm       | 1500 6th Ave. South   | Seattle      | WA    | 98134 | 2nd Floor Class Room        | Kristy Hampton 684-2701; Lisa Dove 684-2778 | 
| Brightwater                   | 2014-10-15T00:00:00 | 7-8 a.m.         | 22505 St. Rt 9 SE     | Woodinville  | WA    | 98072 | "Q" room                    | Pat Stout 263-9465                          | 
| Ryerson Transit Base          | 2014-09-29T00:00:00 | 5:30 - 9:30 a.m. | 1220 4th Ave S.       | Seattle      | WA    | 98134 | Classroom 203 A             | Monique Stream 477-7293                     | 
| Renton Roads                  | 2014-10-16T00:00:00 | 6:30am- 10 am    | 155 Monroe Ave NE     | Renton       | WA    | 98056 | Building C, Gabion Room     | Mary Bass 296-8136                          | 
| Airport                       | 2014-10-29T00:00:00 | noon - 1 pm      | 7277 Perimeter Road S | Seattle      | WA    | 98108 | Airport Terminal, Room 110  | Julie Long 296-7454                         | 
| King Street Center            | 2014-10-07T00:00:00 | 8 am - 4 pm      | 201 S. Jackson St.    | Seattle      | WA    | 98104 | 8th Floor Conference Center | Chris Zanassi 296-4389                      | 
| Bellevue Base                 | 2013-10-08T00:00:00 | 2 - 4:30pm       | 1790 124th Ave NE     | Bellevue     | WA    | 98005 | Classrooms 1&2              | Janice Larson 477-7839                      | 
| Atlantic/Central Transit Base | 2014-10-14T00:00:00 | 5:30 - 9:30 a.m. | 1500 6th Ave. South   | Seattle      | WA    | 98134 | 2nd Floor Class Room        | Kristy Hampton 684-2701; Lisa Dove 684-2778 | 
```