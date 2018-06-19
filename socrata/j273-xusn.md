# Microsite-champaign

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/microsite-champaign-04254) |
| Metadata | [Link](https://data.illinois.gov/api/views/j273-xusn) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/j273-xusn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/j273-xusn/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | j273-xusn |
| Name | Microsite-champaign |
| Created | 2013-01-28T21:06:22Z |
| Publication Date | 2017-03-09T16:09:21Z |

## Description

Control file for the City of Champaign Microsite

## Columns

```ls
| Included | Schema Type | Field Name           | Name                 | Data Type | Render Type |
| ======== | =========== | ==================== | ==================== | ========= | =========== |
| No       | time        | :updated_at          | updated_at           | meta_data | meta_data   |
| Yes      | series tag  | featured_stat        | featured stat        | text      | text        |
| Yes      | series tag  | featured_description | featured description | text      | text        |
| Yes      | series tag  | featured_title       | featured title       | text      | text        |
| Yes      | series tag  | featured_agency      | featured agency      | text      | text        |
| Yes      | series tag  | agency_icon          | agency icon          | photo     | photo       |
| Yes      | series tag  | featured_text        | featured text        | text      | text        |
| Yes      | series tag  | featured_thumbnail   | featured thumbnail   | photo     | photo       |
| Yes      | series tag  | featured_link        | featured link        | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:j273-xusn d:2013-01-30T10:29:00.000Z t:featured_description="Population Growth Since 1860" t:featured_agency="City of Champaign" t:featured_text="Champaign is the 11th-most populous city in Illinois, and the fourth-most populous city in the state outside of the Chicago Metropolitan Area." t:featured_stat=4,593% t:featured_title="Champaign is Growing." t:featured_link=j5j5-zjn8 t:featured_thumbnail=Vca2hv_YYw5E7anuSbRxM7Z-kzxbfJP43rUy4JIIFsQ t:agency_icon=ukqSqkxhZaIFdEsBb1IMOW8Q_BoQecuZ_aUlcJBiWek m:row_number.j273-xusn=1

series e:j273-xusn d:2017-03-09T15:57:07.000Z t:featured_description="Recorded Tree Species" t:featured_agency="City of Champaign" t:featured_text="Trees are selected for insect and disease resistance, adaptability to local climate and soils, resistance to ice and wind damage, and desirable growth habits." t:featured_stat=176 t:featured_title="Diversity is not just for People." t:featured_link=58ti-2bb3 t:featured_thumbnail=gQr7mzhcvf5qMgpufzumcqAinTWwZwttxjEGKnluEpw t:agency_icon=ukqSqkxhZaIFdEsBb1IMOW8Q_BoQecuZ_aUlcJBiWek m:row_number.j273-xusn=2

series e:j273-xusn d:2017-03-09T16:01:11.000Z t:featured_description="Parking Meters" t:featured_agency="City of Champaign" t:featured_text="Champaign has quite a bit of available parking including parking meters, permit parking, a downtown parking deck, and street parking." t:featured_stat=1,983 t:featured_title="Need Parking? No Problem." t:featured_link=cctt-4q6r t:featured_thumbnail=2wAoY9UB5zXkF3CvGBep_P-jMrpenj8-wh7SpfY30uA t:agency_icon=ukqSqkxhZaIFdEsBb1IMOW8Q_BoQecuZ_aUlcJBiWek m:row_number.j273-xusn=3
```

## Meta Commands

```ls
metric m:row_number.j273-xusn p:long l:"Row Number"

entity e:j273-xusn l:Microsite-champaign t:url=https://data.illinois.gov/api/views/j273-xusn

property e:j273-xusn t:meta.view v:id=j273-xusn v:averageRating=0 v:name=Microsite-champaign

property e:j273-xusn t:meta.view.owner v:id=zs8p-j3v5 v:profileImageUrlMedium=/api/users/zs8p-j3v5/profile_images/THUMB v:profileImageUrlLarge=/api/users/zs8p-j3v5/profile_images/LARGE v:screenName="Darrell Cabales" v:profileImageUrlSmall=/api/users/zs8p-j3v5/profile_images/TINY v:displayName="Darrell Cabales"

property e:j273-xusn t:meta.view.tableauthor v:id=zs8p-j3v5 v:profileImageUrlMedium=/api/users/zs8p-j3v5/profile_images/THUMB v:profileImageUrlLarge=/api/users/zs8p-j3v5/profile_images/LARGE v:screenName="Darrell Cabales" v:profileImageUrlSmall=/api/users/zs8p-j3v5/profile_images/TINY v:displayName="Darrell Cabales"
```

## Top Records

```ls
| :updated_at | featured_stat | featured_description         | featured_title                    | featured_agency   | agency_icon                                 | featured_text                                                                                                                                                  | featured_thumbnail                          | featured_link | 
| =========== | ============= | ============================ | ================================= | ================= | =========================================== | ============================================================================================================================================================== | =========================================== | ============= | 
| 1359541740  | 4,593%        | Population Growth Since 1860 | Champaign is Growing.             | City of Champaign | ukqSqkxhZaIFdEsBb1IMOW8Q_BoQecuZ_aUlcJBiWek | Champaign is the 11th-most populous city in Illinois, and the fourth-most populous city in the state outside of the Chicago Metropolitan Area.                 | Vca2hv_YYw5E7anuSbRxM7Z-kzxbfJP43rUy4JIIFsQ | j5j5-zjn8     | 
| 1489075027  | 176           | Recorded Tree Species        | Diversity is not just for People. | City of Champaign | ukqSqkxhZaIFdEsBb1IMOW8Q_BoQecuZ_aUlcJBiWek | Trees are selected for insect and disease resistance, adaptability to local climate and soils, resistance to ice and wind damage, and desirable growth habits. | gQr7mzhcvf5qMgpufzumcqAinTWwZwttxjEGKnluEpw | 58ti-2bb3     | 
| 1489075271  | 1,983         | Parking Meters               | Need Parking? No Problem.         | City of Champaign | ukqSqkxhZaIFdEsBb1IMOW8Q_BoQecuZ_aUlcJBiWek | Champaign has quite a bit of available parking including parking meters, permit parking, a downtown parking deck, and street parking.                          | 2wAoY9UB5zXkF3CvGBep_P-jMrpenj8-wh7SpfY30uA | cctt-4q6r     | 
| 1489075758  | 5,148         | Streetlights                 | More Light, Less Energy.          | City of Champaign | ukqSqkxhZaIFdEsBb1IMOW8Q_BoQecuZ_aUlcJBiWek | Champaign is dedicated to having well lit streets, but also keeping energy costs low. LED streetlights installed around town help to achieve that goal.        | fHCp_Gs22V6RIgVPPd3ozyA9oGjYpw0RoNI0mDjgFng | hydr-ye4b     | 
```