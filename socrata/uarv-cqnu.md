# 2013-2014 PHAP Associates by State

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2013-2014-phap-associates-by-state) |
| Metadata | [Link](https://data.cdc.gov/api/views/uarv-cqnu) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/uarv-cqnu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/uarv-cqnu/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | uarv-cqnu |
| Name | 2013-2014 PHAP Associates by State |
| Attribution | Office for State, Tribal, Local and Territorial Support, Public Health Associate Program |
| Tags | phap, associate, location, program, host site |
| Created | 2015-03-17T15:31:51Z |
| Publication Date | 2015-03-17T16:28:47Z |

## Description

The map illustrates the total number of 2013 and 2014 PHAP associates in each state and U.S. territory.

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type | Render Type |
| ======== | ============== | =================== | =================== | ========= | =========== |
| Yes      | numeric metric | phap_class          | PHAP Class          | number    | number      |
| Yes      | series tag     | name                | Name                | text      | text        |
| Yes      | series tag     | host_site_year_1    | Host Site Year 1    | text      | text        |
| Yes      | series tag     | host_site_year_2    | Host Site Year 2    | text      | text        |
| Yes      | series tag     | year_1_program_area | Year 1 Program Area | text      | text        |
| Yes      | series tag     | year_2_program_area | Year 2 Program Area | text      | text        |
| Yes      | series tag     | year_1_city         | Year 1 City         | text      | text        |
| Yes      | series tag     | year_2_city         | Year 2 City         | text      | text        |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Data Commands

```ls
series e:uarv-cqnu d:2013-01-01T00:00:00.000Z t:year_2_city="White Plains" t:year_1_program_area="Other Communicable Diseases" t:year_2_program_area="Chronic Disease" t:name="Malekmadani, Arienne" t:host_site_year_2="Westchester County Hlth Dept" m:phap_class=2013

series e:uarv-cqnu d:2013-01-01T00:00:00.000Z t:year_1_program_area=Tuberculosis t:year_2_program_area=Tuberculosis t:name="Ford, Jamir" t:host_site_year_1="Chicago Dept of Public Health" t:year_1_city=Chicago m:phap_class=2014

series e:uarv-cqnu d:2013-01-01T00:00:00.000Z t:year_2_city=Marysville t:year_1_program_area="Environmental Health" t:year_2_program_area="Public Health Preparedness" t:name="Schill, Elizabeth Hope" t:host_site_year_2="Union County Health District" m:phap_class=2013
```

## Meta Commands

```ls
metric m:phap_class p:integer l:"PHAP Class" t:dataTypeName=number

entity e:uarv-cqnu l:"2013-2014 PHAP Associates by State" t:attribution="Office for State, Tribal, Local and Territorial Support, Public Health Associate Program" t:url=https://data.cdc.gov/api/views/uarv-cqnu

property e:uarv-cqnu t:meta.view v:id=uarv-cqnu v:attributionLink=http://www.cdc.gov/phap v:averageRating=0 v:name="2013-2014 PHAP Associates by State" v:attribution="Office for State, Tribal, Local and Territorial Support, Public Health Associate Program"

property e:uarv-cqnu t:meta.view.owner v:id=reui-f89e v:screenName="Kerry O" v:displayName="Kerry O"

property e:uarv-cqnu t:meta.view.tableauthor v:id=reui-f89e v:screenName="Kerry O" v:roleName=publisher v:displayName="Kerry O"

property e:uarv-cqnu t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:00 v:Program_Code=009:020
```

## Top Records

```ls
| phap_class | name                   | host_site_year_1                                  | host_site_year_2                | year_1_program_area                                        | year_2_program_area                                     | year_1_city      | year_2_city  | 
| ========== | ====================== | ================================================= | =============================== | ========================================================== | ======================================================= | ================ | ============ | 
| 2013       | Malekmadani, Arienne   |                                                   | Westchester County Hlth Dept    | Other Communicable Diseases                                | Chronic Disease                                         |                  | White Plains | 
| 2014       | Ford, Jamir            | Chicago Dept of Public Health                     |                                 | Tuberculosis                                               | Tuberculosis                                            | Chicago          |              | 
| 2013       | Schill, Elizabeth Hope |                                                   | Union County Health District    | Environmental Health                                       | Public Health Preparedness                              |                  | Marysville   | 
| 2013       | Georges, Tracy         |                                                   | City of New Orleans Health Dept | Maternal/Child Health                                      | Public Health Preparedness                              |                  | New Orleans  | 
| 2014       | Hutsona, Rajay         | Richmond City Health District                     |                                 | Chronic Disease                                            | Communicable Diseases Not Sexually Transmitted Diseases | Richmond         |              | 
| 2014       | Frost, Yvette          | The Florida Dept of Health: Miami-Dade County     |                                 | Sexually Transmitted Diseases/Human Immunodeficiency Virus | Tuberculosis                                            | Miami            |              | 
| 2014       | Walton, Mariah         | Kern County Public Health Services Dept           |                                 | Access To Care                                             | Chronic Disease                                         | Bakersfield      |              | 
| 2014       | Woldeamanuale, Negest  | Johnson County Public Health                      |                                 | Chronic Disease                                            | Chronic Disease                                         | Iowa City        |              | 
| 2014       | Brockington, Regina    | Baltimore City Health Dept                        |                                 | Sexually Transmitted Diseases/Human Immunodeficiency Virus | Human Immunodeficiency Virus                            | Baltimore        |              | 
| 2014       | Jefferson, Briana      | The New York City Dept of Health & Mental Hygiene |                                 | Preparedness                                               | Preparedness                                            | Long Island City |              | 
```