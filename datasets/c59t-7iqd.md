# Prevalence and Mean of Dental Caries (Cavities) among Maryland School Children, 2005-2006

## Dataset

* [Dataset URL](https://data.maryland.gov/api/views/c59t-7iqd/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/prevalence-and-mean-of-dental-caries-among-maryland-school-children-2005-2006-5d737)
* [Metadata URL](https://data.maryland.gov/api/views/c59t-7iqd)
* Id = c59t-7iqd
* Name = Prevalence and Mean of Dental Caries (Cavities) among Maryland School Children, 2005-2006
* Attribution = Survey of the Oral Health Status of Maryland School Children, 2005-2006. Office of Oral Health
* [Attribution Link](http://fha.dhmh.maryland.gov/oralhealth/docs1/Oral_Health_Survey_Report.pdf)
* Category = Health and Human Services
* Tags = [oral health, dental caries, dentist, dentalcare, toothache, children, office of oral health]
* Created = 2013-01-04T00:06:06Z
* Publication Date = 2013-01-04T17:46:46Z
* Rows Updated = 2013-01-04T17:43:47Z

## Description

This is the weighted prevalence of 1,276 schoolchildren.  1,276 out of 1,280 cases examined had prevalence available. One out of 1,276 cases had grade information missed, 564 were in Kindergarten and 711 in 3rd grade.  Prevalence is defined as occurrence of any caries among all selected population.  Mean is the average number of teeth with caries among students with caries in the selected population.  Region Identifiers and Constituent Counties:	
Western (Allegany, Frederick, Garrett, Washington); Central D.C. (Howard, Montgomery, Prince George?s); Southern (Calvert, Charles, St. Mary?s); Central Baltimore (Anne Arundel, Baltimore City, Baltimore County, Carroll, Harford); Eastern Shore (Caroline, Cecil, Dorchester, Kent, Queen Anne?s, Somerset, Talbot, Wicomico, Worcester).

## Columns

```ls
| Name                           | Field Name                   | Data Type | Render Type | Schema Type    | Included | 
| ============================== | ============================ | ========= | =========== | ============== | ======== | 
| updated_at                     | :updated_at                  | meta_data | meta_data   | time           | No       | 
| Characteristic                 | characteristic               | text      | text        | series tag     | Yes      | 
| Prevalence (%)                 | prevalence                   | number    | number      | numeric metric | Yes      | 
| Prevalence Standard Error (SE) | prevalence_standard_error_se | number    | number      | numeric metric | Yes      | 
| Mean                           | mean                         | number    | number      | numeric metric | Yes      | 
| Mean Standard Error (SE)       | mean_standard_error_se       | number    | number      | numeric metric | Yes      | 
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = 
Annotation Fields = 
```

## Data Commands

```ls
series e:c59t-7iqd d:2013-01-03T16:06:08.000Z t:characteristic=Overall m:mean_standard_error_se=0.2 m:prevalence=31.1 m:prevalence_standard_error_se=2.4 m:mean=2.7

series e:c59t-7iqd d:2013-01-03T16:06:08.000Z t:characteristic="Urban (region II, IV)" m:mean_standard_error_se=0.2 m:prevalence=31 m:prevalence_standard_error_se=3.5 m:mean=2.9

series e:c59t-7iqd d:2013-01-03T16:06:08.000Z t:characteristic="Rural (region I,III, V)" m:mean_standard_error_se=0.3 m:prevalence=31.1 m:prevalence_standard_error_se=3 m:mean=2.6
```

## Meta Commands

```ls
metric m:prevalence l:"Prevalence (%)" t:dataTypeName=number

metric m:prevalence_standard_error_se l:"Prevalence Standard Error (SE)" t:dataTypeName=number

metric m:mean l:Mean t:dataTypeName=number

metric m:mean_standard_error_se l:"Mean Standard Error (SE)" t:dataTypeName=number

entity e:c59t-7iqd l:"Prevalence and Mean of Dental Caries (Cavities) among Maryland School Children, 2005-2006" t:attribution="Survey of the Oral Health Status of Maryland School Children, 2005-2006. Office of Oral Health" t:url=https://data.maryland.gov/api/views/c59t-7iqd

property e:c59t-7iqd t:meta.view d:2017-03-08T01:56:37.645Z v:id=c59t-7iqd v:category="Health and Human Services" v:attributionLink=http://fha.dhmh.maryland.gov/oralhealth/docs1/Oral_Health_Survey_Report.pdf v:averageRating=0 v:name="Prevalence and Mean of Dental Caries (Cavities) among Maryland School Children, 2005-2006" v:attribution="Survey of the Oral Health Status of Maryland School Children, 2005-2006. Office of Oral Health"

property e:c59t-7iqd t:meta.view.owner d:2017-03-08T01:56:37.645Z v:id=e5tx-wz6d v:screenName="Andrea Bankoski" v:roleName=editor v:displayName="Andrea Bankoski"

property e:c59t-7iqd t:meta.view.tableauthor d:2017-03-08T01:56:37.645Z v:id=e5tx-wz6d v:screenName="Andrea Bankoski" v:roleName=editor v:displayName="Andrea Bankoski"
```