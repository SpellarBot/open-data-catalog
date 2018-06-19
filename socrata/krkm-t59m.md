# PONE-D-15-23803

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/pone-d-15-23803) |
| Metadata | [Link](https://data.cdc.gov/api/views/krkm-t59m) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/krkm-t59m/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/krkm-t59m/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | krkm-t59m |
| Name | PONE-D-15-23803 |
| Attribution | Centers for Disease Control and Prevention |
| Tags | malaria |
| Created | 2015-11-17T14:39:06Z |
| Publication Date | 2015-11-17T19:15:25Z |

## Description

This data set is from 3 surveys conducted in two districts in western Kenya following the scale up of insecticide treated nets and the implementation of IRS in one of the districts.

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                     | Data Type | Render Type |
| ======== | ============== | ====================== | ======================== | ========= | =========== |
| No       | time           | :updated_at            | updated_at               | meta_data | meta_data   |
| Yes      | series tag     | survey                 | SURVEY                   | text      | text        |
| Yes      | series tag     | district               | DISTRICT                 | text      | text        |
| Yes      | numeric metric | enumerationarea        | ENUMERATION_AREA         | number    | number      |
| Yes      | numeric metric | cpno_new               | CPNO_NEW                 | number    | number      |
| Yes      | series tag     | houseid_new            | HOUSEID_NEW              | text      | text        |
| Yes      | series tag     | housetype              | HOUSE_TYPE               | text      | text        |
| Yes      | series tag     | eavesopen              | EAVES_OPEN               | text      | text        |
| Yes      | numeric metric | totalnumofnets         | TOTALNUMOFNETS           | number    | number      |
| Yes      | series tag     | netsinhouse            | NETS_IN_HOUSE            | text      | text        |
| Yes      | series tag     | irs                    | IRS                      | text      | text        |
| Yes      | series tag     | netsplusspray          | NETS_PLUS_SPRAY          | text      | text        |
| Yes      | series tag     | preventmosquitoes      | PREVENT_MOSQUITOES       | text      | text        |
| Yes      | series tag     | elevation              | ELEVATION                | text      | text        |
| Yes      | series tag     | net_coverage           | NET_COVERAGE             | text      | text        |
| Yes      | series tag     | personid_new           | PERSONID_NEW             | text      | text        |
| Yes      | series tag     | sex                    | SEX                      | text      | text        |
| Yes      | series tag     | withbiologicalmother   | WITH_BIOLOGICAL_MOTHER   | text      | text        |
| Yes      | series tag     | secondaryschool        | SECONDARY_SCHOOL         | text      | text        |
| Yes      | series tag     | agecat                 | AGE_CAT                  | text      | text        |
| Yes      | series tag     | sleepnetlastnight      | SLEEP_NET_LAST_NIGHT     | text      | text        |
| Yes      | series tag     | itn                    | ITN                      | text      | text        |
| Yes      | series tag     | takeantimalarial       | TAKE_ANTIMALARIAL        | text      | text        |
| Yes      | series tag     | coartem1               | COARTEM                  | text      | text        |
| Yes      | numeric metric | hemocuereading         | HEMOCUE_READING          | number    | number      |
| Yes      | series tag     | anemia                 | ANEMIA                   | text      | text        |
| No       |                | pf                     | PF                       | text      | text        |
| Yes      | series tag     | feverin24h             | FEVER_IN_24H             | text      | text        |
| Yes      | series tag     | clinicalmalaria        | CLINICAL_MALARIA         | text      | text        |
| Yes      | numeric metric | parasitespermicroliter | PARASITES_PER_MICROLITER | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = pf
```

## Data Commands

```ls
series e:krkm-t59m d:2015-11-17T06:39:13.000Z t:itn="1=Yes" t:withbiologicalmother=No t:sex=Male t:anemia="2=No" t:irs="1=Yes" t:eavesopen="1=Yes" t:net_coverage=High t:takeantimalarial="2=No" t:elevation=Lowland t:preventmosquitoes="2=No" t:houseid_new=1007-33467 t:feverin24h=NO t:housetype=Permanent t:sleepnetlastnight="1=Yes" t:clinicalmalaria="2=No" t:personid_new=1007-33467-501253 t:coartem1="2=No" t:survey=PostIRS1 t:netsinhouse="1=Yes" t:district="1=Rachuon" t:secondaryschool=Yes t:netsplusspray="1=IRS, ITNs" t:agecat="3=Older than 15 years" m:hemocuereading=15.3 m:cpno_new=1007 m:totalnumofnets=2 m:enumerationarea=19

series e:krkm-t59m d:2015-11-17T06:39:13.000Z t:itn="1=Yes" t:withbiologicalmother=No t:sex=Male t:anemia="2=No" t:irs="1=Yes" t:eavesopen="1=Yes" t:net_coverage=High t:takeantimalarial="2=No" t:elevation=Lowland t:preventmosquitoes="2=No" t:houseid_new=1007-33467 t:feverin24h=YES t:housetype=Permanent t:sleepnetlastnight="1=Yes" t:clinicalmalaria="2=No" t:personid_new=1007-33467-65457 t:coartem1="2=No" t:survey=PostIRS1 t:netsinhouse="1=Yes" t:district="1=Rachuon" t:secondaryschool=Yes t:netsplusspray="1=IRS, ITNs" t:agecat="3=Older than 15 years" m:hemocuereading=16.4 m:cpno_new=1007 m:totalnumofnets=2 m:enumerationarea=19

series e:krkm-t59m d:2015-11-17T06:39:13.000Z t:itn="2=No" t:withbiologicalmother=No t:sex=Male t:anemia="2=No" t:irs="1=Yes" t:eavesopen="1=Yes" t:net_coverage=High t:takeantimalarial="2=No" t:elevation=Lowland t:preventmosquitoes="2=No" t:houseid_new=1007-33467 t:feverin24h=NO t:housetype=Permanent t:sleepnetlastnight="2=No" t:clinicalmalaria="2=No" t:personid_new=1007-33467-818485 t:coartem1="2=No" t:survey=PostIRS1 t:netsinhouse="2=No" t:district="1=Rachuon" t:secondaryschool=Yes t:netsplusspray="2=IRS, No ITNs" t:agecat="3=Older than 15 years" m:hemocuereading=13.9 m:cpno_new=1007 m:totalnumofnets=0 m:enumerationarea=19
```

## Meta Commands

```ls
metric m:enumerationarea p:integer l:ENUMERATION_AREA t:dataTypeName=number

metric m:cpno_new p:integer l:CPNO_NEW t:dataTypeName=number

metric m:totalnumofnets p:integer l:TOTALNUMOFNETS t:dataTypeName=number

metric m:hemocuereading p:float l:HEMOCUE_READING t:dataTypeName=number

metric m:parasitespermicroliter p:integer l:PARASITES_PER_MICROLITER t:dataTypeName=number

entity e:krkm-t59m l:PONE-D-15-23803 t:attribution="Centers for Disease Control and Prevention" t:url=https://data.cdc.gov/api/views/krkm-t59m

property e:krkm-t59m t:meta.view v:id=krkm-t59m v:averageRating=0 v:name=PONE-D-15-23803 v:attribution="Centers for Disease Control and Prevention"

property e:krkm-t59m t:meta.view.owner v:id=iuhx-tkn8 v:screenName="John Gimnig" v:displayName="John Gimnig"

property e:krkm-t59m t:meta.view.tableauthor v:id=iuhx-tkn8 v:screenName="John Gimnig" v:roleName=publisher v:displayName="John Gimnig"

property e:krkm-t59m t:meta.view.metadata.custom_fields.common_core v:Contact_Email=hzg1@cdc.gov v:Contact_Name="John Gimnig" v:Bureau_Code=009:20 v:Program_Code=009:036
```

## Top Records

```ls
| :updated_at | survey   | district  | enumerationarea | cpno_new | houseid_new  | housetype   | eavesopen | totalnumofnets | netsinhouse | irs   | netsplusspray     | preventmosquitoes | elevation | net_coverage | personid_new        | sex    | withbiologicalmother | secondaryschool | agecat                | sleepnetlastnight | itn   | takeantimalarial | coartem1 | hemocuereading     | anemia | pf   | feverin24h | clinicalmalaria | parasitespermicroliter | 
| =========== | ======== | ========= | =============== | ======== | ============ | =========== | ========= | ============== | =========== | ===== | ================= | ================= | ========= | ============ | =================== | ====== | ==================== | =============== | ===================== | ================= | ===== | ================ | ======== | ================== | ====== | ==== | ========== | =============== | ====================== | 
| 1447742353  | PostIRS1 | 1=Rachuon | 19              | 1007     | 1007-33467   | Permanent   | 1=Yes     | 2              | 1=Yes       | 1=Yes | 1=IRS, ITNs       | 2=No              | Lowland   | High         | 1007-33467-501253   | Male   | No                   | Yes             | 3=Older than 15 years | 1=Yes             | 1=Yes | 2=No             | 2=No     | 15.3               | 2=No   | 2=No | NO         | 2=No            |                        | 
| 1447742353  | PostIRS1 | 1=Rachuon | 19              | 1007     | 1007-33467   | Permanent   | 1=Yes     | 2              | 1=Yes       | 1=Yes | 1=IRS, ITNs       | 2=No              | Lowland   | High         | 1007-33467-65457    | Male   | No                   | Yes             | 3=Older than 15 years | 1=Yes             | 1=Yes | 2=No             | 2=No     | 16.399999999999999 | 2=No   | 2=No | YES        | 2=No            |                        | 
| 1447742353  | PostIRS1 | 1=Rachuon | 19              | 1007     | 1007-33467   | Permanent   | 1=Yes     | 0              | 2=No        | 1=Yes | 2=IRS, No ITNs    | 2=No              | Lowland   | High         | 1007-33467-818485   | Male   | No                   | Yes             | 3=Older than 15 years | 2=No              | 2=No  | 2=No             | 2=No     | 13.9               | 2=No   | 2=No | NO         | 2=No            |                        | 
| 1447742353  | PostIRS1 | 1=Rachuon | 19              | 1007     | 1007-726769  | Permanent   | 2=No      | 2              | 1=Yes       | 1=Yes | 1=IRS, ITNs       | 2=No              | Lowland   | High         | 1007-726769-369235  | Female | No                   | Yes             | 3=Older than 15 years | 1=Yes             | 1=Yes | 2=No             | 2=No     | 12.6               | 2=No   | 2=No | NO         | 2=No            |                        | 
| 1447742353  | PostIRS1 | 1=Rachuon | 19              | 1007     | 1007-726769  | Permanent   | 2=No      | 2              | 1=Yes       | 1=Yes | 1=IRS, ITNs       | 2=No              | Lowland   | High         | 1007-726769-525903  | Male   | No                   | Yes             | 3=Older than 15 years | 1=Yes             | 1=Yes | 1=Yes            | 1=Yes    | 14                 | 2=No   | 2=No | NO         | 2=No            |                        | 
| 1447742353  | PostIRS1 | 1=Rachuon | 19              | 1007     | 1007-726769  | Permanent   | 2=No      | 2              | 1=Yes       | 1=Yes | 1=IRS, ITNs       | 2=No              | Lowland   | High         | 1007-726769-57597   | Female | No                   | Yes             | 3=Older than 15 years | 1=Yes             | 1=Yes | 2=No             | 2=No     | 13.9               | 2=No   | 2=No | NO         | 2=No            |                        | 
| 1447742353  | PostIRS1 | 1=Rachuon | 19              | 1007     | 1007-726769  | Permanent   | 2=No      | 2              | 1=Yes       | 1=Yes | 1=IRS, ITNs       | 2=No              | Lowland   | High         | 1007-726769-666777  | Male   | No                   | Yes             | 3=Older than 15 years | 1=Yes             | 1=Yes | 2=No             | 2=No     | 17                 | 2=No   | 2=No | NO         | 2=No            |                        | 
| 1447742353  | PostIRS1 | 1=Rachuon | 19              | 1007     | 1007-726769  | Permanent   | 2=No      | 2              | 1=Yes       | 1=Yes | 1=IRS, ITNs       | 2=No              | Lowland   | High         | 1007-726769-791784  | Female | Yes                  | Yes             | 1=Less than 5 years   | 1=Yes             | 1=Yes | 2=No             | 2=No     | 12                 | 2=No   | 2=No | NO         | 2=No            |                        | 
| 1447742353  | PostIRS1 | 2=Nyando  | 53              | 10093    | 10093-568027 | Traditional | 1=Yes     | 0              | 2=No        | 2=No  | 4=No IRS, No ITNs | 2=No              | Lowland   | High         | 10093-568027-974441 | Male   | No                   | No              | 3=Older than 15 years | 2=No              | 2=No  | 2=No             | 2=No     | 12.5               | 2=No   | 2=No | NO         | 2=No            |                        | 
| 1447742353  | PostIRS1 | 2=Nyando  | 53              | 10093    | 10093-569885 | Traditional | 1=Yes     | 0              | 2=No        | 2=No  | 4=No IRS, No ITNs | 2=No              | Lowland   | High         | 10093-569885-371538 | Male   | No                   | No              | 3=Older than 15 years | 2=No              | 2=No  | 2=No             | 2=No     | 15.1               | 2=No   | 2=No | NO         | 2=No            |                        | 
```