# Local Severe Weather Warning Systems in Missouri

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/local-severe-weather-warning-systems-in-missouri-ff05b) |
| Metadata | [Link](https://data.mo.gov/api/views/n59h-ggai) |
| Data: JSON | [100 Rows](https://data.mo.gov/api/views/n59h-ggai/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.mo.gov/api/views/n59h-ggai/rows.csv?max_rows=100) |
| Host | data.mo.gov |
| Id | n59h-ggai |
| Name | Local Severe Weather Warning Systems in Missouri |
| Attribution | Department of Public Safety |
| Category | Public Safety |
| Tags | weather, alerts, notifications, public safety |
| Created | 2012-03-01T19:00:24Z |
| Publication Date | 2016-03-21T18:11:33Z |

## Description

List of 'Severe Weather Alert Systems' throughout Missouri provided by local governments, media outlets, and other sources.

## Columns

```ls
| Included | Schema Type | Field Name    | Name          | Data Type | Render Type |
| ======== | =========== | ============= | ============= | ========= | =========== |
| No       | time        | :updated_at   | updated_at    | meta_data | meta_data   |
| Yes      | series tag  | county        | County        | text      | text        |
| Yes      | series tag  | web_site      | Web Site      | url       | url         |
| Yes      | series tag  | notifications | Notifications | text      | text        |
| Yes      | series tag  | user_fees     | User Fees     | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:n59h-ggai d:2016-03-21T11:08:54.000Z t:notifications="KSHB Severe Weather Alerts--Mobile ""Coming Soon""" t:county=Adair t:user_fees=None t:web_site="http://contests.kshb.com/engine/Registration.aspx?contestid=17903" m:row_number.n59h-ggai=1

series e:n59h-ggai d:2016-03-21T11:08:54.000Z t:notifications="Severe Warning Systems Weather Alerts" t:county="*** All Areas ***" t:user_fees=None t:web_site=http://severewarningsystems.com/sms_signup.html m:row_number.n59h-ggai=2

series e:n59h-ggai d:2016-03-21T11:08:54.000Z t:notifications="The Weather Channel Severe Weather Alerts" t:county="*** All Areas ***" t:user_fees=None t:web_site="https://registration.weather.com/ursa/alerts/step1?initAlerts=SVR" m:row_number.n59h-ggai=3
```

## Meta Commands

```ls
metric m:row_number.n59h-ggai p:long l:"Row Number"

entity e:n59h-ggai l:"Local Severe Weather Warning Systems in Missouri" t:attribution="Department of Public Safety" t:url=https://data.mo.gov/api/views/n59h-ggai

property e:n59h-ggai t:meta.view v:id=n59h-ggai v:category="Public Safety" v:averageRating=0 v:name="Local Severe Weather Warning Systems in Missouri" v:attribution="Department of Public Safety"

property e:n59h-ggai t:meta.view.license v:name="Public Domain"

property e:n59h-ggai t:meta.view.owner v:id=s7tu-4ex9 v:screenName=hdolce v:displayName=hdolce

property e:n59h-ggai t:meta.view.tableauthor v:id=s7tu-4ex9 v:screenName=hdolce v:roleName=editor v:displayName=hdolce
```

## Top Records

```ls
| :updated_at | county            | web_site                                                                                   | notifications                                     | user_fees                                | 
| =========== | ================= | ========================================================================================== | ================================================= | ======================================== | 
| 1458558534  | Adair             | [http://contests.kshb.com/engine/Registration.aspx?contestid=17903, null]                  | KSHB Severe Weather Alerts--Mobile "Coming Soon"  | None                                     | 
| 1458558534  | *** All Areas *** | [http://severewarningsystems.com/sms_signup.html, null]                                    | Severe Warning Systems Weather Alerts             | None                                     | 
| 1458558534  | *** All Areas *** | [https://registration.weather.com/ursa/alerts/step1?initAlerts=SVR, null]                  | The Weather Channel Severe Weather Alerts         | None                                     | 
| 1458558534  | *** All Areas *** | [http://www.wunderground.com/email/emailsettings.asp, null]                                | Wunderground.com Weather Alerts                   | Free or paid membership, user can choose | 
| 1458558534  | Andrew            | [http://my.textcaster.com/asa/Default.aspx?ID=8076a835-5095-4275-a4e9-d2c9e6b827e4, null]  | St. Joseph News Press Severe Weather Alert Emails | None                                     | 
| 1458558534  | Andrew            | [http://contests.kshb.com/engine/Registration.aspx?contestid=17903, null]                  | KSHB Severe Weather Alerts--Mobile "Coming Soon"  | None                                     | 
| 1458558534  | Andrew            | [http://my.textcaster.com/asa/Default.aspx?ID=8076a835-5095-4275-a4e9-d2c9e6b827e4, null]  | KCTV Severe Weather Text Alerts                   | None                                     | 
| 1458558534  | Andrew            | [http://www.kansascity.com/textalerts/, null]                                              | Kansas City Star Severe Weather Alerts            | None                                     | 
| 1458558534  | Atchison          | [https://my.textcaster.com/asa/Default.aspx?ID=d6c55bb5-270f-4ede-8025-4941c7ca1aa9, null] | Textcaster Severe Weather Warnings                | None                                     | 
| 1458558534  | Atchison          | [http://www.kansascity.com/textalerts/, null]                                              | Kansas City Star Severe Weather Alerts            | None                                     | 
```