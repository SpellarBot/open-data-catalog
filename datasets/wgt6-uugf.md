# Prevalence and Mean of Dental Sealants among Maryland School Children, 2005-2006

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/prevalence-and-mean-of-dental-sealants-among-maryland-school-children-2005-2006-12037) |
| Metadata | [Link](https://data.maryland.gov/api/views/wgt6-uugf) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/wgt6-uugf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/wgt6-uugf/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | wgt6-uugf |
| Name | Prevalence and Mean of Dental Sealants among Maryland School Children, 2005-2006 |
| Attribution | Survey of the Oral Health Status of Maryland School Children, 2005-2006. Office of Oral Health |
| Category | Health and Human Services |
| Tags | oral health, dental caries, dentist, dentalcare, dental, sealant, toothache, children, office of oral health |
| Created | 2013-01-04T01:06:41Z |
| Publication Date | 2013-01-04T17:43:32Z |

## Description

This is the weighted prevalence of 1,276 schoolchildren. 1,276 out of 1,280 cases examined had prevalence available. One out of 1,276 cases had grade information missed, 564 were in Kindergarten and 711 in 3rd grade. Prevalence is defined as occurrence of any sealant among all selected population. Mean is the average number of teeth with sealant among students with sealant in selected population. Region Identifiers and Constituent Counties:	 Western (Allegany, Frederick, Garrett, Washington); Central D.C. (Howard, Montgomery, Prince George?s); Southern (Calvert, Charles, St. Mary?s); Central Baltimore (Anne Arundel, Baltimore City, Baltimore County, Carroll, Harford); Eastern Shore (Caroline, Cecil, Dorchester, Kent, Queen Anne?s, Somerset, Talbot, Wicomico, Worcester).

## Columns

```ls
| Included | Schema Type    | Field Name                   | Name                           | Data Type | Render Type |
| ======== | ============== | ============================ | ============================== | ========= | =========== |
| Yes      | series tag     | characteristic               | Characteristic                 | text      | text        |
| Yes      | numeric metric | prevalence                   | Prevalence (%)                 | number    | number      |
| Yes      | numeric metric | prevalence_standard_error_se | Prevalence Standard Error (SE) | number    | number      |
| Yes      | numeric metric | mean                         | Mean                           | number    | number      |
| Yes      | numeric metric | mean_standard_error_se       | Mean Standard Error (SE)       | number    | number      |
```

## Time Field

```ls
Value = 2005
Format & Zone = yyyy
```

## Data Commands

```ls
series e:wgt6-uugf d:2005-01-01T00:00:00.000Z t:characteristic=Overall m:mean_standard_error_se=0.2 m:prevalence=26.8 m:prevalence_standard_error_se=3.6 m:mean=3

series e:wgt6-uugf d:2005-01-01T00:00:00.000Z t:characteristic="Urban (region II, IV)" m:mean_standard_error_se=0.2 m:prevalence=28.8 m:prevalence_standard_error_se=4.5 m:mean=3.1

series e:wgt6-uugf d:2005-01-01T00:00:00.000Z t:characteristic="Rural (region I,III, V)" m:mean_standard_error_se=0.2 m:prevalence=26.1 m:prevalence_standard_error_se=4.5 m:mean=3
```

## Meta Commands

```ls
metric m:prevalence p:float l:"Prevalence (%)" t:dataTypeName=number

metric m:prevalence_standard_error_se p:float l:"Prevalence Standard Error (SE)" t:dataTypeName=number

metric m:mean p:float l:Mean t:dataTypeName=number

metric m:mean_standard_error_se p:float l:"Mean Standard Error (SE)" t:dataTypeName=number

entity e:wgt6-uugf l:"Prevalence and Mean of Dental Sealants among Maryland School Children, 2005-2006" t:attribution="Survey of the Oral Health Status of Maryland School Children, 2005-2006. Office of Oral Health" t:url=https://data.maryland.gov/api/views/wgt6-uugf

property e:wgt6-uugf t:meta.view v:id=wgt6-uugf v:category="Health and Human Services" v:attributionLink=http://fha.dhmh.maryland.gov/oralhealth/docs1/Oral_Health_Survey_Report.pdf v:averageRating=0 v:name="Prevalence and Mean of Dental Sealants among Maryland School Children, 2005-2006" v:attribution="Survey of the Oral Health Status of Maryland School Children, 2005-2006. Office of Oral Health"

property e:wgt6-uugf t:meta.view.owner v:id=e5tx-wz6d v:screenName="Andrea Bankoski" v:displayName="Andrea Bankoski"

property e:wgt6-uugf t:meta.view.tableauthor v:id=e5tx-wz6d v:screenName="Andrea Bankoski" v:roleName=editor v:displayName="Andrea Bankoski"
```

## Top Records

```ls
| characteristic          | prevalence | prevalence_standard_error_se | mean | mean_standard_error_se | 
| ======================= | ========== | ============================ | ==== | ====================== | 
| Overall                 | 26.8       | 3.6                          | 3.0  | 0.2                    | 
| Municipality            |            |                              |      |                        | 
| Urban (region II, IV)   | 28.8       | 4.5                          | 3.1  | 0.2                    | 
| Rural (region I,III, V) | 26.1       | 4.5                          | 3.0  | 0.2                    | 
| Region                  |            |                              |      |                        | 
| I ? Western             | 43.1       | 4.6                          | 3.5  | 0.1                    | 
| II ? Central DC         | 34.7       | 5.7                          | 2.9  | 0.2                    | 
| III ? Southern          | 34.8       | 9.2                          | 3.0  | 0.1                    | 
| IV ? Central Baltimore  | 18.3       | 5.3                          | 3.1  | 0.3                    | 
| V ? Eastern Shore       | 14.6       | 4.1                          | 2.3  | 0.2                    | 
```