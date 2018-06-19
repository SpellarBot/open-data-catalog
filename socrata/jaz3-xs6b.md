# Report Card 4a Tax Visitor Expenditures

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/report-card-4a-tax-visitor-expenditures-73a4a) |
| Metadata | [Link](https://data.hawaii.gov/api/views/jaz3-xs6b) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/jaz3-xs6b/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/jaz3-xs6b/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | jaz3-xs6b |
| Name | Report Card 4a Tax Visitor Expenditures |
| Created | 2012-11-19T02:16:33Z |
| Publication Date | 2012-11-19T02:16:59Z |

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                 | Data Type | Render Type |
| ======== | ============== | ==================== | ==================== | ========= | =========== |
| Yes      | time           | year                 | Year                 | number    | text        |
| Yes      | numeric metric | visitor_expenditures | Visitor Expenditures | money     | money       |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:jaz3-xs6b d:1997-01-01T00:00:00.000Z m:visitor_expenditures=11520354

series e:jaz3-xs6b d:1998-01-01T00:00:00.000Z m:visitor_expenditures=11379923

series e:jaz3-xs6b d:1999-01-01T00:00:00.000Z m:visitor_expenditures=11380935
```

## Meta Commands

```ls
metric m:visitor_expenditures p:integer l:"Visitor Expenditures" t:dataTypeName=money

entity e:jaz3-xs6b l:"Report Card 4a Tax Visitor Expenditures" t:url=https://data.hawaii.gov/api/views/jaz3-xs6b

property e:jaz3-xs6b t:meta.view v:id=jaz3-xs6b v:averageRating=0 v:name="Report Card 4a Tax Visitor Expenditures"

property e:jaz3-xs6b t:meta.view.owner v:id=pvmv-89ja v:screenName="Daniel Nahoopii" v:displayName="Daniel Nahoopii"

property e:jaz3-xs6b t:meta.view.tableauthor v:id=pvmv-89ja v:screenName="Daniel Nahoopii" v:roleName=editor v:displayName="Daniel Nahoopii"
```

## Top Records

```ls
| year | visitor_expenditures | 
| ==== | ==================== | 
| 1997 | 11520354             | 
| 1998 | 11379923             | 
| 1999 | 11380935             | 
| 2000 | 12017698             | 
| 2001 | 10412234             | 
| 2002 | 11045549             | 
| 2003 | 11468264             | 
| 2004 | 12406828             | 
| 2005 | 13554608             | 
| 2006 | 14198372             | 
```