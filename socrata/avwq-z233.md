# Current Medallions

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/current-medallions-78186) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/avwq-z233) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/avwq-z233/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/avwq-z233/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | avwq-z233 |
| Name | Current Medallions |
| Attribution | Taxi and Limousine Commission (TLC) |
| Category | Transportation |
| Tags | transportation, taxi, limousine, medallion |
| Created | 2011-08-26T20:14:36Z |
| Publication Date | 2012-02-29T15:56:46Z |

## Description

Spreadsheet of all TLC current medallions

## Columns

```ls
| Included | Schema Type | Field Name                                         | Name                                               | Data Type | Render Type |
| ======== | =========== | ================================================== | ================================================== | ========= | =========== |
| Yes      | series tag  | license_number                                     | License Number                                     | text      | text        |
| Yes      | series tag  | name_of_licensee                                   | Name of Licensee                                   | text      | text        |
| Yes      | series tag  | license_type                                       | License Type                                       | text      | text        |
| Yes      | series tag  | driver_of_record_status                            | Driver of Record Status                            | text      | text        |
| Yes      | series tag  | dmv_license_plate                                  | DMV License Plate                                  | text      | text        |
| Yes      | series tag  | vin                                                | VIN                                                | text      | text        |
| Yes      | series tag  | hybrid_accessible_cng_or_stretch_limousine_vehicle | Hybrid_Accessible_CNG_OR_Stretch_Limousine_Vehicle | text      | text        |
| Yes      | time        | model_year                                         | Model Year                                         | number    | number      |
| Yes      | series tag  | type_of_medallions_ind_or_minifleet                | Type of Medallions (Ind or Minifleet)              | text      | text        |
| Yes      | series tag  | medallion_agent_number                             | Medallion Agent Number                             | text      | number      |
```

## Time Field

```ls
Value = model_year
Format & Zone = yyyy
```

## Data Commands

```ls
```

## Meta Commands

```ls
entity e:avwq-z233 l:"Current Medallions" t:attribution="Taxi and Limousine Commission (TLC)" t:url=https://data.cityofnewyork.us/api/views/avwq-z233

property e:avwq-z233 t:meta.view v:id=avwq-z233 v:category=Transportation v:averageRating=0 v:name="Current Medallions" v:attribution="Taxi and Limousine Commission (TLC)"

property e:avwq-z233 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:avwq-z233 t:meta.view.tableauthor v:id=txun-eb7e v:screenName="Albert Webber" v:roleName=administrator v:displayName="Albert Webber"
```

## Top Records

```ls
| license_number | name_of_licensee   | license_type | driver_of_record_status | dmv_license_plate | vin               | hybrid_accessible_cng_or_stretch_limousine_vehicle | model_year | type_of_medallions_ind_or_minifleet | medallion_agent_number | 
| ============== | ================== | ============ | ======================= | ================= | ================= | ================================================== | ========== | =================================== | ====================== | 
| 1A10           | JUHN,JAY,JAEWON    | MEDALLION    | Named Driver            | 1A10A             | 1FMCU4K3XBKB54850 | HYB                                                | 2011       | IU                                  | 0                      | 
| 1A11           | YOON, DAE JIN      | MEDALLION    | Owner Must Driver       | 1A11A             | 2FABP7AV7BX123523 |                                                    | 2011       | IU                                  | 0                      | 
| 1A12           | LOUIS BELFOND      | MEDALLION    | Named Driver            | 1A12A             | 1FMCU4K32BKA16414 | HYB                                                | 2011       | IU                                  | 234                    | 
| 1A13           | MAGDA,GAVRIL       | MEDALLION    | Named Driver            | 1A13A             | 1FMCU4K3XAKA88055 | HYB                                                | 2010       | IU                                  | 213                    | 
| 1A14           | BUTTACAVOLE,JOHN   | MEDALLION    | Named Driver            | 1A14H             | 1FMCU493X9KB31021 | HYB                                                | 2009       | IU                                  | 307                    | 
| 1A15           | TOPPA,JAWAID,A     | MEDALLION    | Owner Must Driver       | 1A15B             | 2FABP7AV7BX107418 |                                                    | 2011       | IU                                  | 0                      | 
| 1A17           | QURESHI, BASHIR A. | MEDALLION    | Named Driver            | 1A17B             | 1FMCU4K33CKA52002 | HYB                                                | 2012       | IU                                  | 202                    | 
| 1A18           | PANTELIS, BILL P.  | MEDALLION    | Named Driver            | 1A18A             | 2FAFP70V78X159207 |                                                    | 2008       | IU                                  | 0                      | 
| 1A19           | AHMED,SHAFAYET     | MEDALLION    | Owner Must Driver       | 1A19B             | 2FABP7AV6AX130526 |                                                    | 2010       | IU                                  | 0                      | 
| 1A20           | ABRAMOWITZ, ALLEN  | MEDALLION    | Unspecified Dirver      | 1A20B             | 2FAHP70V59X130962 |                                                    | 2009       | IU                                  | 102                    | 
```