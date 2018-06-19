# Oregon listed plants by county - complete list for map

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/oregon-listed-plants-by-county-complete-list-for-map-da14b) |
| Metadata | [Link](https://data.oregon.gov/api/views/er5e-y4zf) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/er5e-y4zf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/er5e-y4zf/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | er5e-y4zf |
| Name | Oregon listed plants by county - complete list for map |
| Created | 2014-07-03T17:11:04Z |
| Publication Date | 2014-07-31T22:50:49Z |

## Columns

```ls
| Included | Schema Type | Field Name                                 | Name                                           | Data Type | Render Type |
| ======== | =========== | ========================================== | ============================================== | ========= | =========== |
| No       | time        | :updated_at                                | updated_at                                     | meta_data | meta_data   |
| Yes      | series tag  | county                                     | County                                         | text      | text        |
| Yes      | series tag  | scientific_name_common_name_listing_status | Scientific name - Common name - Listing status | text      | html        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:er5e-y4zf d:2014-07-03T10:11:07.000Z t:county="Crook County" t:scientific_name_common_name_listing_status=NONE m:row_number.er5e-y4zf=1

series e:er5e-y4zf d:2014-07-03T10:11:07.000Z t:county="Hood River County" t:scientific_name_common_name_listing_status=NONE m:row_number.er5e-y4zf=2

series e:er5e-y4zf d:2014-07-03T10:36:45.000Z t:county="Columbia County" t:scientific_name_common_name_listing_status="<p><em>Howellia aquatilis</em> - Howellia - Threatened</p>
<p><em>Sidalcea nelsoniana</em> - Nelson's checkermallow - Threatened</p>" m:row_number.er5e-y4zf=3
```

## Meta Commands

```ls
metric m:row_number.er5e-y4zf p:long l:"Row Number"

entity e:er5e-y4zf l:"Oregon listed plants by county - complete list for map" t:url=https://data.oregon.gov/api/views/er5e-y4zf

property e:er5e-y4zf t:meta.view v:id=er5e-y4zf v:averageRating=0 v:name="Oregon listed plants by county - complete list for map"

property e:er5e-y4zf t:meta.view.owner v:id=6si7-i25g v:screenName=jabrown v:displayName=jabrown

property e:er5e-y4zf t:meta.view.tableauthor v:id=6si7-i25g v:screenName=jabrown v:displayName=jabrown
```

## Top Records

```ls
| :updated_at | county            | scientific_name_common_name_listing_status                                                                                                                                                                                                                                                                                                                                                                                    | 
| =========== | ================= | ============================================================================================================================================================================================================================================================================================================================================================================================================================= | 
| 1404382267  | Crook County      | NONE                                                                                                                                                                                                                                                                                                                                                                                                                          | 
| 1404382267  | Hood River County | NONE                                                                                                                                                                                                                                                                                                                                                                                                                          | 
| 1404383805  | Columbia County   | Howellia aquatilis - Howellia - Threatened
Sidalcea nelsoniana - Nelson's checkermallow - Threatened                                                                                                                                                                                                                                                                                                                          | 
| 1404382483  | Baker County      | Hackelia cronquistii - Cronquist's stickseed - Threatened
Lomatium erythrocarpum - Red-fruited lomatium - Endangered
Lupinus lepidus var. cusickii - Cusick's lupine - Endangered
Pyrrocoma radiata - Snake River goldenweed - Endangered
Thelypodium howellii ssp. spectabilis - Howell's spectacular thelypody - Endangered                                                                                                 | 
| 1404383778  | Clackamas County  | Delphinium leucophaeum - White rock larkspur - Endangered
Delphinium pavonaceum - Peacock larkspur - Endangered
Erigeron decumbens - Willamette daisy - Endangered
Howellia aquatilis - Howellia - Threatened
Sericocarpus rigidus - White-topped aster - Threatened
Sidalcea nelsoniana - Nelson's checkermallow - Threatened                                                                                                | 
| 1404383895  | Coos County       | Abronia umbellata var. breviflora - Pink sandverbena - Endangered
Cordylanthus maritimus ssp. palustris - Point Reyes bird's-beak - Endangered
Lilium occidentale - Western lily - Endangered
Phacelia argentea - Silvery phacelia - Threatened                                                                                                                                                                               | 
| 1404383980  | Curry County      | Abronia umbellata var. breviflora - Pink sandverbena - Endangered
Arabis macdonaldiana - McDonald's rockcress, Red Mountain rockcress - Endangered
Calochortus howellii - Howell's mariposa lily - Threatened
Lilium occidentale - Western lily - Endangered
Microseris howellii - Howell's microseris - Threatened
Oenothera wolfii - Wolf's evening-primrose - Threatened
Phacelia argentea - Silvery phacelia - Threatened | 
| 1404383996  | Deschutes County  | Astragalus peckii - Peck's milkvetch - Threatened
Botrychium pumicola - Pumice grape-fern - Threatened                                                                                                                                                                                                                                                                                                                        | 
| 1404384078  | Douglas County    | Abronia umbellata var. breviflora - Pink sandverbena - Endangered
Calochortus coxii - Crinite mariposa lily - Endangered
Calochortus umpquaensis - Umpqua mariposa lily - Endangered
Eucephalus vialis - Wayside aster - Threatened
Lupinus oreganus - Kincaid's lupine, Oregon lupine - Threatened
Plagiobothrys hirtus - Rough popcornflower - Endangered                                                                   | 
| 1404384092  | Gilliam County    | Astragalus collinus var. laurentii - Lawrence's milkvetch, Laurent's milkvetch - Threatened                                                                                                                                                                                                                                                                                                                                   | 
```