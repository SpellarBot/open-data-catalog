# WA RCO SCORP 2013 Field Definitions

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/wa-rco-scorp-2013-field-definitions-507fc) |
| Metadata | [Link](https://data.wa.gov/api/views/yr5j-kyei) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/yr5j-kyei/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/yr5j-kyei/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | yr5j-kyei |
| Name | WA RCO SCORP 2013 Field Definitions |
| Attribution | Washington State Recreation and Conservation Office (WA RCO) |
| Category | Recreation |
| Tags | washington, state, wa, recreation, conservation, office, rco, comprehensive, outdoor, plan, scorp, 2013, national park service, nps |
| Created | 2013-10-31T22:02:36Z |
| Publication Date | 2013-10-31T22:06:45Z |

## Description

This dataset is a survey of outdoor recreation demand which includes responses from 3,114 residents of Washington state who were interviewed by phone between August 27 and October 26, 2012. The telephone survey was conducted using random digit dialing.  To meet the regional planning requirements of the project, the sample was stratified by the 10 planning regions in Washington (see the 2013 SCORP Plan, Appendix A for survey methodology and map). The consultant obtained a minimum of 300 completed interviews in each region.  Within each region, the results were weighted by demographic characteristics so that the sample was representative of residents of that region.  For statewide results, each region was weighted to be in proper proportion to the state population as a whole.  Study findings are representative at the statewide level as well as by planning region.  Any manipulation or analysis of the data should take this sampling approach and weighting into account.

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type | Render Type |
| ======== | ============== | =============== | =============== | ========= | =========== |
| Yes      | numeric metric | datasetpart     | DatasetPart     | number    | number      |
| Yes      | series tag     | fieldname       | FieldName       | text      | text        |
| Yes      | series tag     | fielddefinition | FieldDefinition | text      | text        |
| Yes      | numeric metric | fieldorder      | FieldOrder      | number    | number      |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Data Commands

```ls
series e:yr5j-kyei d:2013-01-01T00:00:00.000Z t:fielddefinition="Respondent's Tracking (ID) Number" t:fieldname=IDNUMBER m:datasetpart=1 m:fieldorder=1

series e:yr5j-kyei d:2013-01-01T00:00:00.000Z t:fielddefinition="Low weight" t:fieldname=LOWEIGHT m:datasetpart=1 m:fieldorder=2

series e:yr5j-kyei d:2013-01-01T00:00:00.000Z t:fielddefinition="High weight (corrects for age, gender, and region)" t:fieldname=HIWEIGHT m:datasetpart=1 m:fieldorder=3
```

## Meta Commands

```ls
metric m:datasetpart p:integer l:DatasetPart t:dataTypeName=number

metric m:fieldorder p:integer l:FieldOrder t:dataTypeName=number

entity e:yr5j-kyei l:"WA RCO SCORP 2013 Field Definitions" t:attribution="Washington State Recreation and Conservation Office (WA RCO)" t:url=https://data.wa.gov/api/views/yr5j-kyei

property e:yr5j-kyei t:meta.view v:id=yr5j-kyei v:category=Recreation v:attributionLink=http://www.rco.wa.gov v:averageRating=0 v:name="WA RCO SCORP 2013 Field Definitions" v:attribution="Washington State Recreation and Conservation Office (WA RCO)"

property e:yr5j-kyei t:meta.view.license v:name="Public Domain"

property e:yr5j-kyei t:meta.view.owner v:id=4qen-4xif v:screenName="Greg Tudor" v:displayName="Greg Tudor"

property e:yr5j-kyei t:meta.view.tableauthor v:id=4qen-4xif v:screenName="Greg Tudor" v:roleName=publisher v:displayName="Greg Tudor"
```

## Top Records

```ls
| datasetpart | fieldname | fielddefinition                                    | fieldorder | 
| =========== | ========= | ================================================== | ========== | 
| 1           | IDNUMBER  | Respondent's Tracking (ID) Number                  | 1          | 
| 1           | LOWEIGHT  | Low weight                                         | 2          | 
| 1           | HIWEIGHT  | High weight (corrects for age, gender, and region) | 3          | 
| 1           | R1        | Q13. Choose a random starting question             | 4          | 
| 1           | SEEPART   | Q14. What about sightseeing?                       | 5          | 
| 1           | NATACT    | Q15. What about...? Did you...?                    | 6          | 
| 1           | NATACT01  | Visiting a nature interpretive center              | 7          | 
| 1           | NATACT02  | Observing or photographing wildlife or nature      | 8          | 
| 1           | NATACT03  | Gathering or collecting things in a nature setting | 9          | 
| 1           | NATACT04  | Flower or vegetable gardening                      | 10         | 
```