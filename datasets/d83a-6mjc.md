# Oregon Juvenile Referrals 2008 - 2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/oregon-juvenile-referrals-2008-2010-13ca5) |
| Metadata | [Link](https://data.oregon.gov/api/views/d83a-6mjc) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/d83a-6mjc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/d83a-6mjc/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | d83a-6mjc |
| Name | Oregon Juvenile Referrals 2008 - 2010 |
| Attribution | Oregon Youth Authority |
| Category | Public Safety |
| Tags | criminal, delinquency, oya, youth authority, crime, arrest, offense, juvenile, corrections, close custody |
| Created | 2011-08-18T22:47:28Z |
| Publication Date | 2011-08-18T22:47:28Z |

## Description

This dataset contains delinquency and criminal referrals of Oregon youth to county juvenile departments between 2008 and 2010. Referrals in the juvenile justice system are analogous to arrests in the adult system. Each row in this dataset represents a unique referral and includes demographic information about the referred youth. Youth may be referred multiple times; hence, some youth are associated with multiple referrals in this data set.    For more information please go to:  http://www.oregon.gov/OYA/jjis_data_eval

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                       | Data Type | Render Type |
| ======== | ============== | ========================== | ========================== | ========= | =========== |
| Yes      | numeric metric | record_count               | RECORD COUNT               | number    | number      |
| Yes      | series tag     | sex                        | SEX                        | text      | text        |
| Yes      | numeric metric | age_at_referral            | AGE AT REFERRAL            | number    | number      |
| Yes      | time           | referral_year              | REFERRAL YEAR              | number    | text        |
| Yes      | series tag     | race_ethnicity             | RACE/ETHNICITY             | text      | text        |
| Yes      | series tag     | ors_class_code             | ORS CLASS CODE             | text      | text        |
| Yes      | series tag     | referral_county            | REFERRAL COUNTY            | text      | text        |
| Yes      | series tag     | ors_type_code              | ORS TYPE CODE              | text      | text        |
| Yes      | series tag     | offense_category_rollup    | OFFENSE CATEGORY ROLLUP    | text      | text        |
| Yes      | series tag     | offense_type               | OFFENSE TYPE               | text      | text        |
| Yes      | series tag     | youth_zip_code_at_referral | YOUTH ZIP CODE AT REFERRAL | text      | text        |
```

## Time Field

```ls
Value = referral_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:d83a-6mjc d:2008-01-01T00:00:00.000Z t:offense_type=Criminal t:referral_county=Marion t:sex=Male t:ors_class_code=B t:ors_type_code=FEL t:youth_zip_code_at_referral=97301 t:race_ethnicity=White t:offense_category_rollup=Assault m:record_count=1 m:age_at_referral=14

series e:d83a-6mjc d:2008-01-01T00:00:00.000Z t:offense_type=Criminal t:referral_county=Marion t:sex=Male t:ors_class_code=C t:ors_type_code=MIS t:youth_zip_code_at_referral=97302 t:race_ethnicity=Hispanic t:offense_category_rollup="Criminal Other" m:record_count=1 m:age_at_referral=17

series e:d83a-6mjc d:2008-01-01T00:00:00.000Z t:offense_type=Non-Criminal t:referral_county=Clackamas t:sex=Female t:ors_class_code=B t:ors_type_code=VIO t:youth_zip_code_at_referral=97068 t:race_ethnicity=Asian t:offense_category_rollup=Alcohol/MIP m:record_count=1 m:age_at_referral=17
```

## Meta Commands

```ls
metric m:record_count p:integer l:"RECORD COUNT" t:dataTypeName=number

metric m:age_at_referral p:integer l:"AGE AT REFERRAL" t:dataTypeName=number

entity e:d83a-6mjc l:"Oregon Juvenile Referrals 2008 - 2010" t:attribution="Oregon Youth Authority" t:url=https://data.oregon.gov/api/views/d83a-6mjc

property e:d83a-6mjc t:meta.view v:id=d83a-6mjc v:category="Public Safety" v:attributionLink=http://www.oregon.gov/OYA/jjis_data_eval_rpts.shtml v:averageRating=100 v:name="Oregon Juvenile Referrals 2008 - 2010" v:attribution="Oregon Youth Authority"

property e:d83a-6mjc t:meta.view.license v:name="Public Domain"

property e:d83a-6mjc t:meta.view.owner v:id=hzrd-8zyp v:screenName="Willie Rhodes" v:displayName="Willie Rhodes"

property e:d83a-6mjc t:meta.view.tableauthor v:id=hzrd-8zyp v:screenName="Willie Rhodes" v:roleName=editor v:displayName="Willie Rhodes"
```

## Top Records

```ls
| record_count | sex    | age_at_referral | referral_year | race_ethnicity | ors_class_code | referral_county | ors_type_code | offense_category_rollup | offense_type              | youth_zip_code_at_referral | 
| ============ | ====== | =============== | ============= | ============== | ============== | =============== | ============= | ======================= | ========================= | ========================== | 
| 1            | Male   | 14              | 2008          | White          | B              | Marion          | FEL           | Assault                 | Criminal                  | 97301                      | 
| 1            | Male   | 17              | 2008          | Hispanic       | C              | Marion          | MIS           | Criminal Other          | Criminal                  | 97302                      | 
| 1            | Female | 17              | 2008          | Asian          | B              | Clackamas       | VIO           | Alcohol/MIP             | Non-Criminal              | 97068                      | 
| 1            | Male   | 16              | 2008          | White          | B              | Clackamas       | VIO           | Alcohol/MIP             | Non-Criminal              | 97013                      | 
| 1            | Female | 16              | 2008          | White          | C              | Morrow          | FEL           | Assault                 | Criminal                  | 97844                      | 
| 1            | Male   | 16              | 2008          | White          | A              | Benton          | FEL           | Burglary                | Criminal                  | 97370                      | 
| 1            | Male   | 17              | 2008          | White          | C              | Jackson         | FEL           | Assault                 | Criminal                  | 97524                      | 
| 1            | Male   | 12              | 2008          | White          |                | Deschutes       | DST           | Runaway                 | Dependency Status Offense | 97702                      | 
| 1            | Male   | 16              | 2008          | Hispanic       | A              | Yamhill         | MIS           | Criminal Other          | Criminal                  | 97128                      | 
| 1            | Male   | 16              | 2008          | White          | A              | Deschutes       | MIS           | Criminal Other          | Criminal                  | 97701                      | 
```