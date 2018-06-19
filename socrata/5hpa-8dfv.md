# Existing Bike Facilities

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/existing-bike-facilities) |
| Metadata | [Link](https://data.honolulu.gov/api/views/5hpa-8dfv) |
| Data: JSON | [100 Rows](https://data.honolulu.gov/api/views/5hpa-8dfv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.honolulu.gov/api/views/5hpa-8dfv/rows.csv?max_rows=100) |
| Host | data.honolulu.gov |
| Id | 5hpa-8dfv |
| Name | Existing Bike Facilities |
| Category | Transportation |
| Created | 2015-04-16T18:16:02Z |
| Publication Date | 2015-04-16T18:16:53Z |

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type     | Render Type   |
| ======== | ============== | ============== | ============== | ============= | ============= |
| Yes      | series tag     | objectid_1     | OBJECTID_1     | text          | number        |
| Yes      | series tag     | facility_n     | Facility_N     | text          | text          |
| Yes      | series tag     | facility_d     | Facility_D     | text          | text          |
| Yes      | series tag     | facility_t     | Facility_T     | text          | text          |
| Yes      | series tag     | jurisdicti     | Jurisdicti     | text          | text          |
| Yes      | series tag     | corridor_t     | Corridor_T     | text          | text          |
| Yes      | series tag     | source         | Source         | text          | text          |
| Yes      | series tag     | townl          | TOWNL          | text          | text          |
| Yes      | series tag     | neighborl      | NEIGHBORL      | text          | text          |
| Yes      | numeric metric | length_mi      | Length_Mi      | number        | number        |
| Yes      | series tag     | dp_area        | DP_Area        | text          | text          |
| Yes      | series tag     | fac_con        | Fac_Con        | text          | text          |
| No       |                | fac_con_date   | Fac_Con_Date   | text          | text          |
| Yes      | series tag     | fac_con_inspec | Fac_Con_Inspec | text          | text          |
| Yes      | series tag     | fac_note       | Fac_Note       | text          | text          |
| Yes      | time           | creationdate   | CreationDate   | calendar_date | calendar_date |
| Yes      | series tag     | creator        | Creator        | text          | text          |
| No       |                | editdate       | EditDate       | calendar_date | calendar_date |
| Yes      | series tag     | editor         | Editor         | text          | text          |
```

## Time Field

```ls
Value = creationdate
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = fac_con_date,editdate
```

## Data Commands

```ls
series e:5hpa-8dfv d:2015-02-27T18:18:39.000Z t:editor=holisgis t:jurisdicti=County t:creator=holisgis t:facility_t=Lane t:facility_d="Kilani Avenue to California Avenue" t:dp_area="Central Oahu" t:source="State Bike Plan" t:objectid_1=1 t:townl=Wahiawa t:neighborl=WAHIAWA t:corridor_t=Mauka-Makai t:facility_n="North Cane Street" m:length_mi=0.127023639188527

series e:5hpa-8dfv d:2015-02-27T18:18:39.000Z t:editor=holisgis t:jurisdicti=County t:creator=holisgis t:facility_t=Lane t:facility_d="Kamehameha Highway to Plum Street" t:dp_area="Central Oahu" t:source="State Bike Plan" t:objectid_1=2 t:townl=Wahiawa t:neighborl=WAHIAWA t:corridor_t=Mauka-Makai t:facility_n="California Avenue (Eastern Section)" m:length_mi=0.422317757891972

series e:5hpa-8dfv d:2015-02-27T18:18:39.000Z t:editor=holisgis t:jurisdicti=Private t:creator=holisgis t:facility_t=Path t:facility_d="Ainamakua Drive to Lehiwa Drive" t:dp_area="Central Oahu" t:source=N/A t:objectid_1=3 t:facility_n="Mililani Ravine Path" m:length_mi=0.844808017924352
```

## Meta Commands

```ls
metric m:length_mi p:double l:Length_Mi t:dataTypeName=number

entity e:5hpa-8dfv l:"Existing Bike Facilities" t:url=https://data.honolulu.gov/api/views/5hpa-8dfv

property e:5hpa-8dfv t:meta.view d:2017-09-25T07:23:55.849Z v:averageRating=0 v:name="Existing Bike Facilities" v:id=5hpa-8dfv v:category=Transportation

property e:5hpa-8dfv t:meta.view.owner d:2017-09-25T07:23:55.849Z v:displayName="Karl Sueyoshi" v:id=b4zr-4dtj v:screenName="Karl Sueyoshi"

property e:5hpa-8dfv t:meta.view.tableauthor d:2017-09-25T07:23:55.849Z v:displayName="Karl Sueyoshi" v:roleName=publisher v:id=b4zr-4dtj v:screenName="Karl Sueyoshi"
```

## Top Records

```ls
| objectid_1 | facility_n                                | facility_d                                                | facility_t | jurisdicti | corridor_t  | source          | townl                 | neighborl                | length_mi         | dp_area       | fac_con | fac_con_date | fac_con_inspec | fac_note | creationdate        | creator  | editdate            | editor   | 
| ========== | ========================================= | ========================================================= | ========== | ========== | =========== | =============== | ===================== | ======================== | ================= | ============= | ======= | ============ | ============== | ======== | =================== | ======== | =================== | ======== | 
| 1          | North Cane Street                         | Kilani Avenue to California Avenue                        | Lane       | County     | Mauka-Makai | State Bike Plan | Wahiawa               | WAHIAWA                  | 0.127023639188527 | Central Oahu  |         |              |                |          | 2015-02-27T18:18:39 | holisgis | 2015-02-27T18:18:39 | holisgis | 
| 2          | California Avenue (Eastern Section)       | Kamehameha Highway to Plum Street                         | Lane       | County     | Mauka-Makai | State Bike Plan | Wahiawa               | WAHIAWA                  | 0.422317757891972 | Central Oahu  |         |              |                |          | 2015-02-27T18:18:39 | holisgis | 2015-02-27T18:18:39 | holisgis | 
| 3          | Mililani Ravine Path                      | Ainamakua Drive to Lehiwa Drive                           | Path       | Private    |             | N/A             |                       |                          | 0.844808017924352 | Central Oahu  |         |              |                |          | 2015-02-27T18:18:39 | holisgis | 2015-02-27T18:18:39 | holisgis | 
| 4          | Kilani Avenue                             | California Avenue to North Koa Street                     | Route      | County     | Mauka-Makai | State Bike Plan | Wahiawa               | WAHIAWA                  | 1.24191993782277  | Central Oahu  |         |              |                |          | 2015-02-27T18:18:39 | holisgis | 2015-02-27T18:18:39 | holisgis | 
| 5          | California Avenue (Western Section)       | Kilani Avenue to Kamehameha Highway                       | Route      | County     | Mauka-Makai | State Bike Plan | Wahiawa               | WAHIAWA                  | 0.819273651901516 | Central Oahu  |         |              |                |          | 2015-02-27T18:18:39 | holisgis | 2015-02-27T18:18:39 | holisgis | 
| 6          | Kunia Road                                | Anonui Street to Honowai Street                           | Route      | State      | Mauka-Makai | State Bike Plan | Mililani              | MILILANI/WAIPIO/MELEMANU | 1.4985155191386   | Central Oahu  |         |              |                |          | 2015-02-27T18:18:39 | holisgis | 2015-02-27T18:18:39 | holisgis | 
| 7          | Kamehameha Highway (Waipio)               | Ka Uka Boulevard to Waipio Uka Boulevard                  | Route      | State      | Mauka-Makai | State Bike Plan | Waipahu               | WAIPAHU                  | 0.723129155142652 | Central Oahu  |         |              |                |          | 2015-02-27T18:18:39 | holisgis | 2015-02-27T18:18:39 | holisgis | 
| 8          | Pearl Harbor Bike Path (Waipio Peninsula) | Waipahu Depot Road to Pear Harbor Bike Path Access at LCC | Path       | State      | Makai       | State Bike Plan | Waipahu               | WAIPAHU                  | 0.825498167088237 | Central Oahu  |         |              |                |          | 2015-02-27T18:18:39 | holisgis | 2015-02-27T18:18:39 | holisgis | 
| 9          | Queen Street                              | Kamakee to Piikoi                                         | Route      | County     |             | N/A             |                       |                          | 0.354582638509979 | PUC           |         |              |                |          | 2015-02-27T18:18:39 | holisgis | 2015-02-27T18:18:39 | holisgis | 
| 10         | Lunalilo Home Road                        | Kalanianaole Highway to Hawaii Kai Drive                  | Route      | County     | Mauka-Makai | State Bike Plan | Honolulu / Hawaii Kai | HAWAII KAI               | 1.72866251863974  | East Honolulu |         |              |                |          | 2015-02-27T18:18:39 | holisgis | 2015-02-27T18:18:39 | holisgis | 
```