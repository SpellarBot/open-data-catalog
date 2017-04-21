# Public Employment Relations Board Decisions: Beginning 1974

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/public-employment-relations-board-decisions-beginning-1974) |
| Metadata | [Link](https://data.ny.gov/api/views/vmn3-7znf) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/vmn3-7znf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/vmn3-7znf/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | vmn3-7znf |
| Name | Public Employment Relations Board Decisions: Beginning 1974 |
| Attribution | Public Employment Relations Board |
| Category | Government & Finance |
| Tags | taylor law, sera, perb |
| Created | 2015-08-18T11:35:55Z |
| Publication Date | 2016-12-07T15:57:02Z |

## Description

This dataset contains a list of decisions issued by the Public Employment Relations Board, by date on which they were issued, in the form of links to pdf documents.

## Columns

```ls
| Included | Schema Type | Field Name              | Name                    | Data Type     | Render Type   |
| ======== | =========== | ======================= | ======================= | ============= | ============= |
| Yes      | series tag  | title                   | Title                   | text          | text          |
| Yes      | time        | date                    | Date                    | calendar_date | calendar_date |
| Yes      | series tag  | link_to_board_decisions | Link to Board Decisions | url           | url           |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:vmn3-7znf d:2014-12-29T00:00:00.000Z t:title="State of New York Public Employment Relations Board Decisions from December 29, 2014" t:link_to_board_decisions="http://digitalcommons.ilr.cornell.edu/cgi/viewcontent.cgi?article=1658&context=perbdecisions" m:row_number.vmn3-7znf=1

series e:vmn3-7znf d:2014-10-06T00:00:00.000Z t:title="State of New York Public Employment Relations Board Decisions from October 6, 2014" t:link_to_board_decisions="http://digitalcommons.ilr.cornell.edu/cgi/viewcontent.cgi?article=1657&context=perbdecisions" m:row_number.vmn3-7znf=2

series e:vmn3-7znf d:2014-08-20T00:00:00.000Z t:title="State of New York Public Employment Relations Board Decisions from August 20, 2014" t:link_to_board_decisions="http://digitalcommons.ilr.cornell.edu/cgi/viewcontent.cgi?article=1656&context=perbdecisions" m:row_number.vmn3-7znf=3
```

## Meta Commands

```ls
metric m:row_number.vmn3-7znf p:long l:"Row Number"

entity e:vmn3-7znf l:"Public Employment Relations Board Decisions:  Beginning 1974" t:attribution="Public Employment Relations Board" t:url=https://data.ny.gov/api/views/vmn3-7znf

property e:vmn3-7znf t:meta.view v:id=vmn3-7znf v:category="Government & Finance" v:attributionLink=http://perb.ny.gov/perdcilr.asp v:averageRating=0 v:name="Public Employment Relations Board Decisions:  Beginning 1974" v:attribution="Public Employment Relations Board"

property e:vmn3-7znf t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:vmn3-7znf t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:vmn3-7znf t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| title                                                                                | date                | link_to_board_decisions                                                                              | 
| ==================================================================================== | =================== | ==================================================================================================== | 
| State of New York Public Employment Relations Board Decisions from December 29, 2014 | 2014-12-29T00:00:00 | [http://digitalcommons.ilr.cornell.edu/cgi/viewcontent.cgi?article=1658&context=perbdecisions, null] | 
| State of New York Public Employment Relations Board Decisions from October 6, 2014   | 2014-10-06T00:00:00 | [http://digitalcommons.ilr.cornell.edu/cgi/viewcontent.cgi?article=1657&context=perbdecisions, null] | 
| State of New York Public Employment Relations Board Decisions from August 20, 2014   | 2014-08-20T00:00:00 | [http://digitalcommons.ilr.cornell.edu/cgi/viewcontent.cgi?article=1656&context=perbdecisions, null] | 
| State of New York Public Employment Relations Board Decisions from June 20, 2014     | 2014-06-20T00:00:00 | [http://digitalcommons.ilr.cornell.edu/cgi/viewcontent.cgi?article=1655&context=perbdecisions, null] | 
| State of New York Public Employment Relations Board Decisions from May 27, 2014      | 2014-05-27T00:00:00 | [http://digitalcommons.ilr.cornell.edu/cgi/viewcontent.cgi?article=1654&context=perbdecisions, null] | 
| State of New York Public Employment Relations Board Decisions from April 3, 2014     | 2014-04-03T00:00:00 | [http://digitalcommons.ilr.cornell.edu/cgi/viewcontent.cgi?article=1653&context=perbdecisions, null] | 
| State of New York Public Employment Relations Board Decisions from February 28, 2014 | 2014-02-28T00:00:00 | [http://digitalcommons.ilr.cornell.edu/cgi/viewcontent.cgi?article=1652&context=perbdecisions, null] | 
| State of New York Public Employment Relations Board Decisions from November 13, 2013 | 2013-11-13T00:00:00 | [http://digitalcommons.ilr.cornell.edu/cgi/viewcontent.cgi?article=1651&context=perbdecisions, null] | 
| State of New York Public Employment Relations Board Decisions from October 15, 2013  | 2013-10-15T00:00:00 | [http://digitalcommons.ilr.cornell.edu/cgi/viewcontent.cgi?article=1650&context=perbdecisions, null] | 
| State of New York Public Employment Relations Board Decisions from August 23, 2013   | 2013-08-23T00:00:00 | [http://digitalcommons.ilr.cornell.edu/cgi/viewcontent.cgi?article=1649&context=perbdecisions, null] | 
```