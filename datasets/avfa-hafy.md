# PARC annual reports

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/parc-annual-reports-2ff82) |
| Metadata | [Link](https://data.oregon.gov/api/views/avfa-hafy) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/avfa-hafy/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/avfa-hafy/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | avfa-hafy |
| Name | PARC annual reports |
| Category | Natural Resources |
| Tags | parc |
| Created | 2014-04-22T19:31:05Z |
| Publication Date | 2016-02-25T21:19:46Z |

## Columns

```ls
| Included | Schema Type | Field Name    | Name          | Data Type | Render Type |
| ======== | =========== | ============= | ============= | ========= | =========== |
| No       | time        | :updated_at   | updated_at    | meta_data | meta_data   |
| Yes      | series tag  | years         | Years         | html      | html        |
| Yes      | series tag  | annual_report | Annual report | document  | document    |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:avfa-hafy d:2014-08-06T10:01:24.000Z t:annual_report.file_id=MDyYZEm-LsQ5VYf5Mg8vrLPQJAZvnpNdIc6jqrAYn6E t:annual_report.content_type="application/pdf; charset=binary" t:annual_report.size=1373847 t:years=<p>2009-11</p> t:annual_report.filename="PARC report 2009-11.pdf" m:row_number.avfa-hafy=1

series e:avfa-hafy d:2014-08-06T10:01:37.000Z t:annual_report.file_id=sfAkCSaycEfNRQtezpAxBTtD1smyOrjjmq1Vk60bjpk t:annual_report.content_type="application/pdf; charset=binary" t:annual_report.size=1272001 t:years="<p>2008-09</p>
<p>&nbsp;</p>" t:annual_report.filename="PARC report 2008-09.pdf" m:row_number.avfa-hafy=2

series e:avfa-hafy d:2014-08-06T10:02:06.000Z t:annual_report.file_id=KjDwX-0SNeNMHugk9VHiQskGMgqXabti8tDakFRnMv4 t:annual_report.content_type="application/pdf; charset=binary" t:annual_report.size=359290 t:years=<p>2006-07</p> t:annual_report.filename="PARC report 2006-07.pdf" m:row_number.avfa-hafy=3
```

## Meta Commands

```ls
metric m:row_number.avfa-hafy p:long l:"Row Number"

entity e:avfa-hafy l:"PARC annual reports" t:url=https://data.oregon.gov/api/views/avfa-hafy

property e:avfa-hafy t:meta.view v:id=avfa-hafy v:category="Natural Resources" v:averageRating=0 v:name="PARC annual reports"

property e:avfa-hafy t:meta.view.owner v:id=xzpq-yk3z v:screenName="Andy Zimmerman" v:displayName="Andy Zimmerman"

property e:avfa-hafy t:meta.view.tableauthor v:id=xzpq-yk3z v:screenName="Andy Zimmerman" v:roleName=editor v:displayName="Andy Zimmerman"
```

## Top Records

```ls
| :updated_at | years     | annual_report                                                                                                    | 
| =========== | ========= | ================================================================================================================ | 
| 1407319284  | 2009-11   | [application/pdf; charset=binary, MDyYZEm-LsQ5VYf5Mg8vrLPQJAZvnpNdIc6jqrAYn6E, PARC report 2009-11.pdf, 1373847] | 
| 1407319297  | 2008-09
  | [application/pdf; charset=binary, sfAkCSaycEfNRQtezpAxBTtD1smyOrjjmq1Vk60bjpk, PARC report 2008-09.pdf, 1272001] | 
| 1407319326  | 2006-07   | [application/pdf; charset=binary, KjDwX-0SNeNMHugk9VHiQskGMgqXabti8tDakFRnMv4, PARC report 2006-07.pdf, 359290]  | 
| 1407319347  | 2005-06   | [application/pdf; charset=binary, 31t-OZehLtIQmAEgqF7jkOVpV2LrI3SRUKmP9ubEICU, PARC report 2005-06.pdf, 2915805] | 
| 1407319360  | 2001      | [application/pdf; charset=binary, tedJzlj5L5SpjHtNluvyueCreQ5nBogsiNvslNoPG-g, PARC report 2001.pdf, 216296]     | 
| 1407319379  | 2007-08
  | [application/pdf; charset=binary, -V6EMydW-VPHTWFrRtHQ7JgHJ5NHsbvRP00aQBOgsSw, PARC report 2007-08.pdf, 1397560] | 
| 1456406358  | 2011-13   | [application/pdf; charset=binary, f5d0098e-3af6-4923-801e-591731c3d030, PARC report 2011-13.pdf, 187334]         | 
```