# Assisted Living Facilities Listing

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/assisted-living-facilities-listing-37ae9) |
| Metadata | [Link](https://data.hawaii.gov/api/views/iqpn-unzm) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/iqpn-unzm/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/iqpn-unzm/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | iqpn-unzm |
| Name | Assisted Living Facilities Listing |
| Attribution | DOH |
| Category | Health |
| Tags | alf, listing |
| Created | 2012-08-01T01:21:15Z |
| Publication Date | 2012-08-01T01:27:11Z |

## Description

DOH Assisted Living Facilities Listing

## Columns

```ls
| Included | Schema Type | Field Name          | Name                | Data Type | Render Type |
| ======== | =========== | =================== | =================== | ========= | =========== |
| No       | time        | :updated_at         | updated_at          | meta_data | meta_data   |
| Yes      | series tag  | name                | Name                | text      | text        |
| Yes      | series tag  | house               | House               | text      | text        |
| Yes      | series tag  | city_state_zip_code | City/State/Zip code | text      | text        |
| Yes      | series tag  | island              | Island              | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:iqpn-unzm d:2012-07-31T18:21:25.000Z t:name="One Kalakaua Senior Living" t:city_state_zip_code="Honolulu, HI 96815" t:house=1314 t:island=Oahu m:row_number.iqpn-unzm=1

series e:iqpn-unzm d:2012-07-31T18:21:25.000Z t:name="Regency at Hualalai" t:city_state_zip_code="Kailua-Kona, HI 96740" t:house=75-181 t:island=Hawaii m:row_number.iqpn-unzm=2

series e:iqpn-unzm d:2012-07-31T18:21:25.000Z t:name="Regency at Puakea, L.L.C." t:city_state_zip_code="Lihue, HI 96766" t:house=2130 t:island=Kauai m:row_number.iqpn-unzm=3
```

## Meta Commands

```ls
metric m:row_number.iqpn-unzm p:long l:"Row Number"

entity e:iqpn-unzm l:"Assisted Living Facilities Listing" t:attribution=DOH t:url=https://data.hawaii.gov/api/views/iqpn-unzm

property e:iqpn-unzm t:meta.view v:id=iqpn-unzm v:category=Health v:attributionLink=http://hawaii.gov/doh v:averageRating=0 v:name="Assisted Living Facilities Listing" v:attribution=DOH

property e:iqpn-unzm t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:iqpn-unzm t:meta.view.owner v:id=8c9u-vteh v:screenName=lorrink v:displayName=lorrink

property e:iqpn-unzm t:meta.view.tableauthor v:id=q99n-k47h v:screenName="Open Data Portal Administrator" v:roleName=administrator v:displayName="Open Data Portal Administrator"
```

## Top Records

```ls
| :updated_at | name                                          | house    | city_state_zip_code   | island | 
| =========== | ============================================= | ======== | ===================== | ====== | 
| 1343758885  | One Kalakaua Senior Living                    | 1314     | Honolulu, HI 96815    | Oahu   | 
| 1343758885  | Regency at Hualalai                           | 75-181   | Kailua-Kona, HI 96740 | Hawaii | 
| 1343758885  | Regency at Puakea, L.L.C.                     | 2130     | Lihue, HI 96766       | Kauai  | 
| 1343758885  | Pohai Nani Good Samaritan                     | 45-090   | Kaneohe, HI 96744     | Oahu   | 
| 1343758885  | Hi'olani Assisted Living Center at Kahala Nui | 4389     | Honolulu, HI 96825    | Oahu   | 
| 1343758885  | The Plaza at Mililani                         | 95-1050  | Mililani, HI 96789    | Oahu   | 
| 1343758885  | Arcadia Retirement Residence                  | 1434     | Honolulu, HI 96822    | Oahu   | 
| 1343758885  | The Plaza at Punchbowl                        | 918      | Honolulu, HI 96822    | Oahu   | 
| 1343758885  | Hawaii Kai Retirement Comm Phase I and II     | 428, 446 | Honolulu, HI 96825    | Oahu   | 
| 1343758885  | Alii Community Care dba Roselani Place        | 88       | Kahului, HI 96732     | Maui   | 
```