# Human Rights Calendar

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/human-rights-calendar) |
| Metadata | [Link](https://data.montgomerycountymd.gov/api/views/7tbu-af89) |
| Data: JSON | [100 Rows](https://data.montgomerycountymd.gov/api/views/7tbu-af89/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.montgomerycountymd.gov/api/views/7tbu-af89/rows.csv?max_rows=100) |
| Host | data.montgomerycountymd.gov |
| Id | 7tbu-af89 |
| Name | Human Rights Calendar |
| Attribution | Montgomery County, MD |
| Category | Community/Recreation |
| Tags | human_rights, calendar |
| Created | 2016-11-01T23:03:02Z |
| Publication Date | 2016-12-19T21:08:05Z |

## Description

Montgomery County Human Rights Calendar of Events. Update Frequency : Quarterly

## Columns

```ls
| Included | Schema Type | Field Name  | Name        | Data Type     | Render Type   |
| ======== | =========== | =========== | =========== | ============= | ============= |
| Yes      | time        | date        | Date        | calendar_date | calendar_date |
| Yes      | series tag  | event       | Event       | text          | text          |
| Yes      | series tag  | times       | Time(s)     | text          | text          |
| Yes      | series tag  | location    | Location    | text          | text          |
| No       |             | address     | Address     | text          | text          |
| Yes      | series tag  | description | Description | text          | text          |
| Yes      | series tag  | sponsors    | Sponsor(s)  | text          | text          |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = address
```

## Data Commands

```ls
series e:7tbu-af89 d:2017-04-13T00:00:00.000Z t:location="National Civil Rights Museum" t:times="830 am - 530 pm" t:sponsors=HRC/MCOHR t:description="tour sites in Memphis TN" t:event="Civil Rights Educational Tour" m:row_number.7tbu-af89=1

series e:7tbu-af89 d:2017-04-19T00:00:00.000Z t:location="Civic Center" t:times="1130 am - 330 pm" t:sponsors=IADHCG/MCOHR t:description="Legal requirements for real estate professionals" t:event="Fair Housing Workshop" m:row_number.7tbu-af89=2

series e:7tbu-af89 d:2016-08-29T00:00:00.000Z t:location="Rockville Memorial Library" t:times="7-9 pm" t:sponsors=HRC/MCOHR t:description="Meeting open to public" t:event="Human Rights Cmsn Meeting" m:row_number.7tbu-af89=3
```

## Meta Commands

```ls
metric m:row_number.7tbu-af89 p:long l:"Row Number"

entity e:7tbu-af89 l:"Human Rights Calendar" t:attribution="Montgomery County, MD" t:url=https://data.montgomerycountymd.gov/api/views/7tbu-af89

property e:7tbu-af89 t:meta.view v:id=7tbu-af89 v:category=Community/Recreation v:averageRating=0 v:name="Human Rights Calendar" v:attribution="Montgomery County, MD"

property e:7tbu-af89 t:meta.view.license v:name="Public Domain"

property e:7tbu-af89 t:meta.view.owner v:id=ajn4-zy65 v:screenName="MCG ESB Service" v:lastNotificationSeenAt=1491401045 v:displayName="MCG ESB Service"

property e:7tbu-af89 t:meta.view.tableauthor v:id=ajn4-zy65 v:screenName="MCG ESB Service" v:roleName=administrator v:lastNotificationSeenAt=1491401045 v:displayName="MCG ESB Service"
```

## Top Records

```ls
| date                | event                              | times            | location                     | address                                         | description                                      | sponsors      | 
| =================== | ================================== | ================ | ============================ | =============================================== | ================================================ | ============= | 
| 2017-04-13T00:00:00 | Civil Rights Educational Tour      | 830 am - 530 pm  | National Civil Rights Museum | 45 Mulberry St, Memphis, TN 38103               | tour sites in Memphis TN                         | HRC/MCOHR     | 
| 2017-04-19T00:00:00 | Fair Housing Workshop              | 1130 am - 330 pm | Civic Center                 | 2000 Shorefield Rd Wheaton, MD 20902            | Legal requirements for real estate professionals | IADHCG/MCOHR  | 
| 2016-08-29T00:00:00 | Human Rights Cmsn Meeting          | 7-9 pm           | Rockville Memorial Library   | 21 Maryland Ave., Suite 331, Rockville MD 20850 | Meeting open to public                           | HRC/MCOHR     | 
| 2016-10-12T00:00:00 | Comte Hate/Violence Meeting        | 7-9 pm           | Rockville Memorial Library   | 21 Maryland Ave., Suite 331, Rockville MD 20850 | Meeting open to public                           | COHV/MCOHR    | 
| 2017-02-08T00:00:00 | Comte Hate/Violence Meeting        | 7-9 pm           | Rockville Memorial Library   | 21 Maryland Ave., Suite 331, Rockville MD 20850 | Meeting open to public                           | COHV/MCOHR    | 
| 2016-09-27T00:00:00 | One Stop Employment Workshop       | 8 am - noon      | Civic Center                 | 8525 Fenton Street, Silver Spring, MD 20910     | Information about requirements for employers     | HRC/MCOHR     | 
| 2017-04-09T00:00:00 | Civil Rights Educational Tour      | 830 am - 530 pm  | King Center                  | 450 Auburn Ave NE, Atlanta, GA 30322            | tour MLK museum & burial sites                   | HRC/MCOHR     | 
| 2017-04-10T00:00:00 | Civil Rights Educational Tour      | 830 am - 530 pm  | Civil Rights Memorial Center | 400 Washington Av, Montgomery, AL 36104         | tour museums & Rosa Parks site                   | hrC/MCOHR     | 
| 2017-01-16T00:00:00 | Martin Luther King Jr. Celebration | 330-630 pm       | Strathmore Arts Center       | 10701 Rockville Pike, Rockville, MD 20852       | Celbration to honor civil rights leader          | MLK Committee | 
| 2016-07-25T00:00:00 | Human Rights Cmsn Meeting          | 7-9 pm           | Rockville Memorial Library   | 21 Maryland Ave., Suite 331, Rockville MD 20850 | Meeting open to public                           | HRC/MCOHR     | 
```