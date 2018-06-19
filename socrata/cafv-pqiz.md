# Publications from Roswell Park Cancer Institute: Beginning 2006

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/publications-from-roswell-park-cancer-institute-beginning-2006) |
| Metadata | [Link](https://data.ny.gov/api/views/cafv-pqiz) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/cafv-pqiz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/cafv-pqiz/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | cafv-pqiz |
| Name | Publications from Roswell Park Cancer Institute: Beginning 2006 |
| Attribution | Roswell Park Cancer Institute (RPCI) |
| Category | Health |
| Tags | medical publications |
| Created | 2015-02-23T15:26:12Z |
| Publication Date | 2015-06-16T14:06:14Z |

## Description

List of existing publications from Roswell Park Cancer Institute authors, including:  year published; publication type and title; journal name, volume, issue and page range; author list; ISSN; and peer reviewed information

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                 | Data Type | Render Type |
| ======== | ============== | ==================== | ==================== | ========= | =========== |
| Yes      | time           | year_published       | Year Published       | number    | text        |
| Yes      | series tag     | publication_type     | Publication Type     | text      | text        |
| Yes      | series tag     | journal_name         | Journal Name         | text      | text        |
| Yes      | series tag     | publication_title    | Publication Title    | text      | text        |
| Yes      | series tag     | author_list          | Author List          | text      | text        |
| Yes      | numeric metric | journal_volume       | Journal Volume       | number    | number      |
| Yes      | series tag     | journal_issue_number | Journal Issue Number | text      | text        |
| Yes      | series tag     | journal_page_range   | Journal Page Range   | text      | text        |
| Yes      | series tag     | issn                 | ISSN                 | text      | text        |
| Yes      | series tag     | peer_reviewed        | Peer Reviewed        | text      | text        |
| Yes      | numeric metric | impact_factor        | Impact Factor        | number    | number      |
```

## Time Field

```ls
Value = year_published
Format & Zone = yyyy
```

## Data Commands

```ls
series e:cafv-pqiz d:2006-01-01T00:00:00.000Z t:publication_type=Correspondence t:author_list="Chanan-Khan, Asher A" t:issn=0006-4971 t:journal_page_range=850 t:journal_issue_number=3 t:publication_title="Ditching the chaperone!" t:peer_reviewed=TRUE t:journal_name=Blood m:journal_volume=107 m:impact_factor=10.131

series e:cafv-pqiz d:2008-01-01T00:00:00.000Z t:publication_type=Article t:author_list="Hutson, Alan" t:issn=1572-3127 t:journal_page_range=46-55 t:journal_issue_number=1 t:publication_title="Estimating relative rank correlation: Theory and application" t:peer_reviewed=TRUE t:journal_name="Statistical Methodology" m:journal_volume=5

series e:cafv-pqiz d:2011-01-01T00:00:00.000Z t:publication_type="Book Chapter" t:author_list="Matta, Khushi L" t:issn=1550-7416 t:journal_page_range=123-140 t:publication_title="Gastric carcinoma : molecular aspects and current advances" t:peer_reviewed=TRUE t:journal_name="AAPS journal" m:impact_factor=1.874
```

## Meta Commands

```ls
metric m:journal_volume p:integer l:"Journal Volume" d:"Issue number of the journal in which the publication appears. Journal issues are subparts of each journal volume. Blank means this field does not apply for this publication." t:dataTypeName=number

metric m:impact_factor p:float l:"Impact Factor" d:"Indicates the Impact Factor (IF) for the publication. Blank means the IF is either unknown or the publication has not been rated. An IF is a systematic, objective means to critically evaluate and rank the world's leading journals, with quantifiable, statistical information based on citation data. Generally, the higher the IF, the greater the impact of the specific journal?s reputation. Impact factors do not appear until 3 years after the publication of the article due to the way they are calculated." t:dataTypeName=number

entity e:cafv-pqiz l:"Publications from Roswell Park Cancer Institute:  Beginning 2006" t:attribution="Roswell Park Cancer Institute (RPCI)" t:url=https://data.ny.gov/api/views/cafv-pqiz

property e:cafv-pqiz t:meta.view v:id=cafv-pqiz v:category=Health v:attributionLink=https://www.roswellpark.edu/ v:averageRating=0 v:name="Publications from Roswell Park Cancer Institute:  Beginning 2006" v:attribution="Roswell Park Cancer Institute (RPCI)"

property e:cafv-pqiz t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:cafv-pqiz t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:cafv-pqiz t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| year_published | publication_type  | journal_name              | publication_title                                            | author_list                          | journal_volume | journal_issue_number | journal_page_range | issn      | peer_reviewed | impact_factor | 
| ============== | ================= | ========================= | ============================================================ | ==================================== | ============== | ==================== | ================== | ========= | ============= | ============= | 
| 2006           | Correspondence    | Blood                     | Ditching the chaperone!                                      | Chanan-Khan, Asher A                 | 107            | 3                    | 850                | 0006-4971 | TRUE          | 10.131        | 
| 2008           | Article           | Statistical Methodology   | Estimating relative rank correlation: Theory and application | Hutson, Alan                         | 5              | 1                    | 46-55              | 1572-3127 | TRUE          |               | 
| 2011           | Book Chapter      | AAPS journal              | Gastric carcinoma : molecular aspects and current advances   | Matta, Khushi L                      |                |                      | 123-140            | 1550-7416 | TRUE          | 1.874         | 
| 2011           | Book Chapter      | Contemporary oncology     | Vitamin D and cancer                                         | Ma, Yingyu, Johnson, Candace S       |                |                      | 99-114             |           | FALSE         |               | 
| 2009           | Proceedings Paper | Expert review of vaccines | All things mucosal                                           | Thanavala, Yasmin; Lavelle E; Ogra P | 8              | 2                    | 139-142            | 1476-0584 | TRUE          | 2.979         | 
| 2009           | Review            | Leukemia                  | The role of microRNA in human leukemia: a review             | Yendamuri, Sai S; Calin GA           | 23             | 7                    | 1257-1263          | 1476-5551 | TRUE          | 6.924         | 
| 2011           | Book Chapter      | Contemporary oncology     | Vitamin D and cancer                                         | Mazzilli, Sarah A, Reid, Mary E      |                |                      | 175-189            |           | FALSE         |               | 
| 2010           | Correspondence    | Genes and cancer          | Introduction: hanafusa memorial issue                        | Gelman, Irwin H; Sudol M             | 1              | 11                   | 1088               | 1947-6019 | TRUE          |               | 
| 2010           | Correspondence    | Oncotarget                | Tumor-associated oncogenes go on (phage) display             | Kandel, Eugene S                     | 1              | 2                    | 84-85              | 1949-2553 | TRUE          |               | 
| 2011           | Book Chapter      | Contemporary oncology     | Vitamin D and cancer                                         | Trump, Donald L; Johnson, Candace S  |                |                      | 25-52              |           | FALSE         |               | 
```