# Selected Trend Table from Health, United States, 2011. Diabetes prevalence and glycemic control among adults 20 years of age and over, by sex, age, and race and Hispanic origin: United States, sele...

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/selected-trend-table-from-health-united-states-2011-diabetes-prevalence-and-glycemic-contr-63c3a) |
| Metadata | [Link](https://data.cdc.gov/api/views/crtu-weni) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/crtu-weni/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/crtu-weni/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | crtu-weni |
| Name | Selected Trend Table from Health, United States, 2011. Diabetes prevalence and glycemic control among adults 20 years of age and over, by sex, age, and race and Hispanic origin: United States, sele... |
| Attribution | Health, United States |
| Category | Health Statistics |
| Tags | hus, diabetes, adults |
| Created | 2013-07-29T20:12:39Z |
| Publication Date | 2013-08-05T14:31:10Z |

## Description

Health, United States is an annual report on trends in health statistics, find more information at http://www.cdc.gov/nchs/hus.htm.

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type | Render Type |
| ======== | ============== | ================= | ================= | ========= | =========== |
| Yes      | series tag     | category          | Category          | text      | text        |
| Yes      | numeric metric | category_flag     | Category flag     | number    | number      |
| Yes      | series tag     | group             | Group             | text      | text        |
| Yes      | numeric metric | group_flag        | Group flag        | number    | number      |
| Yes      | series tag     | prevalence        | Prevalence        | text      | text        |
| Yes      | series tag     | prevalence_note   | Prevalence note   | text      | text        |
| Yes      | numeric metric | prevalence_flag_1 | Prevalence flag 1 | number    | number      |
| Yes      | numeric metric | prevalence_flag_2 | Prevalence flag 2 | number    | number      |
| Yes      | numeric metric | 1988_1994         | 1988-1994         | number    | number      |
| No       |                | 1988_1994_flag    | 1988-1994 flag    | text      | text        |
| Yes      | numeric metric | 1988_1994_se      | 1988-1994 SE      | number    | number      |
| No       |                | 1988_1994_se_flag | 1988-1994 SE flag | text      | text        |
| Yes      | numeric metric | 1999_2002         | 1999-2002         | number    | number      |
| No       |                | 1999_2002_flag    | 1999-2002 flag    | text      | text        |
| Yes      | numeric metric | 1999_2002_se      | 1999-2002 SE      | number    | number      |
| No       |                | 1999_2002_se_flag | 1999-2002 SE flag | text      | text        |
| Yes      | numeric metric | 2001_2004         | 2001-2004         | number    | number      |
| No       |                | 2001_2004_flag    | 2001-2004 flag    | text      | text        |
| Yes      | numeric metric | 2001_2004_se      | 2001-2004 SE      | number    | number      |
| No       |                | 2001_2004_se_flag | 2001-2004 SE flag | text      | text        |
| Yes      | numeric metric | 2003_2006         | 2003-2006         | number    | number      |
| No       |                | 2003_2006_flag    | 2003-2006 flag    | text      | text        |
| Yes      | numeric metric | 2003_2006_se      | 2003-2006 SE      | number    | number      |
| No       |                | 2003_2006_se_flag | 2003-2006 SE flag | text      | text        |
```

## Time Field

```ls
Value = 2011
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = 1988_1994_flag,1988_1994_se_flag,1999_2002_flag,1999_2002_se_flag,2001_2004_flag,2001_2004_se_flag,2003_2006_flag,2003_2006_se_flag
```

## Data Commands

```ls
series e:crtu-weni d:2011-01-01T00:00:00.000Z t:category="All persons" t:prevalence="Physician-diagnosed and undiagnosed diabetes" t:prevalence_note="Percent of population" t:group="20 years and over, age-adjusted" m:prevalence_flag_2=2 m:1999_2002=9.8 m:prevalence_flag_1=1 m:category_flag=5 m:2001_2004=10.7 m:1988_1994=9.1 m:group_flag=4 m:2003_2006_se=0.5 m:1988_1994_se=0.4 m:2003_2006=10.6 m:2001_2004_se=0.5 m:1999_2002_se=0.4

series e:crtu-weni d:2011-01-01T00:00:00.000Z t:category=Male t:prevalence="Physician-diagnosed and undiagnosed diabetes" t:prevalence_note="Percent of population" t:group="20 years and over, age-adjusted" m:prevalence_flag_2=2 m:1999_2002=10.8 m:prevalence_flag_1=1 m:2001_2004=12 m:1988_1994=9.6 m:group_flag=4 m:2003_2006_se=0.7 m:1988_1994_se=0.4 m:2003_2006=11.5 m:2001_2004_se=0.7 m:1999_2002_se=0.6

series e:crtu-weni d:2011-01-01T00:00:00.000Z t:category=Female t:prevalence="Physician-diagnosed and undiagnosed diabetes" t:prevalence_note="Percent of population" t:group="20 years and over, age-adjusted" m:prevalence_flag_2=2 m:1999_2002=8.8 m:prevalence_flag_1=1 m:2001_2004=9.5 m:1988_1994=8.7 m:group_flag=4 m:2003_2006_se=0.5 m:1988_1994_se=0.6 m:2003_2006=9.8 m:2001_2004_se=0.5 m:1999_2002_se=0.5
```

## Meta Commands

```ls
metric m:category_flag p:integer l:"Category flag" t:dataTypeName=number

metric m:group_flag p:integer l:"Group flag" t:dataTypeName=number

metric m:prevalence_flag_1 p:integer l:"Prevalence flag 1" t:dataTypeName=number

metric m:prevalence_flag_2 p:integer l:"Prevalence flag 2" t:dataTypeName=number

metric m:1988_1994 p:float l:1988-1994 t:dataTypeName=number

metric m:1988_1994_se p:float l:"1988-1994 SE" t:dataTypeName=number

metric m:1999_2002 p:float l:1999-2002 t:dataTypeName=number

metric m:1999_2002_se p:float l:"1999-2002 SE" t:dataTypeName=number

metric m:2001_2004 p:float l:2001-2004 t:dataTypeName=number

metric m:2001_2004_se p:float l:"2001-2004 SE" t:dataTypeName=number

metric m:2003_2006 p:float l:2003-2006 t:dataTypeName=number

metric m:2003_2006_se p:float l:"2003-2006 SE" t:dataTypeName=number

entity e:crtu-weni l:"Selected Trend Table from Health, United States, 2011. Diabetes prevalence and glycemic control among adults 20 years of age and over, by sex, age, and race and Hispanic origin: United States, selected years 1988 - 1994 through 2003 - 2006" t:attribution="Health, United States" t:url=https://data.cdc.gov/api/views/crtu-weni

property e:crtu-weni t:meta.view v:id=crtu-weni v:category="Health Statistics" v:attributionLink=http://www.cdc.gov/nchs/hus.htm v:averageRating=0 v:name="Selected Trend Table from Health, United States, 2011. Diabetes prevalence and glycemic control among adults 20 years of age and over, by sex, age, and race and Hispanic origin: United States, selected years 1988 - 1994 through 2003 - 2006" v:attribution="Health, United States"

property e:crtu-weni t:meta.view.owner v:id=vr5q-rutf v:screenName=SFranco v:displayName=SFranco

property e:crtu-weni t:meta.view.tableauthor v:id=g3fc-zmqn v:profileImageUrlMedium=/api/users/g3fc-zmqn/profile_images/THUMB v:profileImageUrlLarge=/api/users/g3fc-zmqn/profile_images/LARGE v:screenName=CDC v:profileImageUrlSmall=/api/users/g3fc-zmqn/profile_images/TINY v:roleName=publisher v:displayName=CDC

property e:crtu-weni t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:00 v:Program_Code=009:020
```

## Top Records

```ls
| category                                               | category_flag | group                           | group_flag | prevalence                                   | prevalence_note       | prevalence_flag_1 | prevalence_flag_2 | 1988_1994 | 1988_1994_flag | 1988_1994_se | 1988_1994_se_flag | 1999_2002 | 1999_2002_flag | 1999_2002_se | 1999_2002_se_flag | 2001_2004 | 2001_2004_flag | 2001_2004_se | 2001_2004_se_flag | 2003_2006 | 2003_2006_flag | 2003_2006_se | 2003_2006_se_flag | 
| ====================================================== | ============= | =============================== | ========== | ============================================ | ===================== | ================= | ================= | ========= | ============== | ============ | ================= | ========= | ============== | ============ | ================= | ========= | ============== | ============ | ================= | ========= | ============== | ============ | ================= | 
| All persons                                            | 5             | 20 years and over, age-adjusted | 4          | Physician-diagnosed and undiagnosed diabetes | Percent of population | 1                 | 2                 | 9.1       |                | 0.4          |                   | 9.8       |                | 0.4          |                   | 10.7      |                | 0.5          |                   | 10.6      |                | 0.5          |                   | 
| Male                                                   |               | 20 years and over, age-adjusted | 4          | Physician-diagnosed and undiagnosed diabetes | Percent of population | 1                 | 2                 | 9.6       |                | 0.4          |                   | 10.8      |                | 0.6          |                   | 12.0      |                | 0.7          |                   | 11.5      |                | 0.7          |                   | 
| Female                                                 |               | 20 years and over, age-adjusted | 4          | Physician-diagnosed and undiagnosed diabetes | Percent of population | 1                 | 2                 | 8.7       |                | 0.6          |                   | 8.8       |                | 0.5          |                   | 9.5       |                | 0.5          |                   | 9.8       |                | 0.5          |                   | 
| Not Hispanic or Latino: White only                     |               | 20 years and over, age-adjusted | 4          | Physician-diagnosed and undiagnosed diabetes | Percent of population | 1                 | 2                 | 8.0       |                | 0.4          |                   | 8.3       |                | 0.4          |                   | 9.1       |                | 0.5          |                   | 9.0       |                | 0.6          |                   | 
| Not Hispanic or Latino: Black or African American only |               | 20 years and over, age-adjusted | 4          | Physician-diagnosed and undiagnosed diabetes | Percent of population | 1                 | 2                 | 16.0      |                | 0.7          |                   | 16.3      |                | 1.0          |                   | 15.4      |                | 0.9          |                   | 16.4      |                | 0.9          |                   | 
| Mexican                                                |               | 20 years and over, age-adjusted | 4          | Physician-diagnosed and undiagnosed diabetes | Percent of population | 1                 | 2                 | 14.9      |                | 1.1          |                   | 13.2      |                | 0.7          |                   | 15.2      |                | 1.0          |                   | 16.3      |                | 1.2          |                   | 
| Percent of poverty level: Below 100%                   | 6             | 20 years and over, age-adjusted | 4          | Physician-diagnosed and undiagnosed diabetes | Percent of population | 1                 | 2                 | 14.2      |                | 1.1          |                   | 14.5      |                | 1.3          |                   | 14.8      |                | 1.3          |                   | 15.1      |                | 1.3          |                   | 
| Percent of poverty level: 100% or more                 | 6             | 20 years and over, age-adjusted | 4          | Physician-diagnosed and undiagnosed diabetes | Percent of population | 1                 | 2                 | 8.4       |                | 0.4          |                   | 8.9       |                | 0.5          |                   | 9.8       |                | 0.5          |                   | 9.9       |                | 0.6          |                   | 
| Percent of poverty level: 100%-199%                    | 6             | 20 years and over, age-adjusted | 4          | Physician-diagnosed and undiagnosed diabetes | Percent of population | 1                 | 2                 | 10.9      |                | 0.8          |                   | 12.6      |                | 1.1          |                   | 12.9      |                | 1.1          |                   | 13.3      |                | 1.1          |                   | 
| Percent of poverty level: 200% or more                 | 6             | 20 years and over, age-adjusted | 4          | Physician-diagnosed and undiagnosed diabetes | Percent of population | 1                 | 2                 | 7.7       |                | 0.5          |                   | 7.7       |                | 5.0          |                   | 8.8       |                | 0.6          |                   | 8.8       |                | 0.7          |                   | 
```