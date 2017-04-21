# Public Health Nursing Listing

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/public-health-nursing-listing-6d805) |
| Metadata | [Link](https://data.hawaii.gov/api/views/x8h7-p5cj) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/x8h7-p5cj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/x8h7-p5cj/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | x8h7-p5cj |
| Name | Public Health Nursing Listing |
| Attribution | DOH |
| Category | Health |
| Tags | public, health, nursing, listing |
| Created | 2012-08-01T01:29:34Z |
| Publication Date | 2012-08-01T01:30:32Z |

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
series e:x8h7-p5cj d:2012-07-31T18:29:39.000Z t:phone_number=697-7839 t:street="Farrington Highway" t:name="Public Health Nursing, Waianae" t:city_state_zip_code="Waianae, HI 96792" t:house=85-670 t:island=OAHU m:row_number.x8h7-p5cj=1

series e:x8h7-p5cj d:2012-07-31T18:29:39.000Z t:phone_number=241-3387 t:street="Umi Street" t:name="Public Health Nursing, Kauai" t:city_state_zip_code="Lihue, HI 96766" t:house=3040 t:island=KAUAI m:row_number.x8h7-p5cj=2

series e:x8h7-p5cj d:2012-07-31T18:29:39.000Z t:phone_number=675-0073 t:street="Mokuola Street" t:name="Public Health Nursing, Leeward Oahu" t:city_state_zip_code="Waipahu, HI 96797" t:house=94-275 t:island=OAHU m:row_number.x8h7-p5cj=3
```

## Meta Commands

```ls
metric m:row_number.x8h7-p5cj p:long l:"Row Number"

entity e:x8h7-p5cj l:"Public Health Nursing Listing" t:attribution=DOH t:url=https://data.hawaii.gov/api/views/x8h7-p5cj

property e:x8h7-p5cj t:meta.view v:id=x8h7-p5cj v:category=Health v:attributionLink=http://hawaii.gov/doh v:averageRating=0 v:name="Public Health Nursing Listing" v:attribution=DOH

property e:x8h7-p5cj t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:x8h7-p5cj t:meta.view.owner v:id=8c9u-vteh v:screenName=lorrink v:displayName=lorrink

property e:x8h7-p5cj t:meta.view.tableauthor v:id=q99n-k47h v:screenName="Open Data Portal Administrator" v:roleName=administrator v:displayName="Open Data Portal Administrator"
```

## Top Records

```ls
| :updated_at | name                                 | house   | street               | city_state_zip_code  | island  | phone_number | 
| =========== | ==================================== | ======= | ==================== | ==================== | ======= | ============ | 
| 1343759379  | Public Health Nursing, Waianae       | 85-670  | Farrington Highway   | Waianae, HI 96792    | OAHU    | 697-7839     | 
| 1343759379  | Public Health Nursing, Kauai         | 3040    | Umi Street           | Lihue, HI 96766      | KAUAI   | 241-3387     | 
| 1343759379  | Public Health Nursing, Leeward Oahu  | 94-275  | Mokuola Street       | Waipahu, HI 96797    | OAHU    | 675-0073     | 
| 1343759379  | Public Health Nursing, East Honolulu | 3627    | Kiauea Avenue        | Honolulu, HI 96818   | OAHU    | 733-9220     | 
| 1343759379  | Public Health Nursing, Kona          | 79-1015 | Kaukapila Street     | Kealakekua, HI 96750 | HAWAII  | 322-1500     | 
| 1343759379  | Public Health Nursing, Lahaina       | 1830    | Honoapiilani Highway | Lahaina, HI 96761    | MAUI    | 662-4031     | 
| 1343759379  | Public Health Nursing, Wahiawa       | 830     | California Avenue    | Wahiawa, HI 96786    | OAHU    | 622-6445     | 
| 1343759379  | Public Health Nursing, Molokai       | 65      | Makena Street        | Kaunakakai, HI 96748 | MOLOKAI | 533-3663     | 
| 1343759379  | Public Health Nursing, Lanai         | 628     | 7th Street           | Lanai City, HI 96763 | LANAI   | 565-7114     | 
| 1343759379  | Public Health Nursing, East Hawaii   | 75      | Aupuni Street        | Hilo, HI 96720       | HAWAII  | 974-6025     | 
```