# King County Safety Video Library

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/king-county-safety-video-library-688a5) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/25bp-irus) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/25bp-irus/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/25bp-irus/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | 25bp-irus |
| Name | King County Safety Video Library |
| Attribution | King County Safety & Claims |
| Category | Operations |
| Tags | video, dvd, training, safety |
| Created | 2014-12-31T19:00:33Z |
| Publication Date | 2014-12-31T20:07:47Z |

## Description

Lending library for King County employees only

## Columns

```ls
| Included | Schema Type | Field Name  | Name       | Data Type | Render Type |
| ======== | =========== | =========== | ========== | ========= | =========== |
| No       | time        | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag  | kc_number   | KC Number  | text      | number      |
| Yes      | series tag  | title       | Title      | text      | text        |
| Yes      | series tag  | producer    | Producer   | text      | text        |
| Yes      | series tag  | length      | Length     | text      | text        |
| Yes      | series tag  | format      | Format     | text      | text        |
| Yes      | series tag  | notes       | Notes      | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:25bp-irus d:2014-12-31T12:03:23.000Z t:title="Coaching the Experienced Driver" t:length=? t:producer="FLI Learning Systems" t:format=VHS t:kc_number=236 m:row_number.25bp-irus=1

series e:25bp-irus d:2014-12-31T12:03:23.000Z t:title="Taking Control: The Workers? Compensation _ Return to Work Connection" t:length="27 minutes" t:producer="Milt Wright & Associates" t:format=VHS t:notes="Reserved for Safety Class" t:kc_number=235 m:row_number.25bp-irus=2

series e:25bp-irus d:2014-12-31T12:03:23.000Z t:title="Speed Sharp Chain Saw Ginder" t:length="35 minutes" t:producer="Foley Belsaw Company" t:format=VHS t:kc_number=234 m:row_number.25bp-irus=3
```

## Meta Commands

```ls
metric m:row_number.25bp-irus p:long l:"Row Number"

entity e:25bp-irus l:"King County Safety Video Library" t:attribution="King County Safety & Claims" t:url=https://data.kingcounty.gov/api/views/25bp-irus

property e:25bp-irus t:meta.view v:id=25bp-irus v:category=Operations v:attributionLink=http://kingcounty.gov/employees v:averageRating=0 v:name="King County Safety Video Library" v:attribution="King County Safety & Claims"

property e:25bp-irus t:meta.view.license v:name="Public Domain"

property e:25bp-irus t:meta.view.owner v:id=8hw3-qki5 v:screenName="Tammy Harris" v:displayName="Tammy Harris"

property e:25bp-irus t:meta.view.tableauthor v:id=8hw3-qki5 v:screenName="Tammy Harris" v:roleName=publisher v:displayName="Tammy Harris"
```

## Top Records

```ls
| :updated_at | kc_number | title                                                                 | producer                    | length     | format | notes                     | 
| =========== | ========= | ===================================================================== | =========================== | ========== | ====== | ========================= | 
| 1420027403  | 236       | Coaching the Experienced Driver                                       | FLI Learning Systems        | ?          | VHS    |                           | 
| 1420027403  | 235       | Taking Control: The Workers? Compensation _ Return to Work Connection | Milt Wright & Associates    | 27 minutes | VHS    | Reserved for Safety Class | 
| 1420027403  | 234       | Speed Sharp Chain Saw Ginder                                          | Foley Belsaw Company        | 35 minutes | VHS    |                           | 
| 1420027403  | 217       | Back Injury Prevention: You?re in Control                             | Summit Training Source      | 17 minutes | VHS    |                           | 
| 1420027403  | 216       | Personal Protective Equipment                                         | Summit Training Source      | 12 minutes | VHS    |                           | 
| 1420027403  | 215       | Fire Extinguishers                                                    | Valley Videos               | 6 minutes  | VHS    |                           | 
| 1420027403  | 203       | Almost Home: A Focus on Drowsy Driving                                | N?tl Road Safety Foundation | 18 minutes | VHS    |                           | 
| 1420027403  | 202       | NRSF Speed and Aggression Tool Kit                                    | N?tl Road Safety Foundation | 39 minutes | VHS    |                           | 
| 1420027403  | 201       | Meth Lab training video 4/21/03 at King Street Center                 | KCSO                        | 81 minutes | VHS    |                           | 
| 1420027403  | 200       | Meth Lab training video 4/21/03 at King Street Center                 | KCSO                        | 81 minutes | VHS    |                           | 
```