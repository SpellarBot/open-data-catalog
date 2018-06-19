# Automated external defibrillator Locations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/automated-external-defibrillator-locations-333ca) |
| Metadata | [Link](https://data.honolulu.gov/api/views/2swm-eusf) |
| Data: JSON | [100 Rows](https://data.honolulu.gov/api/views/2swm-eusf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.honolulu.gov/api/views/2swm-eusf/rows.csv?max_rows=100) |
| Host | data.honolulu.gov |
| Id | 2swm-eusf |
| Name | Automated external defibrillator Locations |
| Category | Location |
| Created | 2012-06-23T01:28:19Z |
| Publication Date | 2012-06-23T01:31:06Z |

## Columns

```ls
| Included | Schema Type    | Field Name   | Name          | Data Type | Render Type |
| ======== | ============== | ============ | ============= | ========= | =========== |
| No       | time           | :updated_at  | updated_at    | meta_data | meta_data   |
| Yes      | numeric metric | unit         | Unit          | number    | number      |
| Yes      | series tag     | locationname | LocationName  | text      | text        |
| Yes      | series tag     | loc_descrip  | Loc. Descrip. | text      | text        |
| Yes      | series tag     | hrs_op       | Hrs. Op.      | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:2swm-eusf d:2012-06-22T18:28:21.000Z t:hrs_op=24/7 t:loc_descrip="5th floor, on the wall directly across from the elevators." t:locationname="Airport Industrial Park" m:unit=1

series e:2swm-eusf d:2012-06-22T18:28:21.000Z t:hrs_op=24/7 t:loc_descrip="4th floor, on the wall directly across from the elevators." t:locationname="Airport Industrial Park" m:unit=2

series e:2swm-eusf d:2012-06-22T18:28:21.000Z t:hrs_op=24/7 t:loc_descrip="3rd floor, on the wall directly across from the elevators." t:locationname="Airport Industrial Park" m:unit=3
```

## Meta Commands

```ls
metric m:unit p:integer l:Unit t:dataTypeName=number

entity e:2swm-eusf l:"Automated external defibrillator Locations" t:url=https://data.honolulu.gov/api/views/2swm-eusf

property e:2swm-eusf t:meta.view v:id=2swm-eusf v:category=Location v:averageRating=0 v:name="Automated external defibrillator Locations"

property e:2swm-eusf t:meta.view.owner v:id=gcjf-354x v:screenName="Mick Thompson" v:displayName="Mick Thompson"

property e:2swm-eusf t:meta.view.tableauthor v:id=gcjf-354x v:screenName="Mick Thompson" v:displayName="Mick Thompson"
```

## Top Records

```ls
| :updated_at | unit | locationname            | loc_descrip                                                                                                                               | hrs_op | 
| =========== | ==== | ======================= | ========================================================================================================================================= | ====== | 
| 1340389701  | 1    | Airport Industrial Park | 5th floor, on the wall directly across from the elevators.                                                                                | 24/7   | 
| 1340389701  | 2    | Airport Industrial Park | 4th floor, on the wall directly across from the elevators.                                                                                | 24/7   | 
| 1340389701  | 3    | Airport Industrial Park | 3rd floor, on the wall directly across from the elevators.                                                                                | 24/7   | 
| 1340389701  | 4    | Airport Industrial Park | 2nd floor, on the wall directly across from the elevators.                                                                                | 24/7   | 
| 1340389701  | 5    | Airport Industrial Park | 1st floor, enter main doors, pass elevators on the right hand side going down the hall, turn right past the ATM, AED is on the right wall | 24/7   | 
| 1340389701  | 6    | Airport Industrial Park | C suites, top floor, right wall across from C315                                                                                          | 24/7   | 
| 1340389701  | 7    | Airport Industrial Park | B suites, down hallway on the left, across from B 245                                                                                     | 24/7   | 
| 1340389701  | 8    | Sheraton Waikiki        | Behind front desk                                                                                                                         | 24/7   | 
| 1340389701  | 9    | Sheraton Waikiki        | Infinity pool, on column near enterance                                                                                                   | 24/7   | 
| 1340389701  | 10   | Sheraton Waikiki        | Behind Helumoa pool desk                                                                                                                  | 24/7   | 
```