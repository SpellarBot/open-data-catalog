# Field burning season summaries

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/field-burning-season-summaries-edebc) |
| Metadata | [Link](https://data.oregon.gov/api/views/nn5f-3nxc) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/nn5f-3nxc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/nn5f-3nxc/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | nn5f-3nxc |
| Name | Field burning season summaries |
| Category | Natural Resources |
| Tags | field burning |
| Created | 2014-05-06T16:16:24Z |
| Publication Date | 2014-05-21T20:40:36Z |

## Columns

```ls
| Included | Schema Type | Field Name | Name      | Data Type     | Render Type   |
| ======== | =========== | ========== | ========= | ============= | ============= |
| Yes      | time        | year       | Year      | calendar_date | calendar_date |
| Yes      | series tag  | summaries  | Summaries | document      | document      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:nn5f-3nxc d:2013-05-01T00:00:00.000Z t:summaries.size=372537 t:summaries.content_type="application/pdf; charset=binary" t:summaries.file_id=jEz_vj-RpL5-mNyMgx8NtyKEbGEcGdWvLNOSN9OldEc t:summaries.filename=smoke_fb_sum_2013.pdf m:row_number.nn5f-3nxc=1

series e:nn5f-3nxc d:2012-05-01T00:00:00.000Z t:summaries.size=611630 t:summaries.content_type="application/pdf; charset=binary" t:summaries.file_id=MGB8KrWrDLfRp6nJfkiCH5f3M-NcINQXnPLHoIyH8II t:summaries.filename=smoke_fb_sum_2012.pdf m:row_number.nn5f-3nxc=2

series e:nn5f-3nxc d:2011-05-01T00:00:00.000Z t:summaries.size=599992 t:summaries.content_type="application/pdf; charset=binary" t:summaries.file_id=b6DWQsNx8emTp63G0k-XQmdDtoHTSCBC7U1rnrsmzMk t:summaries.filename=smoke_fb_sum_2011.pdf m:row_number.nn5f-3nxc=3
```

## Meta Commands

```ls
metric m:row_number.nn5f-3nxc p:long l:"Row Number"

entity e:nn5f-3nxc l:"Field burning season summaries" t:url=https://data.oregon.gov/api/views/nn5f-3nxc

property e:nn5f-3nxc t:meta.view v:id=nn5f-3nxc v:category="Natural Resources" v:averageRating=0 v:name="Field burning season summaries"

property e:nn5f-3nxc t:meta.view.owner v:id=xzpq-yk3z v:screenName="Andy Zimmerman" v:displayName="Andy Zimmerman"

property e:nn5f-3nxc t:meta.view.tableauthor v:id=xzpq-yk3z v:screenName="Andy Zimmerman" v:roleName=editor v:displayName="Andy Zimmerman"
```

## Top Records

```ls
| year                | summaries                                                                                                     | 
| =================== | ============================================================================================================= | 
| 2013-05-01T00:00:00 | [application/pdf; charset=binary, jEz_vj-RpL5-mNyMgx8NtyKEbGEcGdWvLNOSN9OldEc, smoke_fb_sum_2013.pdf, 372537] | 
| 2012-05-01T00:00:00 | [application/pdf; charset=binary, MGB8KrWrDLfRp6nJfkiCH5f3M-NcINQXnPLHoIyH8II, smoke_fb_sum_2012.pdf, 611630] | 
| 2011-05-01T00:00:00 | [application/pdf; charset=binary, b6DWQsNx8emTp63G0k-XQmdDtoHTSCBC7U1rnrsmzMk, smoke_fb_sum_2011.pdf, 599992] | 
| 2010-05-01T00:00:00 | [application/pdf; charset=binary, 7E8NbQ2x7cqQeXrtk52Hu2EPevR5liMqLhn3rqTpmkA, smoke_fb_sum_2010.pdf, 684944] | 
| 2009-05-01T00:00:00 | [application/pdf; charset=binary, 6rbjWCqM2hv_JoTEq3B76t2uHRqNC38z6p4LlCs0aQ4, smoke_fb_sum_2009.pdf, 413107] | 
| 2008-05-01T00:00:00 | [application/pdf; charset=binary, 7yDsEo41j4XHZSLyfMS9L7j-YwmCdtpHRQh-Yx7y7o0, smoke_fb_sum_2008.pdf, 665619] | 
| 2007-05-01T00:00:00 | [application/pdf; charset=binary, PAEp6M5wbPz7ySI-ZLp9W9sH4nDZjAEJBZUb7QTw4N4, smoke_fb_sum_2007.pdf, 663473] | 
| 2006-05-01T00:00:00 | [application/pdf; charset=binary, fShcW43mONLn2u2RKWolxYBeWWRwlYR7Y5QOJqtNY4U, smoke_fb_sum2006.pdf, 641483]  | 
| 2005-05-01T00:00:00 | [application/pdf; charset=binary, MT-t1j_HdkuXj69mZaOxaNogrrmWQkJpw4P7RO6s4C0, smoke_fb_sum_2005.pdf, 159421] | 
| 2004-05-01T00:00:00 | [application/pdf; charset=binary, qD7uRD0NHts1Ih3bYH-I_kSW2ST2oo_teIaWa6-my1g, smoke_fb_sum_2004.pdf, 256550] | 
```