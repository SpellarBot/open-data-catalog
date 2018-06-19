# Campaign Consultants - Appointment to Public Office

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/campaign-consultants-appointment-to-public-office-375cd) |
| Metadata | [Link](https://data.sfgov.org/api/views/tgmn-chny) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/tgmn-chny/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/tgmn-chny/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | tgmn-chny |
| Name | Campaign Consultants - Appointment to Public Office |
| Attribution | San Francisco Ethics Commission |
| Category | City Management and Ethics |
| Tags | campaign consultant, ethics, appointments, public office |
| Created | 2013-07-22T21:12:28Z |
| Publication Date | 2013-10-01T23:52:45Z |

## Description

If the campaign consultant is appointed to public office during the reporting period and the appointment is made by a local officeholder who is the campaign consultant's client, the campaign consultant must report the public office to which the filer was appointed, the date of the appointment, and the name of the officeholder who appointed the campaign consultant.??

## Columns

```ls
| Included | Schema Type | Field Name          | Name                | Data Type     | Render Type   |
| ======== | =========== | =================== | =================== | ============= | ============= |
| Yes      | series tag  | campaign_consultant | Campaign Consultant | text          | text          |
| Yes      | series tag  | employee            | Employee            | text          | text          |
| Yes      | series tag  | department          | Department          | text          | text          |
| Yes      | series tag  | city_position       | City Position       | text          | text          |
| Yes      | time        | appointment_date    | Appointment Date    | calendar_date | calendar_date |
| Yes      | series tag  | appointing_officer  | Appointing Officer  | text          | text          |
| No       |             | quarter_start_date  | Quarter Start Date  | calendar_date | calendar_date |
| No       |             | quarter_end_date    | Quarter End Date    | calendar_date | calendar_date |
| No       |             | quarter             | Quarter             | number        | text          |
| No       |             | year                | Year                | number        | text          |
```

## Time Field

```ls
Value = appointment_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = quarter_start_date,quarter_end_date,quarter,year
```

## Data Commands

```ls
series e:tgmn-chny d:2010-05-14T00:00:00.000Z t:city_position="Board member" t:department="Golden Gate Park Concourse Authority" t:campaign_consultant="SGR Consulting" t:employee="Roumeliotes, Stefanie" t:appointing_officer="Newsom, Gavin" m:row_number.tgmn-chny=1
```

## Meta Commands

```ls
metric m:row_number.tgmn-chny p:long l:"Row Number"

entity e:tgmn-chny l:"Campaign Consultants - Appointment to Public Office" t:attribution="San Francisco Ethics Commission" t:url=https://data.sfgov.org/api/views/tgmn-chny

property e:tgmn-chny t:meta.view v:id=tgmn-chny v:category="City Management and Ethics" v:attributionLink=http://www.sfethics.org v:averageRating=0 v:name="Campaign Consultants - Appointment to Public Office" v:attribution="San Francisco Ethics Commission"

property e:tgmn-chny t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:tgmn-chny t:meta.view.owner v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:displayName="Steven Massey"

property e:tgmn-chny t:meta.view.tableauthor v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:roleName=publisher v:displayName="Steven Massey"
```

## Top Records

```ls
| campaign_consultant | employee              | department                           | city_position | appointment_date    | appointing_officer | quarter_start_date  | quarter_end_date    | quarter | year | 
| =================== | ===================== | ==================================== | ============= | =================== | ================== | =================== | =================== | ======= | ==== | 
| SGR Consulting      | Roumeliotes, Stefanie | Golden Gate Park Concourse Authority | Board member  | 2010-05-14T00:00:00 | Newsom, Gavin      | 2010-06-01T00:00:00 | 2010-08-31T00:00:00 | 3       | 2010 | 
```