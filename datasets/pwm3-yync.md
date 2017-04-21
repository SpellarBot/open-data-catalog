# Accessible Voting Centers

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/accessible-voting-centers-2ed8f) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/pwm3-yync) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/pwm3-yync/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/pwm3-yync/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | pwm3-yync |
| Name | Accessible Voting Centers |
| Attribution | King County Elections |
| Category | Election operations |
| Tags | vote, voting, accessible, handicapped, elections, ballot machine, avu, accessible voting unit, avc |
| Created | 2011-07-25T19:50:08Z |
| Publication Date | 2011-10-17T18:48:39Z |

## Description

Accessible Voting Centers for the upcoming election

## Columns

```ls
| Included | Schema Type | Field Name         | Name               | Data Type | Render Type |
| ======== | =========== | ================== | ================== | ========= | =========== |
| No       | time        | :updated_at        | updated_at         | meta_data | meta_data   |
| Yes      | series tag  | name               | Name               | html      | html        |
| No       |             | avc_address        | AVC address        | text      | text        |
| Yes      | series tag  | avc_city           | AVC city           | text      | text        |
| Yes      | series tag  | avc_state          | AVC state          | text      | text        |
| Yes      | series tag  | avc_zipcode        | AVC zipcode        | text      | text        |
| Yes      | series tag  | pre_election_days  | Pre-election days  | text      | text        |
| Yes      | series tag  | pre_election_hours | Pre-election hours | text      | text        |
| Yes      | series tag  | election_day       | Election day       | text      | text        |
| Yes      | series tag  | election_day_hours | Election day hours | text      | text        |
| Yes      | series tag  | photo              | Photo              | photo     | photo       |
| Yes      | series tag  | directions         | Directions         | url       | url         |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = avc_address
```

## Data Commands

```ls
series e:pwm3-yync d:2011-10-17T11:46:25.000Z t:directions=http://www.kingcounty.gov/Sites/elections/aboutus/directions.aspx t:election_day_hours="7:00 a.m. - 8:00 p.m." t:avc_state=WA t:name="<strong>King County Elections</strong>" t:avc_city=Renton t:election_day="Tuesday, November 8" t:avc_zipcode=98057 t:pre_election_hours="Monday - Friday, 8:30 a.m. - 4:30 p.m." t:pre_election_days="October 21 - November 7" t:photo=usrfWX13S-UoyBkm1HfHj3NpZyEk_WFNIWyU_wwFBKM m:row_number.pwm3-yync=1

series e:pwm3-yync d:2011-10-17T11:47:36.000Z t:directions="http://maps.google.com/maps?q=450+110th+Ave+NE+Bellevue&daddr=450+110th+Ave+NE,+Bellevue,+WA+98004&hl=en&sll=47.614148,-122.20693&sspn=0.006295,0.006295&gl=us&view=map&geocode=CSAVpRmcrnYZFcSI1gIdLkW3-A&z=16" t:election_day_hours="7:00 a.m. - 8:00 p.m." t:avc_state=WA t:name="<strong>Bellevue City Hall</strong>" t:avc_city=Bellevue t:election_day="Tuesday, November 8" t:avc_zipcode=98009 t:pre_election_hours="10 a.m. - 5 p.m." t:pre_election_days="Monday, November 7" t:photo=ID-AsCtkhcdlDuxMh5KITv7clsUuk5weBvcuktZ0XRw m:row_number.pwm3-yync=2

series e:pwm3-yync d:2011-10-17T11:47:51.000Z t:directions="http://maps.google.com/maps?q=401+South+Jackson+Street,+Seattle,+WA&hl=en&sll=47.614148,-122.20693&sspn=0.009909,0.017531&gl=us&z=16" t:election_day_hours="7:00 a.m. - 8:00 p.m." t:avc_state=WA t:name="<strong>Seattle, Union Station</strong>" t:avc_city=Seattle t:election_day="Tuesday, November 8" t:avc_zipcode=98104 t:pre_election_hours="10 a.m. - 5 p.m." t:pre_election_days="Monday, November 7" t:photo=h6VcH9Yigz6c-prWa8JRf0bdr1mx5NSyBkQIkjESl9Y m:row_number.pwm3-yync=3
```

## Meta Commands

```ls
metric m:row_number.pwm3-yync p:long l:"Row Number"

entity e:pwm3-yync l:"Accessible Voting Centers" t:attribution="King County Elections" t:url=https://data.kingcounty.gov/api/views/pwm3-yync

property e:pwm3-yync t:meta.view v:id=pwm3-yync v:category="Election operations" v:attributionLink=http://www.kingcounty.gov/elections/ v:averageRating=0 v:name="Accessible Voting Centers" v:attribution="King County Elections"

property e:pwm3-yync t:meta.view.license v:name="Public Domain"

property e:pwm3-yync t:meta.view.owner v:id=2gzv-6b6z v:profileImageUrlMedium=/api/users/2gzv-6b6z/profile_images/THUMB v:profileImageUrlLarge=/api/users/2gzv-6b6z/profile_images/LARGE v:screenName="King County Webteam" v:profileImageUrlSmall=/api/users/2gzv-6b6z/profile_images/TINY v:displayName="King County Webteam"

property e:pwm3-yync t:meta.view.tableauthor v:id=2gzv-6b6z v:profileImageUrlMedium=/api/users/2gzv-6b6z/profile_images/THUMB v:profileImageUrlLarge=/api/users/2gzv-6b6z/profile_images/LARGE v:screenName="King County Webteam" v:profileImageUrlSmall=/api/users/2gzv-6b6z/profile_images/TINY v:roleName=administrator v:displayName="King County Webteam"
```

## Top Records

```ls
| :updated_at | name                   | avc_address         | avc_city | avc_state | avc_zipcode | pre_election_days       | pre_election_hours                     | election_day        | election_day_hours     | photo                                       | directions                                                                                                                                                                                                                               | 
| =========== | ====================== | =================== | ======== | ========= | =========== | ======================= | ====================================== | =================== | ====================== | =========================================== | ======================================================================================================================================================================================================================================== | 
| 1318851985  | King County Elections  | 919 SW Grady Way    | Renton   | WA        | 98057       | October 21 - November 7 | Monday - Friday, 8:30 a.m. - 4:30 p.m. | Tuesday, November 8 | 7:00 a.m. - 8:00 p.m.  | usrfWX13S-UoyBkm1HfHj3NpZyEk_WFNIWyU_wwFBKM | [http://www.kingcounty.gov/Sites/elections/aboutus/directions.aspx, (Detailed directions)]                                                                                                                                               | 
| 1318852056  | Bellevue City Hall     | 450 110th Avenue NE | Bellevue | WA        | 98009       | Monday, November 7      | 10 a.m. - 5 p.m.                       | Tuesday, November 8 | 7:00 a.m. - 8:00 p.m.  | ID-AsCtkhcdlDuxMh5KITv7clsUuk5weBvcuktZ0XRw | [http://maps.google.com/maps?q=450+110th+Ave+NE+Bellevue&daddr=450+110th+Ave+NE,+Bellevue,+WA+98004&hl=en&sll=47.614148,-122.20693&sspn=0.006295,0.006295&gl=us&view=map&geocode=CSAVpRmcrnYZFcSI1gIdLkW3-A&z=16, (Detailed directions)] | 
| 1318852071  | Seattle, Union Station | 401 S. Jackson St   | Seattle  | WA        | 98104       | Monday, November 7      | 10 a.m. - 5 p.m.                       | Tuesday, November 8 | 7:00 a.m. - 8:00 p.m.  | h6VcH9Yigz6c-prWa8JRf0bdr1mx5NSyBkQIkjESl9Y | [http://maps.google.com/maps?q=401+South+Jackson+Street,+Seattle,+WA&hl=en&sll=47.614148,-122.20693&sspn=0.009909,0.017531&gl=us&z=16, (Detailed directions)]                                                                            | 
```