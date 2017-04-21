# Care 4 Kids Expenditures By Town CY 2011

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/care-4-kids-expenditures-by-town-cy-2011) |
| Metadata | [Link](https://data.ct.gov/api/views/pqd2-9uud) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/pqd2-9uud/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/pqd2-9uud/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | pqd2-9uud |
| Name | Care 4 Kids Expenditures By Town CY 2011 |
| Attribution | Office of Early Childhood |
| Tags | ct, care 4 kids, education |
| Created | 2014-03-10T13:53:55Z |
| Publication Date | 2014-03-10T13:57:07Z |

## Description

Care 4 Kids expenditures by Town for Calendar Year 2011. Care 4 Kids helps low to moderate income families in Connecticut pay for child care costs. This program is sponsored by the State of Connecticut?s Department of Social Services (also called DSS

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                | Data Type | Render Type |
| ======== | ============== | ======================= | =================== | ========= | =========== |
| Yes      | series tag     | connecticut_care_4_kids | Town                | text      | text        |
| Yes      | numeric metric | none                    | Expendiures CY 2011 | money     | money       |
```

## Time Field

```ls
Value = 2011
Format & Zone = yyyy
```

## Data Commands

```ls
series e:pqd2-9uud d:2011-01-01T00:00:00.000Z t:connecticut_care_4_kids=ABINGTON m:none=0

series e:pqd2-9uud d:2011-01-01T00:00:00.000Z t:connecticut_care_4_kids=AMSTON m:none=33251.96

series e:pqd2-9uud d:2011-01-01T00:00:00.000Z t:connecticut_care_4_kids=ANDOVER m:none=16665.35
```

## Meta Commands

```ls
metric m:none p:double l:"Expendiures CY 2011" d:"Expenditures in Calendar Year 2011" t:dataTypeName=money

entity e:pqd2-9uud l:"Care 4 Kids Expenditures By Town CY 2011" t:attribution="Office of Early Childhood" t:url=https://data.ct.gov/api/views/pqd2-9uud

property e:pqd2-9uud t:meta.view v:id=pqd2-9uud v:attributionLink=http://www.ctcare4kids.com/ v:averageRating=0 v:name="Care 4 Kids Expenditures By Town CY 2011" v:attribution="Office of Early Childhood"

property e:pqd2-9uud t:meta.view.license v:name="Public Domain"

property e:pqd2-9uud t:meta.view.owner v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"

property e:pqd2-9uud t:meta.view.tableauthor v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:roleName=administrator v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"
```

## Top Records

```ls
| connecticut_care_4_kids | none      | 
| ======================= | ========= | 
| ABINGTON                | 0.00      | 
| AMSTON                  | 33251.96  | 
| ANDOVER                 | 16665.35  | 
| ANSONIA                 | 777697.82 | 
| ASHFORD                 | 26025.78  | 
| AVON                    | 97802.00  | 
| BALTIC                  | 72050.96  | 
| BARKHAMSTED             | 10511.97  | 
| BEACON FALLS            | 25118.25  | 
| BERLIN                  | 184486.58 | 
```