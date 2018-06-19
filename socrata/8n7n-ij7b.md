# Prevalence of Children with No Caries, Sealant or Restorations in Maryland School Children, 2005-2006

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/prevalence-of-children-with-no-caries-sealant-or-restorations-in-maryland-school-chil-2005-eefff) |
| Metadata | [Link](https://data.maryland.gov/api/views/8n7n-ij7b) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/8n7n-ij7b/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/8n7n-ij7b/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | 8n7n-ij7b |
| Name | Prevalence of Children with No Caries, Sealant or Restorations in Maryland School Children, 2005-2006 |
| Attribution | Survey of the Oral Health Status of Maryland School Children, 2005-2006. Office of Oral Health |
| Category | Health and Human Services |
| Tags | oral health, dental caries, dentist, dentalcare, dental, restorations, toothache, sealant, children, office of oral health |
| Created | 2013-01-04T18:12:32Z |
| Publication Date | 2013-01-04T18:15:09Z |

## Description

This is the weighted prevalence of 1,276 schoolchildren.  1,276 out of 1,280 cases examined had prevalence available.  One out of 1,276 cases had grade information missed, 564 were in Kindergarten and 711 in 3rd grade.  Prevalence is defined as occurrence of no caries, sealants, or restorations among all selected population.  Region Identifiers and Constituent Counties:	 Western (Allegany, Frederick, Garrett, Washington); Central D.C. (Howard, Montgomery, Prince George?s); Southern (Calvert, Charles, St. Mary?s); Central Baltimore (Anne Arundel, Baltimore City, Baltimore County, Carroll, Harford); Eastern Shore (Caroline, Cecil, Dorchester, Kent, Queen Anne?s, Somerset, Talbot, Wicomico, Worcester).

## Columns

```ls
| Included | Schema Type    | Field Name                   | Name                           | Data Type | Render Type |
| ======== | ============== | ============================ | ============================== | ========= | =========== |
| Yes      | series tag     | characteristic               | Characteristic                 | text      | text        |
| Yes      | numeric metric | prevalence                   | Prevalence (%)                 | number    | number      |
| Yes      | numeric metric | prevalence_standard_error_se | Prevalence Standard Error (SE) | number    | number      |
```

## Time Field

```ls
Value = 2005
Format & Zone = yyyy
```

## Data Commands

```ls
series e:8n7n-ij7b d:2005-01-01T00:00:00.000Z t:characteristic=Overall m:prevalence=39 m:prevalence_standard_error_se=3

series e:8n7n-ij7b d:2005-01-01T00:00:00.000Z t:characteristic="Urban (region II, IV)" m:prevalence=36.4 m:prevalence_standard_error_se=3.7

series e:8n7n-ij7b d:2005-01-01T00:00:00.000Z t:characteristic="Rural (region I,III, V)" m:prevalence=39.9 m:prevalence_standard_error_se=3.8
```

## Meta Commands

```ls
metric m:prevalence p:float l:"Prevalence (%)" t:dataTypeName=number

metric m:prevalence_standard_error_se p:float l:"Prevalence Standard Error (SE)" t:dataTypeName=number

entity e:8n7n-ij7b l:"Prevalence of Children with No Caries, Sealant or Restorations in Maryland School Children, 2005-2006" t:attribution="Survey of the Oral Health Status of Maryland School Children, 2005-2006. Office of Oral Health" t:url=https://data.maryland.gov/api/views/8n7n-ij7b

property e:8n7n-ij7b t:meta.view v:id=8n7n-ij7b v:category="Health and Human Services" v:attributionLink=http://fha.dhmh.maryland.gov/oralhealth/docs1/Oral_Health_Survey_Report.pdf v:averageRating=0 v:name="Prevalence of Children with No Caries, Sealant or Restorations in Maryland School Children, 2005-2006" v:attribution="Survey of the Oral Health Status of Maryland School Children, 2005-2006. Office of Oral Health"

property e:8n7n-ij7b t:meta.view.owner v:id=e5tx-wz6d v:screenName="Andrea Bankoski" v:displayName="Andrea Bankoski"

property e:8n7n-ij7b t:meta.view.tableauthor v:id=e5tx-wz6d v:screenName="Andrea Bankoski" v:roleName=editor v:displayName="Andrea Bankoski"
```

## Top Records

```ls
| characteristic          | prevalence | prevalence_standard_error_se | 
| ======================= | ========== | ============================ | 
| Overall                 | 39.0       | 3.0                          | 
| Municipality            |            |                              | 
| Urban (region II, IV)   | 36.4       | 3.7                          | 
| Rural (region I,III, V) | 39.9       | 3.8                          | 
| Region                  |            |                              | 
| I ? Western             | 28.4       | 5.1                          | 
| II ? Central DC         | 33.7       | 4.7                          | 
| III ? Southern          | 37.4       | 6.0                          | 
| IV ? Central Baltimore  | 45.6       | 4.4                          | 
| V ? Eastern Shore       | 42.8       | 5.4                          | 
```