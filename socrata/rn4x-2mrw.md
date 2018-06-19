# Forms of Municipal Goverment

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/forms-of-municipal-goverment) |
| Metadata | [Link](https://data.ct.gov/api/views/rn4x-2mrw) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/rn4x-2mrw/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/rn4x-2mrw/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | rn4x-2mrw |
| Name | Forms of Municipal Goverment |
| Attribution | Office of Policy and Management |
| Category | Government |
| Tags | towns, municipal, goverment, form, ceo |
| Created | 2016-01-19T19:18:06Z |
| Publication Date | 2016-01-19T19:22:04Z |

## Description

A listing of each of Connecticut's 169 municipalities indicating both the form of local goverment (such as Mayor-Council) and the Term in years for the Cheifl Elected Official

## Columns

```ls
| Included | Schema Type    | Field Name         | Name                | Data Type | Render Type |
| ======== | ============== | ================== | =================== | ========= | =========== |
| No       | time           | :updated_at        | updated_at          | meta_data | meta_data   |
| Yes      | series tag     | municipality       | MUNICIPALITY        | text      | text        |
| Yes      | numeric metric | term_of_ceo_years  | TERM OF CEO (YEARS) | number    | number      |
| Yes      | series tag     | form_of_government | FORM OF GOVERNMENT  | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:rn4x-2mrw d:2016-01-19T11:18:10.000Z t:form_of_government="SELECTMAN-TOWN MEETING" t:municipality=ANDOVER m:term_of_ceo_years=4

series e:rn4x-2mrw d:2016-01-19T11:18:10.000Z t:form_of_government=MAYOR-COUNCIL t:municipality=ANSONIA m:term_of_ceo_years=2

series e:rn4x-2mrw d:2016-01-19T11:18:10.000Z t:form_of_government="SELECTMAN-TOWN MEETING" t:municipality=ASHFORD m:term_of_ceo_years=2
```

## Meta Commands

```ls
metric m:term_of_ceo_years p:integer l:"TERM OF CEO (YEARS)" t:dataTypeName=number

entity e:rn4x-2mrw l:"Forms of Municipal Goverment" t:attribution="Office of Policy and Management" t:url=https://data.ct.gov/api/views/rn4x-2mrw

property e:rn4x-2mrw t:meta.view v:id=rn4x-2mrw v:category=Government v:attributionLink="http://www.ct.gov/opm/cwp/view.asp?a=2984&q=383170" v:averageRating=0 v:name="Forms of Municipal Goverment" v:attribution="Office of Policy and Management"

property e:rn4x-2mrw t:meta.view.license v:name="Public Domain"

property e:rn4x-2mrw t:meta.view.owner v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"

property e:rn4x-2mrw t:meta.view.tableauthor v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:roleName=administrator v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"
```

## Top Records

```ls
| :updated_at | municipality | term_of_ceo_years | form_of_government     | 
| =========== | ============ | ================= | ====================== | 
| 1453202290  | ANDOVER      | 4                 | SELECTMAN-TOWN MEETING | 
| 1453202290  | ANSONIA      | 2                 | MAYOR-COUNCIL          | 
| 1453202290  | ASHFORD      | 2                 | SELECTMAN-TOWN MEETING | 
| 1453202290  | AVON         | 2                 | COUNCIL-MANAGER        | 
| 1453202290  | BARKHAMSTED  | 2                 | SELECTMAN-TOWN MEETING | 
| 1453202290  | BEACON FALLS | 2                 | SELECTMAN-TOWN MEETING | 
| 1453202290  | BERLIN       | 2                 | COUNCIL-MANAGER        | 
| 1453202290  | BETHANY      | 2                 | SELECTMAN-TOWN MEETING | 
| 1453202290  | BETHEL       | 2                 | SELECTMAN-TOWN MEETING | 
| 1453202290  | BETHLEHEM    | 2                 | SELECTMAN-TOWN MEETING | 
```