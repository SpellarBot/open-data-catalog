# Fertilizer publications, forms, tonnage reports and lab analysis

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/fertilizer-publications-forms-tonnage-reports-and-lab-analysis-08990) |
| Metadata | [Link](https://data.oregon.gov/api/views/4it8-vhzu) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/4it8-vhzu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/4it8-vhzu/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | 4it8-vhzu |
| Name | Fertilizer publications, forms, tonnage reports and lab analysis |
| Category | Natural Resources |
| Tags | fertilizer, crop nutrients |
| Created | 2014-03-19T17:02:15Z |
| Publication Date | 2016-12-19T16:31:51Z |

## Columns

```ls
| Included | Schema Type | Field Name    | Name       | Data Type | Render Type |
| ======== | =========== | ============= | ========== | ========= | =========== |
| No       | time        | :updated_at   | updated_at | meta_data | meta_data   |
| Yes      | series tag  | publication   | Subject    | text      | text        |
| Yes      | series tag  | information_x | Link       | document  | document    |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:4it8-vhzu d:2014-03-19T11:53:48.000Z t:information_x.file_id=eRj33R6c4Lunj1zuw5tPFZF-nKjM6QPc7iezk9qU9L0 t:information_x.content_type="application/pdf; charset=binary" t:information_x.filename="Fertilizer metal level rule development.pdf" t:information_x.size=14073 t:publication="Heavy metals" m:row_number.4it8-vhzu=1

series e:4it8-vhzu d:2014-03-19T11:54:05.000Z t:information_x.file_id=NryrrBVoOHaVFKbUjxiLGnsSR5XFUcKRjNJVuKHQ-lM t:information_x.content_type="application/pdf; charset=binary" t:information_x.filename="Heavy metals in fertilizers.pdf" t:information_x.size=176309 t:publication="Heavy metals" m:row_number.4it8-vhzu=2

series e:4it8-vhzu d:2014-03-19T11:54:25.000Z t:information_x.file_id=Kog-Vc5n5mzOJyIX8_hgapS0AFqKukvo9C45N1AxgZE t:information_x.content_type="application/pdf; charset=binary" t:information_x.filename="Review of heavy metals limits.pdf" t:information_x.size=51185 t:publication="Heavy metals" m:row_number.4it8-vhzu=3
```

## Meta Commands

```ls
metric m:row_number.4it8-vhzu p:long l:"Row Number"

entity e:4it8-vhzu l:"Fertilizer publications, forms, tonnage reports and lab analysis" t:url=https://data.oregon.gov/api/views/4it8-vhzu

property e:4it8-vhzu t:meta.view v:id=4it8-vhzu v:category="Natural Resources" v:averageRating=0 v:name="Fertilizer publications, forms, tonnage reports and lab analysis"

property e:4it8-vhzu t:meta.view.owner v:id=xzpq-yk3z v:screenName="Andy Zimmerman" v:displayName="Andy Zimmerman"

property e:4it8-vhzu t:meta.view.tableauthor v:id=xzpq-yk3z v:screenName="Andy Zimmerman" v:roleName=editor v:displayName="Andy Zimmerman"
```

## Top Records

```ls
| :updated_at | publication    | information_x                                                                                                                      | 
| =========== | ============== | ================================================================================================================================== | 
| 1395230028  | Heavy metals   | [application/pdf; charset=binary, eRj33R6c4Lunj1zuw5tPFZF-nKjM6QPc7iezk9qU9L0, Fertilizer metal level rule development.pdf, 14073] | 
| 1395230045  | Heavy metals   | [application/pdf; charset=binary, NryrrBVoOHaVFKbUjxiLGnsSR5XFUcKRjNJVuKHQ-lM, Heavy metals in fertilizers.pdf, 176309]            | 
| 1395230065  | Heavy metals   | [application/pdf; charset=binary, Kog-Vc5n5mzOJyIX8_hgapS0AFqKukvo9C45N1AxgZE, Review of heavy metals limits.pdf, 51185]           | 
| 1404743325  | Tonnage report | [application/pdf; charset=binary, wKBhnfXwzrzn7h_SKzTsUztXXGJemjWDSGOLj_Im3dI, 2005_Oregon_Tonnage .pdf, 386939]                   | 
| 1438858545  | Lab analysis   | [application/pdf; charset=binary, B66TFLQRarcCnOwXRTnT7AOwCq5S1ab91pDv2AYW3OA, 2013_micro_results.pdf, 65024]                      | 
| 1438858547  | Lab analysis   | [application/pdf; charset=binary, sPg03TpKzPQgLvom-xevWeq0XwlDujjFTkp-qOrtVTk, 2010_lab_analysis_results.pdf, 127314]              | 
| 1438858549  | Lab analysis   | [application/pdf; charset=binary, 9lD0rhRL9cY_voOogARwltntn94q9kMprSR8_k0nOpg, 2009_lab_analysis_results.pdf, 148099]              | 
| 1438858552  | Lab analysis   | [application/pdf; charset=binary, deNpXjxX0eM1UgHKmzbQ2W8kqJjuCBvG3qf_rcasVmE, 2008_lab_analysis_results.pdf, 122592]              | 
| 1438858554  | Lab analysis   | [application/pdf; charset=binary, hHbr0jBNb6l-zBbRcBMdKv7XUEtVqvjNSDU8XWyqkFU, 2006 lab analysis results.pdf, 91341]               | 
| 1438858557  | Lab analysis   | [application/pdf; charset=binary, SDgSUaKy5u3P2w4F-na6OLx7hpkgDgaJ26GPTTQx62s, 2014_lab_analyses_results.pdf, 225466]              | 
```