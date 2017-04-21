# STD HIV Clinic

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/std-hiv-clinic-0887f) |
| Metadata | [Link](https://data.hawaii.gov/api/views/gbu4-vtbs) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/gbu4-vtbs/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/gbu4-vtbs/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | gbu4-vtbs |
| Name | STD HIV Clinic |
| Attribution | DOH |
| Category | Health |
| Tags | std, hiv, clinic |
| Created | 2012-08-01T01:25:50Z |
| Publication Date | 2012-08-01T01:26:37Z |

## Description

DOH Facilities Listing

## Columns

```ls
| Included | Schema Type | Field Name          | Name                | Data Type | Render Type |
| ======== | =========== | =================== | =================== | ========= | =========== |
| No       | time        | :updated_at         | updated_at          | meta_data | meta_data   |
| Yes      | series tag  | name                | Name                | text      | text        |
| Yes      | series tag  | house               | House               | text      | text        |
| Yes      | series tag  | street              | Street              | text      | text        |
| Yes      | series tag  | city_state_zip_code | City/State/Zip code | text      | text        |
| Yes      | series tag  | island              | Island              | text      | text        |
| Yes      | series tag  | phone_number        | Phone Number        | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:gbu4-vtbs d:2012-07-31T18:25:57.000Z t:phone_number=322-1500 t:street="Kaukapila Street" t:name="Public Health Nursing, Kona" t:city_state_zip_code="Kealakekua, HI 96750" t:house=79-1015 t:island=HAWAII m:row_number.gbu4-vtbs=1

series e:gbu4-vtbs d:2012-07-31T18:25:57.000Z t:phone_number=733-9281 t:street="Kilauea Avenue" t:name="Department of Health STD/HIV Clinic" t:city_state_zip_code="Honolulu, HI 96818" t:house=3267 t:island=OAHU m:row_number.gbu4-vtbs=2

series e:gbu4-vtbs d:2012-07-31T18:25:57.000Z t:phone_number=733-9220 t:street="Kiauea Avenue" t:name="Public Health Nursing, East Honolulu" t:city_state_zip_code="Honolulu, HI 96818" t:house=3627 t:island=OAHU m:row_number.gbu4-vtbs=3
```

## Meta Commands

```ls
metric m:row_number.gbu4-vtbs p:long l:"Row Number"

entity e:gbu4-vtbs l:"STD HIV Clinic" t:attribution=DOH t:url=https://data.hawaii.gov/api/views/gbu4-vtbs

property e:gbu4-vtbs t:meta.view v:id=gbu4-vtbs v:category=Health v:attributionLink=http://hawaii.gov/doh v:averageRating=0 v:name="STD HIV Clinic" v:attribution=DOH

property e:gbu4-vtbs t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:gbu4-vtbs t:meta.view.owner v:id=8c9u-vteh v:screenName=lorrink v:displayName=lorrink

property e:gbu4-vtbs t:meta.view.tableauthor v:id=8c9u-vteh v:screenName=lorrink v:roleName=editor v:displayName=lorrink
```

## Top Records

```ls
| :updated_at | name                                             | house   | street             | city_state_zip_code  | island  | phone_number | 
| =========== | ================================================ | ======= | ================== | ==================== | ======= | ============ | 
| 1343759157  | Public Health Nursing, Kona                      | 79-1015 | Kaukapila Street   | Kealakekua, HI 96750 | HAWAII  | 322-1500     | 
| 1343759157  | Department of Health STD/HIV Clinic              | 3267    | Kilauea Avenue     | Honolulu, HI 96818   | OAHU    | 733-9281     | 
| 1343759157  | Public Health Nursing, East Honolulu             | 3627    | Kiauea Avenue      | Honolulu, HI 96818   | OAHU    | 733-9220     | 
| 1343759157  | Public Health Nursing, Molokai                   | 65      | Makena Street      | Kaunakakai, HI 96748 | MOLOKAI | 533-3663     | 
| 1343759157  | Public Health Nursing, Wahiawa                   | 830     | California Avenue  | Wahiawa, HI 96786    | OAHU    | 622-6445     | 
| 1343759157  | Public Health Nursing, Waianae                   | 85-670  | Farrington Highway | Waianae, HI 96792    | OAHU    | 697-7839     | 
| 1343759157  | Public Health Nursing, Windward Oahu             | 45-691  | Keaahala Road      | Kaneohe, HI 96744    | OAHU    | 233-5450     | 
| 1343759157  | Department of Health Tuberclosis Control Program | 1700    | Lanakila Avenue    | Honolulu, HI 96817   | OAHU    | 832-5737     | 
| 1343759157  | Public Health Nursing, Maui                      | 121     | Mahalani Street    | Wailuku, HI 96793    | MAUI    | 984-2128     | 
| 1343759157  | Public Health Nursing, Lanai                     | 628     | 7th Street         | Lanai City, HI 96763 | LANAI   | 565-7114     | 
```