# CDC STATE System Tobacco Legislation - Tax

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cdc-state-system-tobacco-legislation-tax-e7afb) |
| Metadata | [Link](https://data.cdc.gov/api/views/2dwv-vfam) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/2dwv-vfam/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/2dwv-vfam/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | 2dwv-vfam |
| Name | CDC STATE System Tobacco Legislation - Tax |
| Attribution | Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Office on Smoking and Health |
| Category | Legislation |
| Tags | tobacco, osh, state system, legislation, policy, tax |
| Created | 2014-07-14T13:49:27Z |
| Publication Date | 2017-02-16T17:22:53Z |

## Description

1995-2017. Centers for Disease Control and Prevention (CDC). State Tobacco Activities Tracking and Evaluation (STATE) System.  Legislation-Tax. The STATE System houses current and historical state-level legislative data on tobacco use prevention and control policies. Data are reported on a quarterly basis. Data include state taxes on combustible, non-combustible (smokeless) tobacco products, and tax stamps. Combustible tobacco products include cigarettes, cigars, little cigars, pipe tobacco, and roll-your-own tobacco. Non-combustible tobacco products include snus, moist snuff, dry snuff, chewing tobacco, and dissolvables. Tax stamps are on packs of cigarettes.

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type | Render Type |
| ======== | ============== | ================== | ================== | ========= | =========== |
| No       |                | year               | Year               | number    | number      |
| No       |                | quarter            | Quarter            | number    | number      |
| Yes      | series tag     | locationabbr       | LocationAbbr       | text      | text        |
| Yes      | series tag     | locationdesc       | LocationDesc       | text      | text        |
| Yes      | series tag     | topicdesc          | TopicDesc          | text      | text        |
| Yes      | series tag     | measuredesc        | MeasureDesc        | text      | text        |
| Yes      | series tag     | datasource         | DataSource         | text      | text        |
| Yes      | series tag     | provisiongroupdesc | ProvisionGroupDesc | text      | text        |
| Yes      | series tag     | provisiondesc      | ProvisionDesc      | text      | text        |
| Yes      | series tag     | provisionvalue     | ProvisionValue     | text      | text        |
| Yes      | series tag     | citation           | Citation           | text      | text        |
| Yes      | numeric metric | provisionaltvalue  | ProvisionAltValue  | number    | number      |
| Yes      | series tag     | datatype           | DataType           | text      | text        |
| Yes      | series tag     | comments           | Comments           | text      | text        |
| No       |                | enacted_date       | Enacted_Date       | text      | text        |
| No       |                | effective_date     | Effective_Date     | text      | text        |
| No       |                | displayorder       | DisplayOrder       | number    | number      |
| Yes      | series tag     | topictypeid        | TopicTypeId        | text      | text        |
| Yes      | series tag     | topicid            | TopicId            | text      | text        |
| Yes      | series tag     | measureid          | MeasureId          | text      | text        |
| Yes      | series tag     | provisiongroupid   | ProvisionGroupID   | text      | text        |
| Yes      | series tag     | provisionid        | ProvisionID        | text      | number      |
```

## Time Field

```ls
Value = year-quarter
Format & Zone = yyyy-q
```

## Series Fields

```ls
Excluded Fields = enacted_date,effective_date,displayorder,year,quarter
```

## Data Commands

```ls
series e:2dwv-vfam d:2015-07-01T00:00:00.000Z t:locationabbr=AL t:locationdesc=Alabama t:topicid=1010LEG t:provisiondesc="Percent Value" t:measureid=671CIG t:measuredesc=Cigar t:provisiongroupdesc=Restrictions t:provisiongroupid=10GRP t:provisionvalue="No Provision" t:provisionid=414 t:topicdesc="Legislation - Tax Combustible Tobacco" t:datatype=Number t:datasource=OSH t:topictypeid=LEG m:provisionaltvalue=0

series e:2dwv-vfam d:2015-07-01T00:00:00.000Z t:locationabbr=AL t:locationdesc=Alabama t:topicid=1030LEG t:provisiondesc="Barcode/Scannable Code Required" t:measureid=690CET t:measuredesc="Tax Stamp" t:provisiongroupdesc=Requirements t:provisiongroupid=12GRP t:provisionvalue="No Provision" t:provisionid=350 t:topicdesc="Legislation - Tax Stamp" t:datatype=Ranking t:datasource=OSH t:topictypeid=LEG m:provisionaltvalue=0

series e:2dwv-vfam d:2015-07-01T00:00:00.000Z t:locationabbr=AL t:locationdesc=Alabama t:topicid=1020LEG t:provisiondesc="Percent Value" t:measureid=681EMS t:measuredesc="Moist Snuff Tobacco" t:provisiongroupdesc=Restrictions t:provisiongroupid=10GRP t:provisionvalue="No Provision" t:provisionid=390 t:topicdesc="Legislation - Tax Non-Combustible Tobacco" t:datatype=Number t:datasource=OSH t:topictypeid=LEG m:provisionaltvalue=0
```

## Meta Commands

```ls
metric m:provisionaltvalue p:double l:ProvisionAltValue d:"Alternate numeric value for non-numeric provision value; used for mapping and graphing" t:dataTypeName=number

entity e:2dwv-vfam l:"CDC STATE System Tobacco Legislation - Tax" t:attribution="Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Office on Smoking and Health" t:url=https://data.cdc.gov/api/views/2dwv-vfam

property e:2dwv-vfam t:meta.view v:id=2dwv-vfam v:category=Legislation v:attributionLink=http://www.cdc.gov/STATESystem/ v:averageRating=0 v:name="CDC STATE System Tobacco Legislation - Tax" v:attribution="Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Office on Smoking and Health"

property e:2dwv-vfam t:meta.view.license v:name="Public Domain"

property e:2dwv-vfam t:meta.view.owner v:id=p5wh-zttj v:profileImageUrlMedium=/api/users/p5wh-zttj/profile_images/THUMB v:profileImageUrlLarge=/api/users/p5wh-zttj/profile_images/LARGE v:screenName=OSHData v:profileImageUrlSmall=/api/users/p5wh-zttj/profile_images/TINY v:displayName=OSHData

property e:2dwv-vfam t:meta.view.tableauthor v:id=p5wh-zttj v:profileImageUrlMedium=/api/users/p5wh-zttj/profile_images/THUMB v:profileImageUrlLarge=/api/users/p5wh-zttj/profile_images/LARGE v:screenName=OSHData v:profileImageUrlSmall=/api/users/p5wh-zttj/profile_images/TINY v:roleName=administrator v:displayName=OSHData

property e:2dwv-vfam t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:20 v:Program_Code=009:020
```

## Top Records

```ls
| year | quarter | locationabbr | locationdesc | topicdesc                                 | measuredesc         | datasource | provisiongroupdesc | provisiondesc                         | provisionvalue | citation | provisionaltvalue | datatype | comments | enacted_date | effective_date | displayorder | topictypeid | topicid | measureid | provisiongroupid | provisionid | 
| ==== | ======= | ============ | ============ | ========================================= | =================== | ========== | ================== | ===================================== | ============== | ======== | ================= | ======== | ======== | ============ | ============== | ============ | =========== | ======= | ========= | ================ | =========== | 
| 2015 | 3       | AL           | Alabama      | Legislation - Tax Combustible Tobacco     | Cigar               | OSH        | Restrictions       | Percent Value                         | No Provision   |          | 0                 | Number   |          |              |                | 3            | LEG         | 1010LEG | 671CIG    | 10GRP            | 414         | 
| 2015 | 3       | AL           | Alabama      | Legislation - Tax Stamp                   | Tax Stamp           | OSH        | Requirements       | Barcode/Scannable Code Required       | No Provision   |          | 0                 | Ranking  |          |              |                | 2            | LEG         | 1030LEG | 690CET    | 12GRP            | 350         | 
| 2015 | 3       | AL           | Alabama      | Legislation - Tax Non-Combustible Tobacco | Moist Snuff Tobacco | OSH        | Restrictions       | Percent Value                         | No Provision   |          | 0                 | Number   |          |              |                | 3            | LEG         | 1020LEG | 681EMS    | 10GRP            | 390         | 
| 2015 | 3       | AL           | Alabama      | Legislation - Tax Non-Combustible Tobacco | Dry Snuff Tobacco   | OSH        | Restrictions       | Percent Value                         | No Provision   |          | 0                 | Number   |          |              |                | 3            | LEG         | 1020LEG | 682EDS    | 10GRP            | 394         | 
| 2015 | 3       | AL           | Alabama      | Legislation - Tax Combustible Tobacco     | Cigar               | OSH        | Restrictions       | Cigar Tax                             | Yes            |          | 2                 | Yes/No   |          |              |                | 1            | LEG         | 1010LEG | 671CIG    | 10GRP            | 412         | 
| 2015 | 3       | AL           | Alabama      | Legislation - Tax Non-Combustible Tobacco | Snus Tobacco        | OSH        | Restrictions       | Snus Tobacco Tax                      | No Provision   |          | 0                 | Yes/No   |          |              |                | 1            | LEG         | 1020LEG | 683EST    | 10GRP            | 396         | 
| 2015 | 3       | AL           | Alabama      | Legislation - Tax Combustible Tobacco     | Little Cigar        | OSH        | Restrictions       | Type of Tax                           | No Provision   |          | 0                 |          |          |              |                | 4            | LEG         | 1010LEG | 672LCG    | 10GRP            | 419         | 
| 2015 | 3       | AL           | Alabama      | Legislation - Tax Non-Combustible Tobacco | Dissolvable Tobacco | OSH        | Restrictions       | Dissolvable Tobacco Tax               | No Provision   |          | 0                 | Yes/No   |          |              |                | 1            | LEG         | 1020LEG | 684EDT    | 10GRP            | 400         | 
| 2015 | 3       | AL           | Alabama      | Legislation - Tax Stamp                   | Tax Stamp           | OSH        | Requirements       | Encrypted Image/Hologram Required     | No Provision   |          | 0                 | Ranking  |          |              |                | 3            | LEG         | 1030LEG | 690CET    | 12GRP            | 351         | 
| 2015 | 3       | AL           | Alabama      | Legislation - Tax Non-Combustible Tobacco | Dissolvable Tobacco | OSH        | Restrictions       | Dissolvable Tobacco Tax ($ per ounce) | No Provision   |          | 0                 | Money    |          |              |                | 2            | LEG         | 1020LEG | 684EDT    | 10GRP            | 401         | 
```