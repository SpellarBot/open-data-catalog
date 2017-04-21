# NCHS - Potentially Excess Deaths from the Five Leading Causes of Death

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nchs-potentially-excess-deaths-from-the-five-leading-causes-of-death) |
| Metadata | [Link](https://data.cdc.gov/api/views/vdpk-qzpr) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/vdpk-qzpr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/vdpk-qzpr/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | vdpk-qzpr |
| Name | NCHS - Potentially Excess Deaths from the Five Leading Causes of Death |
| Attribution | National Center for Health Statistics |
| Category | NCHS |
| Tags | heart disease, cancer, unintentional injury, chronic lower respiratory disease, stroke |
| Created | 2017-01-19T16:25:08Z |
| Publication Date | 2017-01-19T16:31:07Z |

## Description

http://blogs.cdc.gov/nchs-data-visualization/?p=428

State Data Accompanying MMWR Surveillance Summary 66(No. SS-1):1-8: Potentially Excess Deaths from the Five Leading Causes of Death in Nonmetropolitan and Metropolitan Areas, United States, 2005-2015

## Columns

```ls
| Included | Schema Type    | Field Name                | Name                      | Data Type | Render Type |
| ======== | ============== | ========================= | ========================= | ========= | =========== |
| Yes      | time           | year                      | Year                      | number    | text        |
| Yes      | series tag     | cause_of_death            | Cause of Death            | text      | text        |
| Yes      | series tag     | state                     | State                     | text      | text        |
| Yes      | series tag     | state_fips_code           | State FIPS Code           | text      | text        |
| Yes      | numeric metric | hhs_region                | HHS Region                | number    | number      |
| Yes      | series tag     | age_range                 | Age Range                 | text      | text        |
| Yes      | series tag     | benchmark                 | Benchmark                 | text      | text        |
| Yes      | series tag     | locality                  | Locality                  | text      | text        |
| Yes      | numeric metric | observed_deaths           | Observed Deaths           | number    | number      |
| Yes      | numeric metric | population                | Population                | number    | number      |
| Yes      | numeric metric | expected_deaths           | Expected Deaths           | number    | number      |
| Yes      | numeric metric | potentially_excess_deaths | Potentially Excess Deaths | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:vdpk-qzpr d:2005-01-01T00:00:00.000Z t:cause_of_death="Heart Disease" t:benchmark=Floating t:state_fips_code=VT t:state=Vermont t:locality=All t:age_range=0-54 m:potentially_excess_deaths=1.230012 m:observed_deaths=78 m:hhs_region=1 m:expected_deaths=76.951727 m:population=465112

series e:vdpk-qzpr d:2005-01-01T00:00:00.000Z t:cause_of_death="Heart Disease" t:benchmark=Floating t:state_fips_code=WY t:state=Wyoming t:locality=All t:age_range=0-54 m:potentially_excess_deaths=28.199256 m:observed_deaths=90 m:hhs_region=8 m:expected_deaths=61.800744 m:population=393845

series e:vdpk-qzpr d:2005-01-01T00:00:00.000Z t:cause_of_death="Heart Disease" t:benchmark=Floating t:state_fips_code=ND t:state="North Dakota" t:locality=All t:age_range=0-54 m:potentially_excess_deaths=17.987154 m:observed_deaths=91 m:hhs_region=8 m:expected_deaths=73.012846 m:population=487085
```

## Meta Commands

```ls
metric m:hhs_region p:integer l:"HHS Region" t:dataTypeName=number

metric m:observed_deaths p:integer l:"Observed Deaths" t:dataTypeName=number

metric m:population p:integer l:Population t:dataTypeName=number

metric m:expected_deaths p:double l:"Expected Deaths" t:dataTypeName=number

metric m:potentially_excess_deaths p:float l:"Potentially Excess Deaths" t:dataTypeName=number

entity e:vdpk-qzpr l:"NCHS - Potentially Excess Deaths from the Five Leading Causes of Death" t:attribution="National Center for Health Statistics" t:url=https://data.cdc.gov/api/views/vdpk-qzpr

property e:vdpk-qzpr t:meta.view v:id=vdpk-qzpr v:category=NCHS v:attributionLink="http://blogs.cdc.gov/nchs-data-visualization/?p=428" v:averageRating=0 v:name="NCHS - Potentially Excess Deaths from the Five Leading Causes of Death" v:attribution="National Center for Health Statistics"

property e:vdpk-qzpr t:meta.view.owner v:id=ki96-txhe v:profileImageUrlMedium=/api/users/ki96-txhe/profile_images/THUMB v:profileImageUrlLarge=/api/users/ki96-txhe/profile_images/LARGE v:screenName=hku4@cdc.gov v:profileImageUrlSmall=/api/users/ki96-txhe/profile_images/TINY v:displayName=hku4@cdc.gov

property e:vdpk-qzpr t:meta.view.tableauthor v:id=ki96-txhe v:profileImageUrlMedium=/api/users/ki96-txhe/profile_images/THUMB v:profileImageUrlLarge=/api/users/ki96-txhe/profile_images/LARGE v:screenName=hku4@cdc.gov v:profileImageUrlSmall=/api/users/ki96-txhe/profile_images/TINY v:roleName=administrator v:displayName=hku4@cdc.gov

property e:vdpk-qzpr t:meta.view.metadata.custom_fields.common_core v:Contact_Email=hku4@cdc.gov v:Publisher="National Center for Health Statistics" v:Contact_Name=NCHS v:Bureau_Code=009:000 v:Program_Code=009:020
```

## Top Records

```ls
| year | cause_of_death | state                | state_fips_code | hhs_region | age_range | benchmark | locality | observed_deaths | population | expected_deaths | potentially_excess_deaths | 
| ==== | ============== | ==================== | =============== | ========== | ========= | ========= | ======== | =============== | ========== | =============== | ========================= | 
| 2005 | Heart Disease  | Vermont              | VT              | 1          | 0-54      | Floating  | All      | 78              | 465112     | 76.951727       | 1.230012                  | 
| 2005 | Heart Disease  | Wyoming              | WY              | 8          | 0-54      | Floating  | All      | 90              | 393845     | 61.800744       | 28.199256                 | 
| 2005 | Heart Disease  | North Dakota         | ND              | 8          | 0-54      | Floating  | All      | 91              | 487085     | 73.012846       | 17.987154                 | 
| 2005 | Heart Disease  | Alaska               | AK              | 10         | 0-54      | Floating  | All      | 111             | 557494     | 84.125008       | 26.874992                 | 
| 2005 | Heart Disease  | South Dakota         | SD              | 8          | 0-54      | Floating  | All      | 117             | 587870     | 86.473173       | 30.526827                 | 
| 2005 | Heart Disease  | Montana              | MT              | 8          | 0-54      | Floating  | All      | 158             | 699822     | 112.01369       | 45.986308                 | 
| 2005 | Heart Disease  | Delaware             | DE              | 3          | 0-54      | Floating  | All      | 171             | 639944     | 95.673223       | 75.326777                 | 
| 2005 | Heart Disease  | District of Columbia | DC              | 3          | 0-54      | Floating  | All      | 172             | 442285     | 61.008759       | 110.99124                 | 
| 2005 | Heart Disease  | New Hampshire        | NH              | 1          | 0-54      | Floating  | All      | 174             | 993879     | 162.56858       | 11.431415                 | 
| 2005 | Heart Disease  | Idaho                | ID              | 10         | 0-54      | Floating  | All      | 185             | 1119878    | 154.92111       | 32.072432                 | 
```