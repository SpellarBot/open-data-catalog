# Impaired Driving Death Rate, by Age and Gender, 2012 & 2014, Region 4 - Atlanta

## Dataset

* [Dataset URL](https://data.cdc.gov/api/views/28km-nz6e/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/impaired-driving-death-rate-by-age-and-gender-2012-region-4-atlanta)
* [Metadata URL](https://data.cdc.gov/api/views/28km-nz6e)
* Id = 28km-nz6e
* Name = Impaired Driving Death Rate, by Age and Gender, 2012 & 2014, Region 4 - Atlanta
* Attribution = CDC National Center for Injury Prevention and Control, Division of Unintentional Injury Prevention
* [Attribution Link](http://www.cdc.gov/motorvehiclesafety/)
* Category = Motor Vehicle
* Tags = [centers for disease control and prevention, cdc]
* Created = 2014-12-17T15:46:24Z
* Publication Date = 2016-09-14T15:18:14Z
* Rows Updated = 2016-09-14T15:16:48Z

## Description

Rate of deaths by age/gender (per 100,000 population) for people killed in crashes involving a driver with BAC =>0.08%, 2012, 2014. 2012 Source: Fatality Analysis Reporting System (FARS). 2014 Source: National Highway Traffic Administration's (NHTSA) Fatality Analysis Reporting System (FARS), 2014 Annual Report File. Note: Blank cells indicate data are suppressed. Fatality rates based on fewer than 20 deaths are suppressed.

## Columns

```ls
| Name             | Field Name      | Data Type | Render Type | Schema Type    | Included | 
| ================ | =============== | ========= | =========== | ============== | ======== | 
| updated_at       | :updated_at     | meta_data | meta_data   | time           | No       | 
| State            | state           | text      | text        | series tag     | Yes      | 
| All Ages, 2012   | all_ages        | number    | number      | numeric metric | Yes      | 
| Ages 0-20, 2012  | ages_0_20       | number    | number      | numeric metric | Yes      | 
| Ages 21-34, 2012 | ages_21_34      | number    | number      | numeric metric | Yes      | 
| Ages 35+, 2012   | ages_35         | number    | number      | numeric metric | Yes      | 
| Male, 2012       | male            | number    | number      | numeric metric | Yes      | 
| Female, 2012     | female          | number    | number      | numeric metric | Yes      | 
| All Ages, 2014   | all_ages_2014   | number    | number      | numeric metric | Yes      | 
| Ages 0-20, 2014  | ages_0_20_2014  | number    | number      | numeric metric | Yes      | 
| Ages 21-34, 2014 | ages_21_34_2014 | number    | number      | numeric metric | Yes      | 
| Ages 35+, 2014   | ages_35_2014    | number    | number      | numeric metric | Yes      | 
| Male, 2014       | male_2014       | number    | number      | numeric metric | Yes      | 
| Female, 2014     | female_2014     | number    | number      | numeric metric | Yes      | 
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
series e:28km-nz6e d:2016-09-14T15:16:34.000Z t:state="United States" m:ages_21_34_2014=6.2 m:ages_0_20_2014=1.2 m:male_2014=4.9 m:female_2014=1.4 m:female=1.5 m:ages_21_34=6.7 m:male=5.2 m:ages_0_20=1.3 m:ages_35=3.1 m:all_ages_2014=3.1 m:all_ages=3.3 m:ages_35_2014=3

series e:28km-nz6e d:2016-09-14T15:16:37.000Z t:state=Alabama m:ages_21_34_2014=10 m:ages_0_20_2014=2.1 m:male_2014=8.6 m:female_2014=2.6 m:female=2.9 m:ages_21_34=10.3 m:male=8.4 m:ages_0_20=2.7 m:ages_35=5 m:all_ages_2014=5.5 m:all_ages=5.5 m:ages_35_2014=5.5

series e:28km-nz6e d:2016-09-14T15:16:38.000Z t:state=Florida m:ages_21_34_2014=7.4 m:ages_0_20_2014=1.2 m:male_2014=5.4 m:female_2014=1.7 m:female=1.7 m:ages_21_34=8 m:male=5.7 m:ages_0_20=1.2 m:ages_35=3.3 m:all_ages_2014=3.5 m:all_ages=3.7 m:ages_35_2014=3.1
```

## Meta Commands

```ls
metric m:all_ages l:"All Ages, 2012" t:dataTypeName=number

metric m:ages_0_20 l:"Ages 0-20, 2012" t:dataTypeName=number

metric m:ages_21_34 l:"Ages 21-34, 2012" t:dataTypeName=number

metric m:ages_35 l:"Ages 35+, 2012" t:dataTypeName=number

metric m:male l:"Male, 2012" t:dataTypeName=number

metric m:female l:"Female, 2012" t:dataTypeName=number

metric m:all_ages_2014 l:"All Ages, 2014" t:dataTypeName=number

metric m:ages_0_20_2014 l:"Ages 0-20, 2014" t:dataTypeName=number

metric m:ages_21_34_2014 l:"Ages 21-34, 2014" t:dataTypeName=number

metric m:ages_35_2014 l:"Ages 35+, 2014" t:dataTypeName=number

metric m:male_2014 l:"Male, 2014" t:dataTypeName=number

metric m:female_2014 l:"Female, 2014" t:dataTypeName=number

entity e:28km-nz6e l:"Impaired Driving Death Rate, by Age and Gender, 2012 & 2014, Region 4 - Atlanta" t:attribution="CDC National Center for Injury Prevention and Control, Division of Unintentional Injury Prevention" t:url=https://data.cdc.gov/api/views/28km-nz6e

property e:28km-nz6e t:meta.view d:2017-03-07T18:56:02.701Z v:id=28km-nz6e v:category="Motor Vehicle" v:attributionLink=http://www.cdc.gov/motorvehiclesafety/ v:averageRating=0 v:name="Impaired Driving Death Rate, by Age and Gender, 2012 & 2014, Region 4 - Atlanta" v:attribution="CDC National Center for Injury Prevention and Control, Division of Unintentional Injury Prevention"

property e:28km-nz6e t:meta.view.license d:2017-03-07T18:56:02.701Z v:name="Public Domain"

property e:28km-nz6e t:meta.view.owner d:2017-03-07T18:56:02.701Z v:id=cg4e-25jx v:screenName=iqw7@cdc.gov v:roleName=publisher v:displayName=iqw7@cdc.gov

property e:28km-nz6e t:meta.view.tableauthor d:2017-03-07T18:56:02.701Z v:id=cg4e-25jx v:screenName=iqw7@cdc.gov v:roleName=publisher v:displayName=iqw7@cdc.gov

property e:28km-nz6e t:meta.view.metadata.custom_fields.common_core d:2017-03-07T18:56:02.701Z v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:00 v:Program_Code=009:020
```