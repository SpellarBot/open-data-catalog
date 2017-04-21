# Campaign Finance - FPPC Form 460 - Summary Totals

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/campaign-finance-fppc-form-460-summary-totals-ccf39) |
| Metadata | [Link](https://data.sfgov.org/api/views/4tts-fyix) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/4tts-fyix/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/4tts-fyix/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | 4tts-fyix |
| Name | Campaign Finance - FPPC Form 460 - Summary Totals |
| Attribution | San Francisco Ethics Commission |
| Category | City Management and Ethics |
| Tags | ethics, campaign, finance, summary, fppc, form, 460 |
| Created | 2012-04-30T16:54:54Z |
| Publication Date | 2014-08-21T08:09:00Z |

## Description

This dataset includes all summary totals e-filed on Fair Political Practices Commission (FPPC) Form 460 Summary Page from 1998 to the present.The data is current as of the last modified date on this dataset.See the data key for column definitions:  https://data.sfgov.org/Ethics/Campaign-Finance-Data-Key/wygs-cc76

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type     | Render Type   |
| ======== | ============== | =================== | =================== | ============= | ============= |
| Yes      | series tag     | filer_id            | Filer_ID            | text          | text          |
| Yes      | series tag     | filer_naml          | Filer_NamL          | text          | text          |
| Yes      | series tag     | report_num          | Report_Num          | text          | number        |
| Yes      | series tag     | committee_type      | Committee_Type      | text          | text          |
| No       |                | rpt_date            | Rpt_Date            | calendar_date | calendar_date |
| No       |                | from_date           | From_Date           | calendar_date | calendar_date |
| Yes      | time           | thru_date           | Thru_Date           | calendar_date | calendar_date |
| No       |                | elect_date          | Elect_Date          | calendar_date | calendar_date |
| Yes      | series tag     | tblcover_office_cd  | tblCover_Office_Cd  | text          | text          |
| Yes      | series tag     | tblcover_offic_dscr | tblCover_Offic_Dscr | text          | text          |
| Yes      | series tag     | rec_type            | Rec_Type            | text          | text          |
| Yes      | series tag     | form_type           | Form_Type           | text          | text          |
| Yes      | series tag     | line_item           | Line_Item           | text          | text          |
| Yes      | numeric metric | amount_a            | Amount_A            | money         | money         |
| Yes      | numeric metric | amount_b            | Amount_B            | money         | money         |
| Yes      | numeric metric | amount_c            | Amount_C            | money         | money         |
```

## Time Field

```ls
Value = thru_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = rpt_date,from_date,elect_date
```

## Data Commands

```ls
series e:4tts-fyix d:2016-06-30T00:00:00.000Z t:report_num=0 t:form_type=B1 t:rec_type=SMRY t:filer_id=1381957 t:committee_type=CAO t:line_item=1 t:filer_naml="Joshua Arce for Supervisor 2016" m:amount_a=0

series e:4tts-fyix d:2016-10-22T00:00:00.000Z t:report_num=0 t:form_type=H t:rec_type=SMRY t:filer_id=921622 t:committee_type=RCP t:line_item=1 t:filer_naml="San Francisco Taxpayers Association" m:amount_a=0

series e:4tts-fyix d:2016-06-30T00:00:00.000Z t:report_num=0 t:form_type=C t:rec_type=SMRY t:filer_id=1385115 t:committee_type=CTL t:line_item=2 t:filer_naml="Jill Wynns for Democratic Central Committee 2016" m:amount_a=0
```

## Meta Commands

```ls
metric m:amount_a p:double l:Amount_A d:"If Form_Type=F460 then Total this period (From Attached Schedules), if schedule letter value = line item from subtotal on 460 form schedule. If Form Type=other FPPC form, refer to the applicable summary page" t:dataTypeName=money

metric m:amount_b p:double l:Amount_B d:"If Form_Type=F460 then Calendar Year Total to Date, if schedule letter value = line item from subtotal on 460 form schedule. If Form Type=other FPPC form, refer to the applicable summary page" t:dataTypeName=money

metric m:amount_c p:integer l:Amount_C d:"If Form_Type=F460 then Election Total to Date (No longer in use), if schedule letter value = line item from subtotal on 460 form schedule. If Form Type=other FPPC form, refer to the applicable summary page" t:dataTypeName=money

entity e:4tts-fyix l:"Campaign Finance - FPPC Form 460 - Summary Totals" t:attribution="San Francisco Ethics Commission" t:url=https://data.sfgov.org/api/views/4tts-fyix

property e:4tts-fyix t:meta.view v:id=4tts-fyix v:category="City Management and Ethics" v:attributionLink="http://nf4.netfile.com/pub2?aid=sfo" v:averageRating=0 v:name="Campaign Finance - FPPC Form 460 - Summary Totals" v:attribution="San Francisco Ethics Commission"

property e:4tts-fyix t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:4tts-fyix t:meta.view.owner v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:displayName="Steven Massey"

property e:4tts-fyix t:meta.view.tableauthor v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:roleName=publisher v:displayName="Steven Massey"
```

## Top Records

```ls
| filer_id | filer_naml                                                          | report_num | committee_type | rpt_date            | from_date           | thru_date           | elect_date          | tblcover_office_cd | tblcover_offic_dscr | rec_type | form_type | line_item | amount_a | amount_b | amount_c | 
| ======== | =================================================================== | ========== | ============== | =================== | =================== | =================== | =================== | ================== | =================== | ======== | ========= | ========= | ======== | ======== | ======== | 
| 1381957  | Joshua Arce for Supervisor 2016                                     | 0          | CAO            | 2016-07-27T00:00:00 | 2016-05-22T00:00:00 | 2016-06-30T00:00:00 |                     |                    |                     | SMRY     | B1        | 1         | 0        |          |          | 
| 921622   | San Francisco Taxpayers Association                                 | 0          | RCP            | 2016-10-25T00:00:00 | 2016-09-25T00:00:00 | 2016-10-22T00:00:00 | 2016-11-08T00:00:00 |                    |                     | SMRY     | H         | 1         | 0        |          |          | 
| 1385115  | Jill Wynns for Democratic Central Committee 2016                    | 0          | CTL            | 2016-08-01T00:00:00 | 2016-05-22T00:00:00 | 2016-06-30T00:00:00 | 2016-06-07T00:00:00 |                    |                     | SMRY     | C         | 2         | 0        |          |          | 
| 1367704  | Transport Workers Union Local 250A COPE Fund                        | 1          | RCP            | 2016-08-24T00:00:00 | 2016-05-22T00:00:00 | 2016-06-30T00:00:00 | 2016-06-07T00:00:00 |                    |                     | SMRY     | F460      | 10        | 0        | 0        |          | 
| 1381957  | Joshua Arce for Supervisor 2016                                     | 1          | CAO            | 2016-05-26T00:00:00 | 2016-04-24T00:00:00 | 2016-05-21T00:00:00 | 2016-11-08T00:00:00 |                    |                     | SMRY     | F         | 2         | 2060.63  |          |          | 
| 1386300  | Yes on S, San Franciscans for the Arts & Ending Family Homelessness | 0          | BMC            | 2016-10-27T00:00:00 | 2016-09-25T00:00:00 | 2016-10-22T00:00:00 | 2016-11-08T00:00:00 |                    |                     | SMRY     | F460      | 13        | 140713   |          |          | 
| 941562   | SAN FRANCISCO LABOR COUNCIL LABOR & NEIGHBOR PAC                    | 0          | RCP            | 2016-09-28T00:00:00 | 2016-07-01T00:00:00 | 2016-09-24T00:00:00 |                     |                    |                     | SMRY     | C         | 3         | 0        |          |          | 
| 1342652  | San Francisco Latino Democratic Club                                | 0          | RCP            | 2016-05-25T00:00:00 | 2016-04-24T00:00:00 | 2016-05-21T00:00:00 | 2016-06-07T00:00:00 |                    |                     | SMRY     | A         | 3         | 23.87    |          |          | 
| pending  | 2016 SF Sunshine Ordinance Amendments                               | 0          | BMC            | 2016-07-28T00:00:00 | 2016-07-01T00:00:00 | 2016-07-15T00:00:00 | 2016-11-08T00:00:00 |                    |                     | SMRY     | F460      | 7         | 0        | 0        |          | 
| 1386717  | De Guzman for Supervisor 2016                                       | 0          | CTL            | 2016-08-03T00:00:00 | 2016-01-01T00:00:00 | 2016-06-30T00:00:00 | 2016-11-08T00:00:00 |                    |                     | SMRY     | F460      | 12        | 0        |          |          | 
```