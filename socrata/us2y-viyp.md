# Grow Green Participant Locations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/grow-green-participant-locations) |
| Metadata | [Link](https://data.austintexas.gov/api/views/us2y-viyp) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/us2y-viyp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/us2y-viyp/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | us2y-viyp |
| Name | Grow Green Participant Locations |
| Attribution | City of Austin Watershed Protection Grow Green |
| Category | Environmental |
| Tags | grow green, native and adapted landscape plant guide, grow green participating locations |
| Created | 2015-04-23T16:10:06Z |
| Publication Date | 2015-04-24T13:11:09Z |

## Description

This is a list of nurseries and home improvement stores throughout Austin that have the Grow Green fact sheets and the Native and Adapted Landscape Plant Guides available.

## Columns

```ls
| Included | Schema Type | Field Name  | Name       | Data Type | Render Type |
| ======== | =========== | =========== | ========== | ========= | =========== |
| No       | time        | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag  | nursery     | Name       | text      | text        |
| Yes      | series tag  | phone       | Phone      | text      | text        |
| Yes      | series tag  | zip_code    | Zip Code   | text      | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:us2y-viyp d:2015-04-24T05:55:43.000Z t:phone=512-636-0003 t:zip_code=78748 t:nursery="Austin Texas Xeriscapes (Wholesale)" m:row_number.us2y-viyp=1

series e:us2y-viyp d:2015-04-24T05:56:29.000Z t:phone=512-972-1960 t:zip_code=78725 t:nursery="Austin Water Center for Environmental Research*" m:row_number.us2y-viyp=2

series e:us2y-viyp d:2015-04-24T06:00:14.000Z t:phone=512-328-3960 t:zip_code=78746 t:nursery="Breed & Co. (West)" m:row_number.us2y-viyp=3
```

## Meta Commands

```ls
metric m:row_number.us2y-viyp p:long l:"Row Number"

entity e:us2y-viyp l:"Grow Green Participant Locations" t:attribution="City of Austin Watershed Protection Grow Green" t:url=https://data.austintexas.gov/api/views/us2y-viyp

property e:us2y-viyp t:meta.view v:id=us2y-viyp v:category=Environmental v:attributionLink=http://www.growgreen.org v:averageRating=0 v:name="Grow Green Participant Locations" v:attribution="City of Austin Watershed Protection Grow Green"

property e:us2y-viyp t:meta.view.owner v:id=2z47-i38b v:screenName="Watershed Education" v:displayName="Watershed Education"

property e:us2y-viyp t:meta.view.tableauthor v:id=2z47-i38b v:screenName="Watershed Education" v:roleName=publisher v:displayName="Watershed Education"
```

## Top Records

```ls
| :updated_at | nursery                                          | phone        | zip_code | 
| =========== | ================================================ | ============ | ======== | 
| 1429854943  | Austin Texas Xeriscapes (Wholesale)              | 512-636-0003 | 78748    | 
| 1429854989  | Austin Water Center for Environmental Research*  | 512-972-1960 | 78725    | 
| 1429855214  | Breed & Co. (West)                               | 512-328-3960 | 78746    | 
| 1429855299  | City of Austin Development Assistance Center *   | 512-974-2550 | 78704    | 
| 1429855338  | COA Planning & Development Review - 4th Floor*   | 512-974-1876 | 78704    | 
| 1429855347  | COA Watershed Protection Department- 11th Floor* | 512-974-2550 | 78704    | 
| 1429855372  | Far South Growers (Wholesale)                    | 512-291-4648 | 78748    | 
| 1429855408  | Garden-Ville/Creedmoor                           | 512-329-4900 | 78610    | 
| 1429855440  | Green 'n Growing (Pflugerville)                  | 512-251-3262 | 78660    | 
| 1429855446  | Gus Garcia Community Garden *                    | 512-339-0016 | 78753    | 
```