# Alcohol and Drug Abuse Prevention Services

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/alcohol-and-drug-abuse-prevention-services-617ab) |
| Metadata | [Link](https://data.hawaii.gov/api/views/2dr7-mwnn) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/2dr7-mwnn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/2dr7-mwnn/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | 2dr7-mwnn |
| Name | Alcohol and Drug Abuse Prevention Services |
| Attribution | Department of Health |
| Category | Health |
| Tags | drugs, alcohol |
| Created | 2012-08-24T23:42:04Z |
| Publication Date | 2012-08-25T00:06:59Z |

## Description

Location of facilities participating in Alocohol and Drug Abuse Prevention and Awareness Services

## Columns

```ls
| Included | Schema Type    | Field Name  | Name       | Data Type | Render Type |
| ======== | ============== | =========== | ========== | ========= | =========== |
| No       | time           | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag     | name        | Name       | text      | text        |
| Yes      | series tag     | services    | Services   | text      | text        |
| Yes      | numeric metric | house       | House      | number    | number      |
| Yes      | series tag     | zip_code    | Zip code   | text      | number      |
| Yes      | series tag     | island      | Island     | text      | text        |
| Yes      | series tag     | phone       | PHONE      | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:2dr7-mwnn d:2012-08-24T17:06:05.000Z t:phone=249-2990 t:services="Youth Substance Abuse Prevention" t:zip_code=96793 t:name="Maui Economic Opportunity" t:island=OAHU m:house=99

series e:2dr7-mwnn d:2012-08-24T17:06:05.000Z t:phone=596-8433 t:services="Youth Substance Abuse Prevention Services" t:zip_code=96814 t:name="The Institute for Family Enrichment" t:island=OAHU m:house=615

series e:2dr7-mwnn d:2012-08-24T17:06:05.000Z t:phone=586-1444 t:services="Coordination of Coalition for Enforcement of Underage Drinking Laws" t:zip_code=96813 t:name="Department of Attorney General" t:island=OAHU m:house=235
```

## Meta Commands

```ls
metric m:house p:integer l:House t:dataTypeName=number

entity e:2dr7-mwnn l:"Alcohol and Drug Abuse Prevention Services" t:attribution="Department of Health" t:url=https://data.hawaii.gov/api/views/2dr7-mwnn

property e:2dr7-mwnn t:meta.view v:id=2dr7-mwnn v:category=Health v:attributionLink=http://hawaii.gov/health v:averageRating=0 v:name="Alcohol and Drug Abuse Prevention Services" v:attribution="Department of Health"

property e:2dr7-mwnn t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:2dr7-mwnn t:meta.view.owner v:id=8c9u-vteh v:screenName=lorrink v:displayName=lorrink

property e:2dr7-mwnn t:meta.view.tableauthor v:id=a5cm-ukuw v:profileImageUrlMedium=/api/users/a5cm-ukuw/profile_images/THUMB v:profileImageUrlLarge=/api/users/a5cm-ukuw/profile_images/LARGE v:screenName="OIMT Open Data Coordinator" v:profileImageUrlSmall=/api/users/a5cm-ukuw/profile_images/TINY v:roleName=publisher v:displayName="OIMT Open Data Coordinator"
```

## Top Records

```ls
| :updated_at | name                                                           | services                                                                                                        | house | zip_code | island | phone    | 
| =========== | ============================================================== | =============================================================================================================== | ===== | ======== | ====== | ======== | 
| 1345827965  | Parents and Children Together, Kaneohe Community Family Center | Youth and Families Substance Abuse Prevention                                                                   |       | 96744    | OAHU   | 235-7747 | 
| 1345827965  | Maui Economic Opportunity                                      | Youth Substance Abuse Prevention                                                                                | 99    | 96793    | OAHU   | 249-2990 | 
| 1345827965  | The Institute for Family Enrichment                            | Youth Substance Abuse Prevention Services                                                                       | 615   | 96814    | OAHU   | 596-8433 | 
| 1345827965  | Hina Mauka                                                     | Youth Substance Abuse Prevention                                                                                |       | 96744    | OAHU   | 447-5259 | 
| 1345827965  | Department of Attorney General                                 | Coordination of Coalition for Enforcement of Underage Drinking Laws                                             | 235   | 96813    | OAHU   | 586-1444 | 
| 1345827965  | Honolulu Police Department                                     | 1)Enforcement of State law prohibiting Tobacco Sales to Minors; 2)Compliance checks for alcohol sales to minors | 801   | 96813    | OAHU   | 529-3882 | 
| 1345827965  | University of Hawaii, Office of Public Health Studies          | Alcohol Random Sample Survey-Compliance Check                                                                   | 1960  | 96822    | OAHU   | 956-8577 | 
| 1345827965  | Alu Like                                                       | Youth and Families Substance Abuse Prevention                                                                   | 458   | 96813    | OAHU   | 535-6700 | 
| 1345827965  | Hoa? Aina O Makaha                                             | Youth and Families Substance Abuse Prevention                                                                   |       | 96792    | OAHU   | 695-8978 | 
| 1345827965  | Hawaii County Police Department                                | 1)Enforcement of State law prohibiting Tobacco Sales to Minors; 2)Compliance checks for alcohol sales to minors | 349   | 96720    | Hawaii | 961-2254 | 
```