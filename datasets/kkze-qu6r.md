# WDFW-Hatchery Environmental Compliance

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/wdfw-hatchery-environmental-compliance-a4e55) |
| Metadata | [Link](https://data.wa.gov/api/views/kkze-qu6r) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/kkze-qu6r/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/kkze-qu6r/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | kkze-qu6r |
| Name | WDFW-Hatchery Environmental Compliance |
| Attribution | Washington Department of Fish and Wildlife |
| Category | Natural Resources & Environment |
| Tags | wdfw, hatcheries, salmon |
| Created | 2013-07-30T22:04:19Z |
| Publication Date | 2013-08-16T01:02:08Z |

## Columns

```ls
| Included | Schema Type | Field Name                     | Name                           | Data Type | Render Type |
| ======== | =========== | ============================== | ============================== | ========= | =========== |
| No       | time        | :updated_at                    | updated_at                     | meta_data | meta_data   |
| Yes      | series tag  | facility_name                  | Facility Name                  | text      | text        |
| Yes      | series tag  | screening_compliance           | Screening Compliance           | text      | text        |
| Yes      | series tag  | passage_compliance             | Passage Compliance             | text      | text        |
| Yes      | series tag  | water_quality_compliant        | Water Quality Compliant        | checkbox  | checkbox    |
| Yes      | series tag  | water_quality_violation        | Water Quality Violation        | checkbox  | checkbox    |
| Yes      | series tag  | water_quality_treatment_status | Water Quality Treatment Status | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:kkze-qu6r d:2013-07-30T15:04:25.000Z t:facility_name="Arlington Hatchery" t:water_quality_treatment_status="Needs to meet AKART/ has wetland disposal" m:row_number.kkze-qu6r=1

series e:kkze-qu6r d:2013-07-30T15:04:25.000Z t:water_quality_violation=false t:facility_name="Bingham Creek Hatchery" t:screening_compliance="Under review" t:water_quality_treatment_status=AKART t:water_quality_compliant=true t:passage_compliance=Mneeded m:row_number.kkze-qu6r=2

series e:kkze-qu6r d:2013-07-30T15:04:25.000Z t:water_quality_violation=false t:facility_name="Bogachiel Hatchery" t:screening_compliance="Under review" t:water_quality_treatment_status="Other/ Needs to meet AKART, has flow-through - a large dirt rearing pond with no ability to dewater or clean." t:water_quality_compliant=true t:passage_compliance=No m:row_number.kkze-qu6r=3
```

## Meta Commands

```ls
metric m:row_number.kkze-qu6r p:long l:"Row Number"

entity e:kkze-qu6r l:"WDFW-Hatchery Environmental Compliance" t:attribution="Washington Department of Fish and Wildlife" t:url=https://data.wa.gov/api/views/kkze-qu6r

property e:kkze-qu6r t:meta.view v:id=kkze-qu6r v:category="Natural Resources & Environment" v:attributionLink=http://wdfw.wa.gov/score v:averageRating=0 v:name="WDFW-Hatchery Environmental Compliance" v:attribution="Washington Department of Fish and Wildlife"

property e:kkze-qu6r t:meta.view.owner v:id=h2p6-jrpv v:profileImageUrlMedium=/api/users/h2p6-jrpv/profile_images/THUMB v:profileImageUrlLarge=/api/users/h2p6-jrpv/profile_images/LARGE v:screenName="WDFW Data" v:profileImageUrlSmall=/api/users/h2p6-jrpv/profile_images/TINY v:displayName="WDFW Data"

property e:kkze-qu6r t:meta.view.tableauthor v:id=h2p6-jrpv v:profileImageUrlMedium=/api/users/h2p6-jrpv/profile_images/THUMB v:profileImageUrlLarge=/api/users/h2p6-jrpv/profile_images/LARGE v:screenName="WDFW Data" v:profileImageUrlSmall=/api/users/h2p6-jrpv/profile_images/TINY v:roleName=publisher v:displayName="WDFW Data"
```

## Top Records

```ls
| :updated_at | facility_name              | screening_compliance | passage_compliance               | water_quality_compliant | water_quality_violation | water_quality_treatment_status                                                                                      | 
| =========== | ========================== | ==================== | ================================ | ======================= | ======================= | =================================================================================================================== | 
| 1375196665  | Arlington Hatchery         |                      |                                  |                         |                         | Needs to meet AKART/ has wetland disposal                                                                           | 
| 1375196665  | Bingham Creek Hatchery     | Under review         | Mneeded                          | true                    | false                   | AKART                                                                                                               | 
| 1375196665  | Bogachiel Hatchery         | Under review         | No                               | true                    | false                   | Other/ Needs to meet AKART, has flow-through - a large dirt rearing pond with no ability to dewater or clean.       | 
| 1375196665  | Cedar River Hatchery       |                      |                                  |                         |                         | Needs treatment, as it has none                                                                                     | 
| 1375196665  | Chambers Creek Hatchery    | Under review         | Yes                              | true                    | false                   | Other/ needs to meet AKART, earth pond non-compliant (Scheduled for PA in 2015-17) Currently has wetland treatment. | 
| 1375196665  | Coulter Creek Rearing Pond | Under review         | Mneeded (Coulter Creek Trib= No) |                         |                         | Needs Facilities to Meet AKART, Does have Wetland Treatment                                                         | 
| 1375196665  | Dungeness Hatchery         | Under review         | No                               | true                    | false                   | AKART                                                                                                               | 
| 1375196665  | Eells Springs Hatchery     | Under review         | N/A                              |                         |                         | Other/Has nothing, needs to meet AKART                                                                              | 
| 1375196665  | Elwha Hatchery             | Under review         | N/A                              | true                    | false                   | Other/ Has upland treatment                                                                                         | 
| 1375196665  | Forks Creek Hatchery       | Under review         | No                               | true                    | true                    | AKART                                                                                                               | 
```