# Lobbyists on Behalf of the City Disclosure Reports

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/lobbyists-on-behalf-of-the-city-disclosure-reports) |
| Metadata | [Link](https://data.sfgov.org/api/views/sz7b-c3pn) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/sz7b-c3pn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/sz7b-c3pn/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | sz7b-c3pn |
| Name | Lobbyists on Behalf of the City Disclosure Reports |
| Attribution | San Francisco Ethics Commission |
| Category | City Management and Ethics |
| Created | 2015-07-28T22:43:31Z |
| Publication Date | 2017-08-29T15:55:14Z |

## Description

The San Francisco Sunshine Ordinance, S.F. Admin. Code Section 67.1 et seq., requires lobbyists who contract for economic consideration with the City to represent the City in matters before any local, regional, state or federal administrative or legislative body to file quarterly activity reports with the Ethics Commission. These persons and entities are referred to as “Lobbyists on Behalf of the City.”

Please note: Lobbyists on Behalf of the City should not be confused with lobbyists who attempt to influence City officers on local legislative or administrative action on behalf of private parties. The latter are regulated by the San Francisco Lobbyist Ordinance, S.F. Campaign and Governmental Conduct Code Section 2.100, et seq., not by the Sunshine Ordinance.

## Columns

```ls
| Included | Schema Type | Field Name                | Name                      | Data Type     | Render Type   |
| ======== | =========== | ========================= | ========================= | ============= | ============= |
| Yes      | series tag  | lobbyist_name             | Lobbyist Name             | text          | text          |
| Yes      | series tag  | report                    | Report                    | document      | document      |
| Yes      | time        | date_filed                | Date Filed                | calendar_date | calendar_date |
| No       |             | period_start_date         | Period Start Date         | calendar_date | calendar_date |
| No       |             | period_end_date           | Period End Date           | calendar_date | calendar_date |
| Yes      | series tag  | amendment_filing          | Amendment Filing          | checkbox      | checkbox      |
| No       |             | amendment_to_report_filed | Amendment to Report Filed | calendar_date | calendar_date |
```

## Time Field

```ls
Value = date_filed
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = period_start_date,period_end_date,amendment_to_report_filed
```

## Data Commands

```ls
series e:sz7b-c3pn d:2015-05-14T00:00:00.000Z t:report.size=1231828 t:report.content_type="application/pdf; charset=binary" t:report.file_id=9HIooxQA8K8VvZE-f8UVRn5VLcmzVZqDgQpIMqz2F34 t:lobbyist_name="SHAW / YODER / ANTWIH / INC" t:report.filename="SHAW, YODER, ANTWIH, Inc - Quarter 1 - 2015 - Period February 1, 2015 to April 30, 2015.pdf" m:row_number.sz7b-c3pn=1

series e:sz7b-c3pn d:2014-05-29T00:00:00.000Z t:report.size=549723 t:report.content_type="application/pdf; charset=binary" t:report.file_id=YGRdp7o1zBDcuhlhdepRfhmg8Z9ccLbFdiS-4jDFX94 t:lobbyist_name="Holland & Knight" t:report.filename=Holland.Knight.Quarter.1.2014.Period.February.1.2014.to.April.30.2014.pdf m:row_number.sz7b-c3pn=2

series e:sz7b-c3pn d:2014-11-19T00:00:00.000Z t:report.size=272098 t:report.content_type="application/pdf; charset=binary" t:report.file_id=S_uIPf_Ls-wLd1-5lXYEOHlB-6U8_C__bxGX33plWUU t:lobbyist_name="Daryl Owen Associates, Inc" t:report.filename="Daryl Owen Associates INC. - Quarter 3 - 2014 Period August 1, 2014 to October 31, 2014.pdf" m:row_number.sz7b-c3pn=3
```

## Meta Commands

```ls
metric m:row_number.sz7b-c3pn p:long l:"Row Number"

entity e:sz7b-c3pn l:"Lobbyists on Behalf of the City Disclosure Reports" t:attribution="San Francisco Ethics Commission" t:url=https://data.sfgov.org/api/views/sz7b-c3pn

property e:sz7b-c3pn t:meta.view d:2017-09-25T07:30:58.578Z v:averageRating=0 v:name="Lobbyists on Behalf of the City Disclosure Reports" v:attribution="San Francisco Ethics Commission" v:attributionLink=http://www.sfethics.org v:id=sz7b-c3pn v:category="City Management and Ethics"

property e:sz7b-c3pn t:meta.view.license d:2017-09-25T07:30:58.578Z v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:sz7b-c3pn t:meta.view.owner d:2017-09-25T07:30:58.578Z v:displayName="San Francisco Ethics Commission" v:lastNotificationSeenAt=1500665894 v:id=kcqd-yeev v:screenName="San Francisco Ethics Commission"

property e:sz7b-c3pn t:meta.view.tableauthor d:2017-09-25T07:30:58.578Z v:displayName="San Francisco Ethics Commission" v:lastNotificationSeenAt=1500665894 v:roleName=publisher v:id=kcqd-yeev v:screenName="San Francisco Ethics Commission"
```

## Top Records

```ls
| lobbyist_name               | report                                                                                                                                                                                  | date_filed          | period_start_date   | period_end_date     | amendment_filing | amendment_to_report_filed | 
| =========================== | ======================================================================================================================================================================================= | =================== | =================== | =================== | ================ | ========================= | 
| SHAW / YODER / ANTWIH / INC | [application/pdf; charset=binary, 9HIooxQA8K8VvZE-f8UVRn5VLcmzVZqDgQpIMqz2F34, SHAW, YODER, ANTWIH, Inc - Quarter 1 - 2015 - Period February 1, 2015 to April 30, 2015.pdf, 1231828]    | 2015-05-14T00:00:00 | 2015-02-01T00:00:00 | 2015-04-30T00:00:00 |                  |                           | 
| Holland & Knight            | [application/pdf; charset=binary, YGRdp7o1zBDcuhlhdepRfhmg8Z9ccLbFdiS-4jDFX94, Holland.Knight.Quarter.1.2014.Period.February.1.2014.to.April.30.2014.pdf, 549723]                       | 2014-05-29T00:00:00 | 2014-02-01T00:00:00 | 2014-04-30T00:00:00 |                  |                           | 
| Daryl Owen Associates, Inc  | [application/pdf; charset=binary, S_uIPf_Ls-wLd1-5lXYEOHlB-6U8_C__bxGX33plWUU, Daryl Owen Associates INC. - Quarter 3 - 2014 Period August 1, 2014 to October 31, 2014.pdf, 272098]     | 2014-11-19T00:00:00 | 2014-08-01T00:00:00 | 2014-10-31T00:00:00 |                  |                           | 
| SHAW / YODER / ANTWIH / INC | [application/pdf; charset=binary, sXWOq2QL5s_G0ecSi0K2Vw6rt5Egbz_GuCKiGWOcZ3I, SHAW YODER ANTWIH INC. - Quarter 3 - 2014 Period August 1, 2014 to October 31, 2014.pdf, 6479258]        | 2014-12-03T00:00:00 | 2014-08-01T00:00:00 | 2014-10-31T00:00:00 |                  |                           | 
| Daryl Owen Associates, Inc  | [application/pdf; charset=binary, EsjGFJGfmm2hOWCf9Vu6jjzWXgxzehlKX7jcqRhs20o, Daryl Owen Associates, Inc - Quarter 4 - 2014 - Period November 1, 2014 to January 31, 2014.pdf, 300757] | 2015-02-25T00:00:00 | 2014-11-01T00:00:00 | 2015-01-31T00:00:00 |                  |                           | 
| Daryl Owen Associates, Inc  | [application/pdf; charset=binary, jnDLvseYJRnM2CIVfFCIn3WRFuAS5yyzPbOyRoPvB7Y, Daryl.Owen.Quarter.1.2013.Period.February.1.to.April.30.2013.pdf, 312696]                                | 2013-05-31T00:00:00 | 2013-02-01T00:00:00 | 2013-04-30T00:00:00 |                  |                           | 
| Holland & Knight            | [application/pdf; charset=binary, 4zZdEtCUKZT2vkJpyV0I1mG46gxqCVOBZebqY3UI09k, Holland.Knight.Quarter.1.2013.Period.February.1.2013.to.April.30.2013.pdf, 553892]                       | 2013-06-06T00:00:00 | 2013-02-01T00:00:00 | 2013-04-30T00:00:00 |                  |                           | 
| Daryl Owen Associates, Inc  | [application/pdf; charset=binary, GtxGUoDrMNh2Dk5XsXKVfU2wa13Ha8K6HGpzagWcYdM, Daryl.Owen.Quarter.2.2013.Period.May.1.2013.to.July.31.2013.pdf, 299971]                                 | 2013-08-19T00:00:00 | 2013-05-01T00:00:00 | 2013-07-31T00:00:00 |                  |                           | 
| Holland & Knight            | [application/pdf; charset=binary, 0BqYbYpKqWQxgwVg3nzVr4O9-39ufv-8C6_kT6Wqbl8, Holland.Knight.Quarter.2.2013.Period.May.1.2013.to.July.31.2013.pdf, 544768]                             | 2013-08-27T00:00:00 | 2013-05-01T00:00:00 | 2013-07-31T00:00:00 |                  |                           | 
| Daryl Owen Associates, Inc  | [application/pdf; charset=binary, QAigJFY31EjeqjAtDkUOhOrtuEar1ALe2VpvZt6b6g0, Daryl.Owen.Quarter.1.2012.Period.February.1.2012.to.April.30.2012.pdf, 294488]                           | 2012-05-02T00:00:00 | 2012-02-01T00:00:00 | 2012-04-30T00:00:00 |                  |                           | 
```