# Vital Signs Codebook And Sources (2010 - 2012)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/vital-signs-codebook-and-sources-2010-2012-3bb81) |
| Metadata | [Link](https://data.baltimorecity.gov/api/views/uuev-6p46) |
| Data: JSON | [100 Rows](https://data.baltimorecity.gov/api/views/uuev-6p46/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.baltimorecity.gov/api/views/uuev-6p46/rows.csv?max_rows=100) |
| Host | data.baltimorecity.gov |
| Id | uuev-6p46 |
| Name | Vital Signs Codebook And Sources (2010 - 2012) |
| Attribution | The Baltimore Neighborhood Indicators Alliance-Jacob France Institute at the University of Baltimore (known as BNIA-JFI) |
| Category | Neighborhoods |
| Tags | vital signs, code book, bnia |
| Created | 2014-05-20T17:42:33Z |
| Publication Date | 2014-05-20T17:44:52Z |

## Description

For indicator definitions and calculation notes,  visit http://www.bniajfi.org. Citing Vital Signs in Reports and Publications: For citing BNIA-JFI, specifically the Vital Signs reports, we recommend using American Psychological Association (APA) guidelines. An example of the format, as applied to Vital Signs is below:Baltimore Neighborhood Indicators Alliance - Jacob France Institute. (2013). Vital Signs 11 [data file]. Retrieved from www.bniajfi.org/indicators For your parenthetical, in-text citation, use the following format: (Baltimore Neighborhood Indicators Alliance - Jacob France Institute, 2013). Crediting BNIA-JFI for Maps/Tables/Graphs/Other Content: For more informal use of our data, in maps, data tables, graphs, and presentations, we recommend that data users cite the original source (Baltimore City Police Department, American Community Survey, Baltimore City Public School System, etc.) and credit BNIA-JFI with analysis. Below is an example: Source: Baltimore City Public School System, Analysis: Baltimore Neighborhood Indicators Alliance - Jacob France Institute (2013)

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
series e:uuev-6p46 d:2010-01-01T00:00:00.000Z t:indicator="Total Population" t:variable_name=tpopXX t:full_source="U.S. Bureau of the Census" t:section="Census Demographics" m:row_number.uuev-6p46=1

series e:uuev-6p46 d:2010-01-01T00:00:00.000Z t:indicator="Total Male Population" t:variable_name=maleXX t:full_source="U.S. Bureau of the Census" t:section="Census Demographics" m:row_number.uuev-6p46=2

series e:uuev-6p46 d:2010-01-01T00:00:00.000Z t:indicator="Total Female Population" t:variable_name=femaleXX t:full_source="U.S. Bureau of the Census" t:section="Census Demographics" m:row_number.uuev-6p46=3
```

## Meta Commands

```ls
metric m:row_number.uuev-6p46 p:long l:"Row Number"

entity e:uuev-6p46 l:"Vital Signs Codebook And Sources (2010 - 2012)" t:attribution="The Baltimore Neighborhood Indicators Alliance-Jacob France Institute at the University of Baltimore (known as BNIA-JFI)" t:url=https://data.baltimorecity.gov/api/views/uuev-6p46

property e:uuev-6p46 t:meta.view v:id=uuev-6p46 v:category=Neighborhoods v:attributionLink=http://bniajfi.org v:averageRating=0 v:name="Vital Signs Codebook And Sources (2010 - 2012)" v:attribution="The Baltimore Neighborhood Indicators Alliance-Jacob France Institute at the University of Baltimore (known as BNIA-JFI)"

property e:uuev-6p46 t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:uuev-6p46 t:meta.view.owner v:id=6r9a-dfdj v:screenName="Open Baltimore" v:displayName="Open Baltimore"

property e:uuev-6p46 t:meta.view.tableauthor v:id=6r9a-dfdj v:screenName="Open Baltimore" v:roleName=administrator v:displayName="Open Baltimore"
```

## Top Records

```ls
| section             | variable_name | indicator                                                                                                               | full_source               | years_available | normalization_source | 
| =================== | ============= | ======================================================================================================================= | ========================= | =============== | ==================== | 
| Census Demographics | tpopXX        | Total Population                                                                                                        | U.S. Bureau of the Census | 2010            |                      | 
| Census Demographics | maleXX        | Total Male Population                                                                                                   | U.S. Bureau of the Census | 2010            |                      | 
| Census Demographics | femaleXX      | Total Female Population                                                                                                 | U.S. Bureau of the Census | 2010            |                      | 
| Census Demographics | paaXX         | Percent of Residents - Black/African-American (Non-Hispanic)                                                            | U.S. Bureau of the Census | 2010            |                      | 
| Census Demographics | pwhiteXX      | Percent of Residents - White/Caucasian (Noon-Hispanic)                                                                  | U.S. Bureau of the Census | 2010            |                      | 
| Census Demographics | pasiXX        | Percent of Residents - Asian (Non-Hispanic)                                                                             | U.S. Bureau of the Census | 2010            |                      | 
| Census Demographics | p2moreXX      | Percent of Residents - Two or More Races (Non-Hispanic)                                                                 | U.S. Bureau of the Census | 2010            |                      | 
| Census Demographics | ppacXX        | Percent of Residents - All Other Races (Hawaiian/ Pacific Islander, Alaskan/ Native American Other Race) (Non-Hispanic) | U.S. Bureau of the Census | 2010            |                      | 
| Census Demographics | phispXX       | Percent of Residents - Hispanic                                                                                         | U.S. Bureau of the Census | 2010            |                      | 
| Census Demographics | racdivXX      | Racial Diversity Index                                                                                                  | U.S. Bureau of the Census | 2010            |                      | 
```