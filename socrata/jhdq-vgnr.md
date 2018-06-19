# US Patents Issued to Health Research Inc on Behalf of Roswell Park Cancer Institute

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/us-patents-issued-to-health-research-inc-on-behalf-of-roswell-park-cancer-institute) |
| Metadata | [Link](https://data.ny.gov/api/views/jhdq-vgnr) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/jhdq-vgnr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/jhdq-vgnr/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | jhdq-vgnr |
| Name | US Patents Issued to Health Research Inc on Behalf of Roswell Park Cancer Institute |
| Attribution | Roswell Park Cancer Institute |
| Category | Health |
| Tags | medical patents, rpci, hri |
| Created | 2015-01-29T17:19:26Z |
| Publication Date | 2015-04-22T13:31:49Z |

## Description

This dataset is a list of active patents issued to Health Research, Inc. on behalf of Roswell Park Cancer Institute (RPCI).  It includes the patent number and date of issuance as well as the patent title.

## Columns

```ls
| Included | Schema Type | Field Name            | Name                  | Data Type     | Render Type   |
| ======== | =========== | ===================== | ===================== | ============= | ============= |
| Yes      | series tag  | patent_number         | Patent Number         | text          | html          |
| Yes      | series tag  | status                | Status                | text          | text          |
| Yes      | time        | issue_date            | Issue Date            | calendar_date | calendar_date |
| Yes      | series tag  | country               | Country               | text          | text          |
| Yes      | series tag  | patent_title          | Patent Title          | text          | text          |
| Yes      | series tag  | patent_assignee_owner | Patent Assignee/Owner | text          | text          |
```

## Time Field

```ls
Value = issue_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:jhdq-vgnr d:1998-03-03T00:00:00.000Z t:patent_assignee_owner="Health Research, Inc. for Roswell Park Cancer Institute" t:patent_number=5723719 t:status=Issued t:patent_title="Transgenic Mouse as Model for Diseases Involving Dopaminergic Dysfunction" t:country="United States" m:row_number.jhdq-vgnr=1

series e:jhdq-vgnr d:1997-09-16T00:00:00.000Z t:patent_assignee_owner="Health Research, Inc. for Roswell Park Cancer Institute" t:patent_number=5668253 t:status=Issued t:patent_title="Peptide Having Antigenic Properties Similar to a Determinant of Hepatitis B Surface Antigen" t:country="United States" m:row_number.jhdq-vgnr=2

series e:jhdq-vgnr d:1999-01-05T00:00:00.000Z t:patent_assignee_owner="Health Research, Inc. for Roswell Park Cancer Institute" t:patent_number=5856087 t:status=Issued t:patent_title="Method for Detecting Immune Response to Hepatitis B" t:country="United States" m:row_number.jhdq-vgnr=3
```

## Meta Commands

```ls
metric m:row_number.jhdq-vgnr p:long l:"Row Number"

entity e:jhdq-vgnr l:"US Patents Issued to Health Research Inc on Behalf of Roswell Park Cancer Institute" t:attribution="Roswell Park Cancer Institute" t:url=https://data.ny.gov/api/views/jhdq-vgnr

property e:jhdq-vgnr t:meta.view v:id=jhdq-vgnr v:category=Health v:attributionLink=https://www.roswellpark.edu/ v:averageRating=0 v:name="US Patents Issued to Health Research Inc on Behalf of Roswell Park Cancer Institute" v:attribution="Roswell Park Cancer Institute"

property e:jhdq-vgnr t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:jhdq-vgnr t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:jhdq-vgnr t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| patent_number | status | issue_date          | country       | patent_title                                                                                | patent_assignee_owner                                   | 
| ============= | ====== | =================== | ============= | =========================================================================================== | ======================================================= | 
| 5723719       | Issued | 1998-03-03T00:00:00 | United States | Transgenic Mouse as Model for Diseases Involving Dopaminergic Dysfunction                   | Health Research, Inc. for Roswell Park Cancer Institute | 
| 5668253       | Issued | 1997-09-16T00:00:00 | United States | Peptide Having Antigenic Properties Similar to a Determinant of Hepatitis B Surface Antigen | Health Research, Inc. for Roswell Park Cancer Institute | 
| 5856087       | Issued | 1999-01-05T00:00:00 | United States | Method for Detecting Immune Response to Hepatitis B                                         | Health Research, Inc. for Roswell Park Cancer Institute | 
| 5928641       | Issued | 1999-07-27T00:00:00 | United States | Anti-Endoglin Monoclonal Antibodies and Their Use in Antiangiogenic Therapy                 | Health Research, Inc. for Roswell Park Cancer Institute | 
| 6200566       | Issued | 2001-03-13T00:00:00 | United States | Anti-Endoglin Monoclonal Antibodies and Their Use in Antiangiogenic Therapy                 | Health Research, Inc. for Roswell Park Cancer Institute | 
| 6190660       | Issued | 2001-02-20T00:00:00 | United States | Anti-Endoglin Monoclonal Antibodies and Their Use in Antiangiogenic Therapy                 | Health Research, Inc. for Roswell Park Cancer Institute | 
| 7097836       | Issued | 2006-08-29T00:00:00 | United States | Method for Increasing the Efficacy of Anti-Tumor Agents by Anti-Endoglin Antibody           | Health Research, Inc. for Roswell Park Cancer Institute | 
| 7691374       | Issued | 2010-04-06T00:00:00 | United States | Method for Increasing the Efficacy of Anti-Tumor Agents by Anti-Endoglin Antibody           | Health Research, Inc. for Roswell Park Cancer Institute | 
| 7527810       | Issued | 2009-05-05T00:00:00 | United States | Oral Immunology Using Plant Product Containing Hepatitis Surface Antigen                    | Health Research, Inc. for Roswell Park Cancer Institute | 
| 7572466       | Issued | 2009-08-11T00:00:00 | United States | Oral Immunology Using Plant Product Containing A Non-Enteric Pathogen Antigen               | Health Research, Inc. for Roswell Park Cancer Institute | 
```