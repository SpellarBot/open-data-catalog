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
| Rows Updated | 2015-04-16T18:16:27Z |

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type     | Render Type   |
| ======== | ============== | ============== | ============== | ============= | ============= |
| Yes      | numeric metric | objectid_1     | OBJECTID_1     | number        | number        |
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
| Yes      | series tag     | fac_con_date   | Fac_Con_Date   | text          | text          |
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
Excluded Fields = editdate
```

## Data Commands

```ls
series e:5hpa-8dfv d:2015-02-27T18:18:39.000Z t:facility_n="North Cane Street" t:editor=holisgis t:jurisdicti=County t:source="State Bike Plan" t:dp_area="Central Oahu" t:facility_t=Lane t:facility_d="Kilani Avenue to California Avenue" t:corridor_t=Mauka-Makai t:townl=Wahiawa t:neighborl=WAHIAWA t:creator=holisgis m:length_mi=0.12702 m:objectid_1=1

series e:5hpa-8dfv d:2015-02-27T18:18:39.000Z t:facility_n="California Avenue (Eastern Section)" t:editor=holisgis t:jurisdicti=County t:source="State Bike Plan" t:dp_area="Central Oahu" t:facility_t=Lane t:facility_d="Kamehameha Highway to Plum Street" t:corridor_t=Mauka-Makai t:townl=Wahiawa t:neighborl=WAHIAWA t:creator=holisgis m:length_mi=0.42232 m:objectid_1=2

series e:5hpa-8dfv d:2015-02-27T18:18:39.000Z t:facility_n="Mililani Ravine Path" t:editor=holisgis t:jurisdicti=Private t:source=N/A t:dp_area="Central Oahu" t:facility_t=Path t:facility_d="Ainamakua Drive to Lehiwa Drive" t:creator=holisgis m:length_mi=0.84481 m:objectid_1=3
```

## Meta Commands

```ls
metric m:objectid_1 p:integer l:OBJECTID_1 t:dataTypeName=number

metric m:length_mi p:double l:Length_Mi t:dataTypeName=number

entity e:5hpa-8dfv l:"Existing Bike Facilities" t:url=https://data.honolulu.gov/api/views/5hpa-8dfv

property e:5hpa-8dfv t:meta.view v:id=5hpa-8dfv v:category=Transportation v:averageRating=0 v:name="Existing Bike Facilities"

property e:5hpa-8dfv t:meta.view.owner v:id=b4zr-4dtj v:screenName="Karl Sueyoshi" v:roleName=administrator v:displayName="Karl Sueyoshi"

property e:5hpa-8dfv t:meta.view.tableauthor v:id=b4zr-4dtj v:screenName="Karl Sueyoshi" v:roleName=administrator v:displayName="Karl Sueyoshi"
```