# Hawaii State Ethics Commission's Lobbyist Registration Statements

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/hawaii-state-ethics-commissions-lobbyist-registration-statements-89353) |
| Metadata | [Link](https://data.hawaii.gov/api/views/gdxe-t5ff) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/gdxe-t5ff/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/gdxe-t5ff/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | gdxe-t5ff |
| Name | Hawaii State Ethics Commission's Lobbyist Registration Statements |
| Created | 2013-10-29T22:49:30Z |
| Publication Date | 2017-04-18T02:02:34Z |

## Columns

```ls
| Included | Schema Type | Field Name        | Name              | Data Type     | Render Type   |
| ======== | =========== | ================= | ================= | ============= | ============= |
| Yes      | series tag  | registration_form | View              | url           | url           |
| Yes      | series tag  | lobbyist          | Lobbyist Name     | text          | text          |
| Yes      | series tag  | organization      | Organization Name | text          | text          |
| Yes      | series tag  | lobby_year        | Lobby Year        | text          | text          |
| Yes      | time        | registration      | Registration      | calendar_date | calendar_date |
| No       |             | termination       | Termination       | calendar_date | calendar_date |
| Yes      | series tag  | original          | Original          | checkbox      | checkbox      |
| Yes      | series tag  | amended           | Amended           | checkbox      | checkbox      |
```

## Time Field

```ls
Value = registration
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = termination
```

## Data Commands

```ls
series e:gdxe-t5ff d:2013-01-14T00:00:00.000Z t:amended=false t:organization="Hawaii Family Forum" t:registration_form=http://files.hawaii.gov/ethics/lobreg/1314/Kfx10-1000.pdf t:lobbyist="Andrade, Eva M." t:original=true t:lobby_year=2013-2014 m:row_number.gdxe-t5ff=1

series e:gdxe-t5ff d:2015-05-18T00:00:00.000Z t:amended=false t:organization="Hawaii Pilots Association" t:registration_form=http://files.hawaii.gov/ethics/lobreg/1516/Kfx10-10009.pdf t:lobbyist="Brown, Sinclair" t:original=true t:lobby_year=2015-2016 m:row_number.gdxe-t5ff=2

series e:gdxe-t5ff d:2013-01-14T00:00:00.000Z t:amended=false t:organization="Investment Company Institute" t:registration_form=http://files.hawaii.gov/ethics/lobreg/1314/Kfx10-1001.pdf t:lobbyist="Natori, Nathan T." t:original=true t:lobby_year=2013-2014 m:row_number.gdxe-t5ff=3
```

## Meta Commands

```ls
metric m:row_number.gdxe-t5ff p:long l:"Row Number"

entity e:gdxe-t5ff l:"Hawaii State Ethics Commission's Lobbyist Registration Statements" t:url=https://data.hawaii.gov/api/views/gdxe-t5ff

property e:gdxe-t5ff t:meta.view v:id=gdxe-t5ff v:averageRating=0 v:name="Hawaii State Ethics Commission's Lobbyist Registration Statements"

property e:gdxe-t5ff t:meta.view.owner v:id=ikz2-vjne v:screenName=PatrickLui v:displayName=PatrickLui

property e:gdxe-t5ff t:meta.view.tableauthor v:id=ikz2-vjne v:screenName=PatrickLui v:roleName=editor v:displayName=PatrickLui
```

## Top Records

```ls
| registration_form                                                  | lobbyist               | organization                                      | lobby_year | registration        | termination         | original | amended | 
| ================================================================== | ====================== | ================================================= | ========== | =================== | =================== | ======== | ======= | 
| [http://files.hawaii.gov/ethics/lobreg/1314/Kfx10-1000.pdf, Form]  | Andrade, Eva M.        | Hawaii Family Forum                               | 2013-2014  | 2013-01-14T00:00:00 | 2014-12-31T00:00:00 | true     | false   | 
| [http://files.hawaii.gov/ethics/lobreg/1516/Kfx10-10009.pdf, Form] | Brown, Sinclair        | Hawaii Pilots Association                         | 2015-2016  | 2015-05-18T00:00:00 | 2016-12-31T00:00:00 | true     | false   | 
| [http://files.hawaii.gov/ethics/lobreg/1314/Kfx10-1001.pdf, Form]  | Natori, Nathan T.      | Investment Company Institute                      | 2013-2014  | 2013-01-14T00:00:00 | 2014-12-31T00:00:00 | true     | false   | 
| [http://files.hawaii.gov/ethics/lobreg/1516/Kfx10-10010.pdf, Form] | Nakamura, Cynthia S.   | Hawaii Pacific Health                             | 2015-2016  | 2015-05-12T00:00:00 | 2016-12-31T00:00:00 | true     | false   | 
| [http://files.hawaii.gov/ethics/lobreg/1516/Kfx10-10011.pdf, Form] | Pear, Charles E.       | Disney Vacation Development, Inc.                 | 2015-2016  | 2015-05-06T00:00:00 | 2016-12-31T00:00:00 | true     | false   | 
| [http://files.hawaii.gov/ethics/lobreg/1314/Kfx10-1002.pdf, Form]  | Kamakeeaina, Loyna L.  | United Public Workers, AFSCME, Local 646, AFL-CIO | 2013-2014  | 2013-01-14T00:00:00 | 2014-12-31T00:00:00 | true     | false   | 
| [http://files.hawaii.gov/ethics/lobreg/1314/Kfx10-1003.pdf, Form]  | Kong Kee, Florence     | United Public Workers, AFSCME, Local 646, AFL-CIO | 2013-2014  | 2013-01-14T00:00:00 | 2014-12-31T00:00:00 | true     | false   | 
| [http://files.hawaii.gov/ethics/lobreg/1314/Kfx10-1004.pdf, Form]  | Matsuura, Scott A.     | Syngenta Hawaii LLC                               | 2013-2014  | 2013-01-14T00:00:00 | 2014-12-31T00:00:00 | true     | false   | 
| [http://files.hawaii.gov/ethics/lobreg/1516/Kfx10-10072.pdf, Form] | Garcia, Lyndsey Kanani | HiPHI dba Coalition for a Tobacco-Free Hawaii     | 2015-2016  | 2015-01-22T00:00:00 | 2015-12-10T00:00:00 | true     | false   | 
| [http://files.hawaii.gov/ethics/lobreg/1314/Kfx10-1013.pdf, Form]  | Halagao, Avelino J.    | Hawaiian Electric Industries, Inc.                | 2013-2014  | 2013-01-15T00:00:00 | 2014-12-31T00:00:00 | true     | false   | 
```