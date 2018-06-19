# Battery Drop Off Locations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/battery-drop-off-locations) |
| Metadata | [Link](https://data.austintexas.gov/api/views/pdfd-8tju) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/pdfd-8tju/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/pdfd-8tju/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | pdfd-8tju |
| Name | Battery Drop Off Locations |
| Tags | battery, drop off, arr, hazardous waste |
| Created | 2015-07-30T23:11:29Z |
| Publication Date | 2015-07-30T23:15:47Z |

## Description

This is a list of battery drop off locations.  Only batteries will be accepted at these locations.  DO NOT put any other items in bags with batteries.  These locations are not equipped to handle other types of waste.  *Please call first to make sure the location is actively participating in the program.  Locations change often.

## Columns

```ls
| Included | Schema Type | Field Name  | Name       | Data Type | Render Type |
| ======== | =========== | =========== | ========== | ========= | =========== |
| No       | time        | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag  | business    | Business   | text      | text        |
| Yes      | series tag  | zip_code    | Zip Code   | text      | number      |
| Yes      | series tag  | phone       | Phone #    | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:pdfd-8tju d:2015-07-30T16:11:35.000Z t:phone=258-6944 t:zip_code=78613 t:business="Radio Shack" m:row_number.pdfd-8tju=1

series e:pdfd-8tju d:2015-07-30T16:11:35.000Z t:phone=476-3977 t:zip_code=78701 t:business="Wolf Camera+Video" m:row_number.pdfd-8tju=2

series e:pdfd-8tju d:2015-07-30T16:11:35.000Z t:phone=478-9120 t:zip_code=78703 t:business="Tarrytown Pharmacy" m:row_number.pdfd-8tju=3
```

## Meta Commands

```ls
metric m:row_number.pdfd-8tju p:long l:"Row Number"

entity e:pdfd-8tju l:"Battery Drop Off Locations" t:url=https://data.austintexas.gov/api/views/pdfd-8tju

property e:pdfd-8tju t:meta.view v:id=pdfd-8tju v:averageRating=0 v:name="Battery Drop Off Locations"

property e:pdfd-8tju t:meta.view.owner v:id=nnyu-u79i v:screenName=erin.benoit@austintexas.gov v:displayName=erin.benoit@austintexas.gov

property e:pdfd-8tju t:meta.view.tableauthor v:id=nnyu-u79i v:screenName=erin.benoit@austintexas.gov v:roleName=editor v:displayName=erin.benoit@austintexas.gov
```

## Top Records

```ls
| :updated_at | business                | zip_code | phone    | 
| =========== | ======================= | ======== | ======== | 
| 1438272695  | Radio Shack             | 78613    | 258-6944 | 
| 1438272695  | Wolf Camera+Video       | 78701    | 476-3977 | 
| 1438272695  | Tarrytown Pharmacy      | 78703    | 478-9120 | 
| 1438272695  | Whole Earth Provision   | 78703    | 476-1414 | 
| 1438272695  | Whole Foods             | 78703    | 476-1206 | 
| 1438272695  | Batteries Plus          | 78704    | 416-1191 | 
| 1438272695  | Camera CoOp             | 78704    | 804-2667 | 
| 1438272695  | Radio Shack             | 78704    | 441-0617 | 
| 1438272695  | Free Wheelin' Bike Shop | 78705    | 477-6789 | 
| 1438272695  | Wolf Camera+Video       | 78717    | 331-2730 | 
```