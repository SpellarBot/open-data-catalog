# Calls for Service 2013

## Dataset

* [Dataset URL](https://data.nola.gov/api/views/5fn8-vtui/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/calls-for-service-2013)
* [Metadata URL](https://data.nola.gov/api/views/5fn8-vtui)
* Id = 5fn8-vtui
* Name = Calls for Service 2013
* Attribution = Orleans Parish Communications District
* Category = Public Safety and Preparedness
* Tags = [crime, police, nopd]
* Created = 2013-02-04T22:04:42Z
* Publication Date = 2016-02-11T22:53:26Z
* Rows Updated = 2015-11-02T18:13:14Z

## Description

This dataset reflects incidents that have been reported to the New Orleans Police Department in 2013. Data is provided by Orleans Parish Communication District (OPCD), the administrative office of 9-1-1 for the City of New Orleans. In the OPCD system, NOPD may reclassify or change the signal type for up to 36 hours after the incident is marked up. For information about an incident after this time period, citizens may request police reports from the NOPD Public Records Division.  In order to protect the privacy of victims, addresses are shown at the block level and the call types cruelty to juveniles, juvenile attachment and missing juvenile have been removed in accordance with the Louisiana Public Records Act, L.R.S. 44:1.  Map coordinates (X,Y) have been removed for the following call types: Aggravated Rape, Aggravated Rape - MA, Crime Against Nature, Mental Patient, Oral Sexual Battery, Prostitution, Sexual Battery, Simple Rape, Simple Rape - Male V, and Soliciting for Prost.Disclaimer: These incidents may be based upon preliminary information supplied to the Police Department by the reporting parties that have not been verified. The preliminary crime classifications may be changed at a later date based upon additional investigation and there is always the possibility of mechanical or human error. Therefore, the New Orleans Police Department does not guarantee (either expressed or implied) the accuracy, completeness, timeliness, or correct sequencing of the information and the information should not be used for comparison purposes over time. The New Orleans Police Department will not be responsible for any error or omission, or for the use of, or the results obtained from the use of this information. All data visualizations on maps should be considered approximate and attempts to derive specific addresses are strictly prohibited. The New Orleans Police Department is not responsible for the content of any off-site pages that are referenced by or that reference this web page other than an official City of New Orleans or New Orleans Police Department web page. The user specifically acknowledges that the New Orleans Police Department is not responsible for any defamatory, offensive, misleading, or illegal conduct of other users, links, or third parties and that the risk of injury from the foregoing rests entirely with the user. Any use of the information for commercial purposes is strictly prohibited. The unauthorized use of the words "New Orleans Police Department," "NOPD," or any colorable imitation of these words or the unauthorized use of the New Orleans Police Department logo is unlawful. This web page does not, in any way, authorize such use.

## Columns

```ls
| Name            | Field Name      | Data Type     | Render Type   | Schema Type    | Included | 
| =============== | =============== | ============= | ============= | ============== | ======== | 
| NOPD_Item       | nopd_item       | text          | text          | series tag     | Yes      | 
| Type_           | type_           | text          | text          | series tag     | Yes      | 
| TypeText        | typetext        | text          | text          | series tag     | Yes      | 
| Priority        | priority        | text          | text          | series tag     | Yes      | 
| MapX            | mapx            | number        | text          | numeric metric | Yes      | 
| MapY            | mapy            | number        | text          | numeric metric | Yes      | 
| TimeCreate      | timecreate      | calendar_date | calendar_date | time           | Yes      | 
| TimeDispatch    | timedispatch    | calendar_date | calendar_date |                | No       | 
| TimeArrive      | timearrive      | calendar_date | calendar_date |                | No       | 
| TimeClosed      | timeclosed      | calendar_date | calendar_date |                | No       | 
| Disposition     | disposition     | text          | text          | series tag     | Yes      | 
| DispositionText | dispositiontext | text          | text          | series tag     | Yes      | 
| BLOCK_ADDRESS   | block_address   | text          | text          |                | No       | 
| Zip             | zip             | text          | text          | series tag     | Yes      | 
| PoliceDistrict  | policedistrict  | text          | number        | series tag     | Yes      | 
```

## Time Field

```ls
Value = timecreate
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = timeclosed,timearrive,timedispatch,block_address
Annotation Fields = 
```

## Data Commands

```ls
series e:5fn8-vtui d:2012-12-31T23:59:34.000Z t:zip=70117 t:type_=94 t:nopd_item=A0000113 t:priority=2B t:dispositiontext=UNFOUNDED t:policedistrict=5 t:typetext="DISCHARGING FIREARM" t:disposition=UNF m:mapx=3696313 m:mapy=533332

series e:5fn8-vtui d:2012-12-31T23:59:49.000Z t:zip=70131 t:type_=94 t:nopd_item=A0000213 t:priority=2B t:dispositiontext=UNFOUNDED t:policedistrict=4 t:typetext="DISCHARGING FIREARM" t:disposition=UNF m:mapx=3710263 m:mapy=518976

series e:5fn8-vtui d:2013-01-01T00:00:22.000Z t:zip=70130 t:type_=67S t:nopd_item=A0000313 t:priority=1C t:dispositiontext=DUPLICATE t:policedistrict=8 t:typetext=SHOPLIFTING t:disposition=DUP m:mapx=3683068 m:mapy=531830
```

## Meta Commands

```ls
metric m:mapx l:MapX t:dataTypeName=number

metric m:mapy p:integer l:MapY t:dataTypeName=number

entity e:5fn8-vtui l:"Calls for Service 2013" t:attribution="Orleans Parish Communications District" t:url=https://data.nola.gov/api/views/5fn8-vtui

property e:5fn8-vtui t:meta.view d:2017-03-08T02:32:25.715Z v:id=5fn8-vtui v:category="Public Safety and Preparedness" v:averageRating=0 v:name="Calls for Service 2013" v:attribution="Orleans Parish Communications District"

property e:5fn8-vtui t:meta.view.license d:2017-03-08T02:32:25.715Z v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:5fn8-vtui t:meta.view.owner d:2017-03-08T02:32:25.715Z v:id=guap-8ddq v:profileImageUrlMedium=/api/users/guap-8ddq/profile_images/THUMB v:profileImageUrlLarge=/api/users/guap-8ddq/profile_images/LARGE v:screenName="City of New Orleans GIS Department" v:profileImageUrlSmall=/api/users/guap-8ddq/profile_images/TINY v:roleName=administrator v:displayName="City of New Orleans GIS Department" v:privilegesDisabled=false

property e:5fn8-vtui t:meta.view.tableauthor d:2017-03-08T02:32:25.715Z v:id=guap-8ddq v:profileImageUrlMedium=/api/users/guap-8ddq/profile_images/THUMB v:profileImageUrlLarge=/api/users/guap-8ddq/profile_images/LARGE v:screenName="City of New Orleans GIS Department" v:profileImageUrlSmall=/api/users/guap-8ddq/profile_images/TINY v:roleName=administrator v:displayName="City of New Orleans GIS Department" v:privilegesDisabled=false

property e:5fn8-vtui t:meta.view.metadata.custom_fields.common_core d:2017-03-08T02:32:25.715Z v:Contact_Email=data@nola.gov
```