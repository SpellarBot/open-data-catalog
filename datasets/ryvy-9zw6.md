# BNIA Vital Signs Codebook

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/bnia-vital-signs-codebook-e42f6) |
| Metadata | [Link](https://data.baltimorecity.gov/api/views/ryvy-9zw6) |
| Data: JSON | [100 Rows](https://data.baltimorecity.gov/api/views/ryvy-9zw6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.baltimorecity.gov/api/views/ryvy-9zw6/rows.csv?max_rows=100) |
| Host | data.baltimorecity.gov |
| Id | ryvy-9zw6 |
| Name | BNIA Vital Signs Codebook |
| Attribution | BNIA-JFI |
| Category | Neighborhoods |
| Tags | vital signs, census, indicators, neighborhoods |
| Created | 2013-08-14T15:14:21Z |
| Publication Date | 2014-04-04T00:24:27Z |

## Description

Lists the short variable names and their corresponding full names, along with their sources. - See more at: http://bniajfi.org/data_downloads

## Columns

```ls
| Included | Schema Type | Field Name           | Name                 | Data Type | Render Type |
| ======== | =========== | ==================== | ==================== | ========= | =========== |
| Yes      | series tag  | section              | Section              | text      | text        |
| Yes      | series tag  | variable_name        | Variable Name        | text      | text        |
| Yes      | series tag  | indicator            | Indicator            | text      | text        |
| Yes      | series tag  | full_source          | Full Source          | text      | text        |
| Yes      | time        | years_available      | Years Available      | text      | text        |
| Yes      | series tag  | normalization_source | Normalization Source | text      | text        |
```

## Time Field

```ls
Value = years_available
Format & Zone = yyyy
```

## Data Commands

```ls
series e:ryvy-9zw6 d:2010-01-01T00:00:00.000Z t:indicator="Total Population" t:variable_name=tpopXX t:full_source="U.S. Bureau of the Census" t:section=Socioeconomic/Demographics m:row_number.ryvy-9zw6=1

series e:ryvy-9zw6 d:2010-01-01T00:00:00.000Z t:indicator="Total Male Population" t:variable_name=maleXX t:full_source="U.S. Bureau of the Census" t:section=Socioeconomic/Demographics m:row_number.ryvy-9zw6=2

series e:ryvy-9zw6 d:2010-01-01T00:00:00.000Z t:indicator="Total Female Population" t:variable_name=femaleXX t:full_source="U.S. Bureau of the Census" t:section=Socioeconomic/Demographics m:row_number.ryvy-9zw6=3
```

## Meta Commands

```ls
metric m:row_number.ryvy-9zw6 p:long l:"Row Number"

entity e:ryvy-9zw6 l:"BNIA Vital Signs Codebook" t:attribution=BNIA-JFI t:url=https://data.baltimorecity.gov/api/views/ryvy-9zw6

property e:ryvy-9zw6 t:meta.view v:id=ryvy-9zw6 v:category=Neighborhoods v:attributionLink=http://bniajfi.org v:averageRating=0 v:name="BNIA Vital Signs Codebook" v:attribution=BNIA-JFI

property e:ryvy-9zw6 t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:ryvy-9zw6 t:meta.view.owner v:id=6r9a-dfdj v:screenName="Open Baltimore" v:displayName="Open Baltimore"

property e:ryvy-9zw6 t:meta.view.tableauthor v:id=6r9a-dfdj v:screenName="Open Baltimore" v:roleName=administrator v:displayName="Open Baltimore"
```

## Top Records

```ls
| section                    | variable_name | indicator                                                                                                               | full_source               | years_available | normalization_source | 
| ========================== | ============= | ======================================================================================================================= | ========================= | =============== | ==================== | 
| Socioeconomic/Demographics | tpopXX        | Total Population                                                                                                        | U.S. Bureau of the Census | 2010            |                      | 
| Socioeconomic/Demographics | maleXX        | Total Male Population                                                                                                   | U.S. Bureau of the Census | 2010            |                      | 
| Socioeconomic/Demographics | femaleXX      | Total Female Population                                                                                                 | U.S. Bureau of the Census | 2010            |                      | 
| Socioeconomic/Demographics | paaXX         | Percent of Residents - Black/African-American (Non-Hispanic)                                                            | U.S. Bureau of the Census | 2010            |                      | 
| Socioeconomic/Demographics | pwhiteXX      | Percent of Residents - White/Caucasian (Noon-Hispanic)                                                                  | U.S. Bureau of the Census | 2010            |                      | 
| Socioeconomic/Demographics | pasiXX        | Percent of Residents - Asian (Non-Hispanic)                                                                             | U.S. Bureau of the Census | 2010            |                      | 
| Socioeconomic/Demographics | p2moreXX      | Percent of Residents - Two or More Races (Non-Hispanic)                                                                 | U.S. Bureau of the Census | 2010            |                      | 
| Socioeconomic/Demographics | ppacXX        | Percent of Residents - All Other Races (Hawaiian/ Pacific Islander, Alaskan/ Native American Other Race) (Non-Hispanic) | U.S. Bureau of the Census | 2010            |                      | 
| Socioeconomic/Demographics | phispXX       | Percent of Residents - Hispanic                                                                                         | U.S. Bureau of the Census | 2010            |                      | 
| Socioeconomic/Demographics | racdivXX      | Racial Diversity Index                                                                                                  | U.S. Bureau of the Census | 2010            |                      | 
```