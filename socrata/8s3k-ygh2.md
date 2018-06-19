# Oregon listed and candidate plants - complete list

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/oregon-listed-and-candidate-plants-complete-list-c007b) |
| Metadata | [Link](https://data.oregon.gov/api/views/8s3k-ygh2) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/8s3k-ygh2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/8s3k-ygh2/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | 8s3k-ygh2 |
| Name | Oregon listed and candidate plants - complete list |
| Attribution | Oregon Department of Agriculture Native Plant Conservation Program |
| Category | Natural Resources |
| Tags | "state-listed", "rare plant", threatened, endangered, "plant conservation" |
| Created | 2014-02-13T21:00:18Z |
| Publication Date | 2014-08-13T18:11:00Z |

## Description

This is an attempt to compile a complete dataset of all state-listed (both threatened and endangered) and candidate plant species along with all their plant profile information.

## Columns

```ls
| Included | Schema Type | Field Name      | Name                       | Data Type | Render Type |
| ======== | =========== | =============== | ========================== | ========= | =========== |
| No       | time        | :updated_at     | updated_at                 | meta_data | meta_data   |
| Yes      | series tag  | scientific_name | Scientific name            | html      | html        |
| Yes      | series tag  | profile_link    | Common name & profile link | url       | url         |
| Yes      | series tag  | listing_status  | Listing                    | text      | text        |
| Yes      | series tag  | flower_photo_2  | Flower                     | photo     | photo       |
| Yes      | series tag  | habit_photo     | Habit                      | photo     | photo       |
| Yes      | series tag  | habitat_photo   | Habitat                    | photo     | photo       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:8s3k-ygh2 d:2014-08-13T10:18:11.000Z t:flower_photo_2=uW4fAt5ZWVHZLbGbj28xN8O2DEkBB0uKW1HKH4j_aAg t:profile_link=http://www.oregon.gov/oda/shared/Documents/Publications/PlantConservation/AbroniaUmbellataBrevifloraProfile.pdf t:habit_photo=_iaa87S80ATyiX7imFZBCtN2pEL-0WkJEn7_yD4Fpp4 t:listing_status=E t:scientific_name="<p><em>Abronia umbellata</em> var. <em>breviflora</em></p>" t:habitat_photo=BOZOYpVy_oJVAQ6qU0cXhClyMwWTEByLpbn_8VkkGGk m:row_number.8s3k-ygh2=1

series e:8s3k-ygh2 d:2014-08-13T10:18:25.000Z t:flower_photo_2=E3xv5FKJt6T35A-hgizv3miI1GMGYiIpbaPWy-C6-P4 t:profile_link=http://www.oregon.gov/oda/shared/Documents/Publications/PlantConservation/ArabisMacdonaldianaProfile.pdf t:habit_photo=jXU1W6ohRFE8Bo5UywkFPnvR4xVc1VUr8AZt5SKtKD0 t:listing_status=E t:scientific_name="<p><em>Arabis macdonaldiana</em></p>" t:habitat_photo=xKEmElWevqnWVSyS5qNwuqOgwZtTOgNwnPgeslVQ-84 m:row_number.8s3k-ygh2=2

series e:8s3k-ygh2 d:2014-08-13T10:26:20.000Z t:flower_photo_2=BK3dW671wLemSbGsAdmgkGveB5A1dSLg2tms6sXlBpQ t:profile_link=http://www.oregon.gov/oda/shared/Documents/Publications/PlantConservation/HowelliaAquatilisProfile.pdf t:habit_photo=w0axyKjETJcA3L-HaN5P_vUtLUDqOXgUdmSeWPBupHA t:listing_status=T t:scientific_name="<p><em>Howellia aquatilis</em></p>" t:habitat_photo=t-YimKB0yENywQHzOgucr4OsooP6l-NoV-KfJZr2u0s m:row_number.8s3k-ygh2=3
```

## Meta Commands

```ls
metric m:row_number.8s3k-ygh2 p:long l:"Row Number"

entity e:8s3k-ygh2 l:"Oregon listed and candidate plants - complete list" t:attribution="Oregon Department of Agriculture Native Plant Conservation Program" t:url=https://data.oregon.gov/api/views/8s3k-ygh2

property e:8s3k-ygh2 t:meta.view v:id=8s3k-ygh2 v:category="Natural Resources" v:averageRating=0 v:name="Oregon listed and candidate plants - complete list" v:attribution="Oregon Department of Agriculture Native Plant Conservation Program"

property e:8s3k-ygh2 t:meta.view.owner v:id=6si7-i25g v:screenName=jabrown v:displayName=jabrown

property e:8s3k-ygh2 t:meta.view.tableauthor v:id=6si7-i25g v:screenName=jabrown v:displayName=jabrown
```

## Top Records

```ls
| :updated_at | scientific_name                      | profile_link                                                                                                                                        | listing_status | flower_photo_2                              | habit_photo                                 | habitat_photo                               | 
| =========== | ==================================== | =================================================================================================================================================== | ============== | =========================================== | =========================================== | =========================================== | 
| 1407925091  | Abronia umbellata var. breviflora    | [http://www.oregon.gov/oda/shared/Documents/Publications/PlantConservation/AbroniaUmbellataBrevifloraProfile.pdf, Pink sandverbena]                 | E              | uW4fAt5ZWVHZLbGbj28xN8O2DEkBB0uKW1HKH4j_aAg | _iaa87S80ATyiX7imFZBCtN2pEL-0WkJEn7_yD4Fpp4 | BOZOYpVy_oJVAQ6qU0cXhClyMwWTEByLpbn_8VkkGGk | 
| 1407925105  | Arabis macdonaldiana                 | [http://www.oregon.gov/oda/shared/Documents/Publications/PlantConservation/ArabisMacdonaldianaProfile.pdf, McDonald's rockcress]                    | E              | E3xv5FKJt6T35A-hgizv3miI1GMGYiIpbaPWy-C6-P4 | jXU1W6ohRFE8Bo5UywkFPnvR4xVc1VUr8AZt5SKtKD0 | xKEmElWevqnWVSyS5qNwuqOgwZtTOgNwnPgeslVQ-84 | 
| 1407925580  | Howellia aquatilis                   | [http://www.oregon.gov/oda/shared/Documents/Publications/PlantConservation/HowelliaAquatilisProfile.pdf, Howellia]                                  | T              | BK3dW671wLemSbGsAdmgkGveB5A1dSLg2tms6sXlBpQ | w0axyKjETJcA3L-HaN5P_vUtLUDqOXgUdmSeWPBupHA | t-YimKB0yENywQHzOgucr4OsooP6l-NoV-KfJZr2u0s | 
| 1407925197  | Ivesia rhypara var. rhypara          | [http://www.oregon.gov/oda/shared/Documents/Publications/PlantConservation/IvesiaRhyparaRhyparaProfile.pdf, Grimy ivesia]                           | E              | uTUX2YVXrA5vfi-nB4zLhetT_-qRDu6UrhwioMGofsc | 7Kc1UO8SDZbtpLM3v-CEiYw86R4ersTumVB6yUZUZN0 | WXcL9CJncZrdplz4uHfnZi8QjvGwroW8_RwncGHl7yA | 
| 1407925213  | Lilium occidentale                   | [http://www.oregon.gov/oda/shared/Documents/Publications/PlantConservation/LiliumOccidentaleProfile.pdf, Western lily]                              | E              | 3KMRpbbtZm_rctkRvjscQl7p1oInUvQ9ULwWZu0Rnms | HrUlvlByih__nq1QZIjfIdV-T1w_UFA4J3nzrYBErPQ | WQ8LCQLlC6cfnfUKkwqTi9O5m7TnzCKC25HxRwyxbK0 | 
| 1407925233  | Limnanthes floccosa ssp. grandiflora | [http://www.oregon.gov/oda/shared/Documents/Publications/PlantConservation/LimnanthesFloccosaGrandifloraProfile.pdf, Big-flowered wooly meadowfoam] | E              | P6DPlCO5huijz_OLdLuFJXwcs4QzbkeMAc-BH9ArIzQ | wA9p_Qs27sQs7lYO5yAMxmUUHhOJqz9trsCdlcZLZt4 | bDuL3BtTi0CVbjBvlpLuCIN7ELpXvfGEWMuN_Pw3W6U | 
| 1407925240  | Lomatium bradshawii                  | [http://www.oregon.gov/oda/shared/Documents/Publications/PlantConservation/LomatiumBradshawiiProfile.pdf, Bradshaw's desert parsley]                | E              | tMVEiEQ3FN6D-Qn7cKjDfxL_jXoOdLHCMq-3UdU2ojk | DZKs1k7zTuFFCb1nhLARwMsfN27CC_KiBMc3q8VBztM | 23b8mYQrztX63zRf6RtqJSrEivr_EKfeUfjGKg0B4hg | 
| 1407925245  | Lomatium cookii                      | [http://www.oregon.gov/oda/shared/Documents/Publications/PlantConservation/LomatiumCookiiProfile.pdf, Cook's desert parsley]                        | E              | 2N2bgVSHH3umIO4Lez3RMVXA5ZKhTVLjl0nWnkGtLuQ | sgIh-nIWMdtfELvEKHrBO9pW0SufeYgDVcxH4g_zcAY | 2rq8N2xN1QX8WL7OlJZbGCZukAyWG-mEmPpRriP0-HE | 
| 1407925252  | Lomatium erythrocarpum               | [http://www.oregon.gov/oda/shared/Documents/Publications/PlantConservation/LomatiumErythrocarpumProfile.pdf, Red-fruited lomatium]                  | E              |                                             | iutU3HjxsDtpx9Vu1O2SAX2-WS0gdem4ZMFTzOuMezc | IOYPgfbCIY4sricCEZJ0axuBRW7y4XZsXK6btiUJiL0 | 
| 1407925290  | Plagiobothrys lamprocarpus           | [http://www.oregon.gov/oda/shared/Documents/Publications/PlantConservation/PlagiobothrysLamprocarpusProfile.pdf, Shiny-fruited allocarya]           | E              |                                             |                                             |                                             | 
```