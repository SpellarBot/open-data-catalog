# Care 4 Kids Expenditures By Town Calendar Year 2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/care-4-kids-expenditures-by-town-calendar-year-2012) |
| Metadata | [Link](https://data.ct.gov/api/views/dcwn-aa3d) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/dcwn-aa3d/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/dcwn-aa3d/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | dcwn-aa3d |
| Name | Care 4 Kids Expenditures By Town Calendar Year 2012 |
| Attribution | Office of Early Childhood |
| Category | Education |
| Tags | ct, care 4 kids, education |
| Created | 2014-03-10T14:00:40Z |
| Publication Date | 2014-03-10T14:03:31Z |

## Description

Care 4 Kids expenditures by Town for Calendar Year 2012. Care 4 Kids helps low to moderate income families in Connecticut pay for child care costs. This program is sponsored by the State of Connecticut?s Department of Social Services (also called DSS

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                 | Data Type | Render Type |
| ======== | ============== | ======================= | ==================== | ========= | =========== |
| Yes      | series tag     | connecticut_care_4_kids | Town                 | text      | text        |
| Yes      | numeric metric | none                    | Expenditures CY 2012 | money     | money       |
```

## Time Field

```ls
Value = 2012
Format & Zone = yyyy
```

## Data Commands

```ls
series e:dcwn-aa3d d:2012-01-01T00:00:00.000Z t:connecticut_care_4_kids=ABINGTON m:none=882.55

series e:dcwn-aa3d d:2012-01-01T00:00:00.000Z t:connecticut_care_4_kids=AMSTON m:none=28180.87

series e:dcwn-aa3d d:2012-01-01T00:00:00.000Z t:connecticut_care_4_kids=ANDOVER m:none=22033.59
```

## Meta Commands

```ls
metric m:none p:double l:"Expenditures CY 2012" t:dataTypeName=money

entity e:dcwn-aa3d l:"Care 4 Kids Expenditures By Town Calendar Year 2012" t:attribution="Office of Early Childhood" t:url=https://data.ct.gov/api/views/dcwn-aa3d

property e:dcwn-aa3d t:meta.view v:id=dcwn-aa3d v:category=Education v:attributionLink=http://www.ctcare4kids.com/ v:averageRating=0 v:name="Care 4 Kids Expenditures By Town Calendar Year 2012" v:attribution="Office of Early Childhood"

property e:dcwn-aa3d t:meta.view.license v:name="Public Domain"

property e:dcwn-aa3d t:meta.view.owner v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"

property e:dcwn-aa3d t:meta.view.tableauthor v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:roleName=administrator v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"
```

## Top Records

```ls
| connecticut_care_4_kids | none      | 
| ======================= | ========= | 
| ABINGTON                | 882.55    | 
| AMSTON                  | 28180.87  | 
| ANDOVER                 | 22033.59  | 
| ANSONIA                 | 935068.03 | 
| ASHFORD                 | 21919.78  | 
| AVON                    | 99745.33  | 
| BALTIC                  | 27995.28  | 
| BARKHAMSTED             | 18359.05  | 
| BEACON FALLS            | 27621.89  | 
| BERLIN                  | 273241.16 | 
```