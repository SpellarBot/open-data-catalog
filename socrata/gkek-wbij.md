# Organizational Reports For Hawaii State and County Candidates

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/organizational-reports-for-hawaii-state-and-county-candidates-4908e) |
| Metadata | [Link](https://data.hawaii.gov/api/views/gkek-wbij) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/gkek-wbij/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/gkek-wbij/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | gkek-wbij |
| Name | Organizational Reports For Hawaii State and County Candidates |
| Attribution | State of Hawaii; Campaign Spending Commission |
| Category | Community |
| Tags | campaign spending commission, campaign finance, candidate, hawaii candidates, contributions, political contributions, campaign contributions, campaign spending |
| Created | 2013-06-19T21:50:18Z |
| Publication Date | 2017-03-13T21:28:14Z |

## Columns

```ls
| Included | Schema Type    | Field Name               | Name                     | Data Type     | Render Type   |
| ======== | ============== | ======================== | ======================== | ============= | ============= |
| Yes      | series tag     | reg_no                   | Reg No                   | text          | text          |
| Yes      | series tag     | candidate_name           | Candidate Name           | text          | text          |
| Yes      | series tag     | candidate_committee_name | Candidate Committee Name | text          | text          |
| No       |                | address_1                | Address 1                | text          | text          |
| No       |                | address_2                | Address 2                | text          | text          |
| Yes      | series tag     | city                     | City                     | text          | text          |
| Yes      | series tag     | state                    | State                    | text          | text          |
| Yes      | series tag     | zip_code                 | Zip Code                 | text          | text          |
| Yes      | series tag     | business_phone           | Business Phone           | text          | text          |
| Yes      | series tag     | chairperson_name         | Chairperson Name         | text          | text          |
| No       |                | chair_address_1          | Chair Address 1          | text          | text          |
| No       |                | chair_address_2          | Chair Address 2          | text          | text          |
| Yes      | series tag     | chair_city               | Chair City               | text          | text          |
| Yes      | series tag     | chair_state              | Chair State              | text          | text          |
| Yes      | series tag     | chair_zip_code           | Chair Zip Code           | text          | text          |
| Yes      | series tag     | chair_business_phone     | Chair Business Phone     | text          | text          |
| Yes      | series tag     | treasurer_name           | Treasurer Name           | text          | text          |
| No       |                | treasurer_address_1      | Treasurer Address 1      | text          | text          |
| No       |                | treasurer_address_2      | Treasurer Address 2      | text          | text          |
| Yes      | series tag     | treasurer_city           | Treasurer City           | text          | text          |
| Yes      | series tag     | treasurer_state          | Treasurer State          | text          | text          |
| Yes      | series tag     | treasurer_zip_code       | Treasurer Zip Code       | text          | text          |
| Yes      | series tag     | treasurer_business_phone | Treasurer Business Phone | text          | text          |
| Yes      | series tag     | office                   | Office                   | text          | text          |
| Yes      | series tag     | district                 | District                 | text          | text          |
| Yes      | series tag     | county                   | County                   | text          | text          |
| Yes      | series tag     | party                    | Party                    | text          | text          |
| Yes      | series tag     | terminated               | Terminated               | text          | text          |
| Yes      | numeric metric | in_office                | In-Office                | number        | text          |
| Yes      | time           | filing_date              | Filing Date              | calendar_date | calendar_date |
```

## Time Field

```ls
Value = filing_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = address_1,address_2,chair_address_1,chair_address_2,treasurer_address_1,treasurer_address_2
```

## Data Commands

```ls
series e:gkek-wbij d:2014-03-21T13:21:35.000Z t:chair_city=Naalehu t:office="Hawaii Council" t:treasurer_name="Martin, Robert M." t:zip_code=96737 t:treasurer_state=HI t:candidate_name="Abbett, Richard" t:candidate_committee_name="Friends of Richard Abbett" t:state=HI t:treasurer_city=Naalehu t:party=Non-Partisan t:reg_no=CC11028 t:city="Ocean View" t:chairperson_name="Miller, Jendayi T." t:chair_zip_code=96772 t:business_phone=8083336241 t:county=Hawaii t:terminated=Y t:chair_state=HI t:treasurer_business_phone=8084431596 t:chair_business_phone=8083339392 t:treasurer_zip_code=96772 t:district=6 m:in_office=0

series e:gkek-wbij d:2016-06-15T01:42:40.000Z t:chair_city=Haiku t:office=House t:treasurer_name="Eno, Jason" t:zip_code=96793 t:treasurer_state=HI t:candidate_name="Abbett, Richard" t:candidate_committee_name="Richard Abbett for House" t:state=HI t:treasurer_city=Haiku t:party=Democrat t:reg_no=CC11314 t:city=Wailuku t:chairperson_name="Eno, Jason" t:chair_zip_code=96708 t:business_phone=808-268-3422 t:terminated=N t:chair_state=HI t:treasurer_business_phone=808-268-3422 t:chair_business_phone=808-268-3422 t:treasurer_zip_code=96708 t:district=8 m:in_office=0

series e:gkek-wbij d:2008-08-05T15:04:11.000Z t:chair_city=Honolulu t:office=House t:treasurer_name="Abe, Michael K." t:zip_code=96816 t:treasurer_state=HI t:candidate_name="Abe, Michael" t:candidate_committee_name="Mike Abe for State House" t:state=HI t:treasurer_city=Honolulu t:party=Democrat t:reg_no=CC10496 t:city=Honolulu t:chairperson_name="Abe, Michael K." t:chair_zip_code=96816 t:business_phone=7346603 t:terminated=Y t:chair_state=HI t:treasurer_business_phone=7346603 t:chair_business_phone=7346603 t:treasurer_zip_code=96816 t:district=19 m:in_office=0
```

## Meta Commands

```ls
metric m:in_office p:integer l:In-Office t:dataTypeName=number

entity e:gkek-wbij l:"Organizational Reports For Hawaii State and County Candidates" t:attribution="State of Hawaii; Campaign Spending Commission" t:url=https://data.hawaii.gov/api/views/gkek-wbij

property e:gkek-wbij t:meta.view v:id=gkek-wbij v:category=Community v:attributionLink=http://www.hawaii.gov/campaign v:averageRating=0 v:name="Organizational Reports For Hawaii State and County Candidates" v:attribution="State of Hawaii; Campaign Spending Commission"

property e:gkek-wbij t:meta.view.owner v:id=g6c2-gabj v:profileImageUrlMedium=/api/users/g6c2-gabj/profile_images/THUMB v:profileImageUrlLarge=/api/users/g6c2-gabj/profile_images/LARGE v:screenName="Hawaii Campaign Spending Commission" v:profileImageUrlSmall=/api/users/g6c2-gabj/profile_images/TINY v:displayName="Hawaii Campaign Spending Commission"

property e:gkek-wbij t:meta.view.tableauthor v:id=g6c2-gabj v:profileImageUrlMedium=/api/users/g6c2-gabj/profile_images/THUMB v:profileImageUrlLarge=/api/users/g6c2-gabj/profile_images/LARGE v:screenName="Hawaii Campaign Spending Commission" v:profileImageUrlSmall=/api/users/g6c2-gabj/profile_images/TINY v:roleName=editor v:displayName="Hawaii Campaign Spending Commission"
```

## Top Records

```ls
| reg_no  | candidate_name        | candidate_committee_name  | address_1                       | address_2 | city       | state | zip_code | business_phone | chairperson_name    | chair_address_1             | chair_address_2 | chair_city | chair_state | chair_zip_code | chair_business_phone | treasurer_name       | treasurer_address_1            | treasurer_address_2 | treasurer_city | treasurer_state | treasurer_zip_code | treasurer_business_phone | office         | district | county | party        | terminated | in_office | filing_date         | 
| ======= | ===================== | ========================= | =============================== | ========= | ========== | ===== | ======== | ============== | =================== | =========================== | =============== | ========== | =========== | ============== | ==================== | ==================== | ============================== | =================== | ============== | =============== | ================== | ======================== | ============== | ======== | ====== | ============ | ========== | ========= | =================== | 
| CC11028 | Abbett, Richard       | Friends of Richard Abbett | PO BOX 6201                     |           | Ocean View | HI    | 96737    | 8083336241     | Miller, Jendayi T.  | PO BOX 576                  |                 | Naalehu    | HI          | 96772          | 8083339392           | Martin, Robert M.    | PO BOX 1126                    |                     | Naalehu        | HI              | 96772              | 8084431596               | Hawaii Council | 6        | Hawaii | Non-Partisan | Y          | 0         | 2014-03-21T13:21:35 | 
| CC11314 | Abbett, Richard       | Richard Abbett for House  | 551 Kailana St                  |           | Wailuku    | HI    | 96793    | 808-268-3422   | Eno, Jason          | PO Box 81560                |                 | Haiku      | HI          | 96708          | 808-268-3422         | Eno, Jason           | PO Box 81560                   |                     | Haiku          | HI              | 96708              | 808-268-3422             | House          | 8        |        | Democrat     | N          | 0         | 2016-06-15T01:42:40 | 
| CC10496 | Abe, Michael          | Mike Abe for State House  | 3566 Harding Avenue Rm 204D     |           | Honolulu   | HI    | 96816    | 7346603        | Abe, Michael K.     | 3556 Maunaloa Avenue        |                 | Honolulu   | HI          | 96816          | 7346603              | Abe, Michael K.      | 3556 Maunaloa Avenu            |                     | Honolulu       | HI              | 96816              | 7346603                  | House          | 19       |        | Democrat     | Y          | 0         | 2008-08-05T15:04:11 | 
| CC10529 | Abercrombie, Neil     | Abercrombie for Governor  | c/o 81 S. Hotel Street, Ste 300 |           | Honolulu   | HI    | 96813    | 808-522-8833   | Kaneko, William     | c/o 81 S. Hotel Street      | Ste 300         | Honolulu   | HI          | 96813          | 808-522-8833         | Endo, Jack Y.        | 81 South Hotel Street, Ste 300 |                     | Honolulu       | HI              | 96813              | 808-522-8833             | Governor       |          |        | Democrat     | N          | 1         | 2009-03-09T11:00:44 | 
| CC10211 | Abinsay, Felipe (Jun) | Friends of Jun Abinsay    | 1260 Richard Lane #B516         |           | Honolulu   | HI    | 96819    | 8084288684     | Manegdeg, Jake      | 3215 Ala Ilima Street, #502 |                 | Honolulu   | HI          | 96818          | 8082515249           | Sabino, Christine B. | 85-577 Momona Place            |                     | Waianae        | HI              | 96792              | 8084295360               | House          | 29       |        | Democrat     | Y          | 0         | 2007-01-19T09:36:47 | 
| CC10757 | Able, Johnathan       | Johnathan Able            | box 181                         |           | kealakekua | HI    | 96750    | na             | Able, Johnathan     | box181                      |                 | kealakekua | HI          | 96750          | 8089365434           | Able, Johnathan      | box181                         |                     | kealakekua     | HI              | 96750              | na                       | House          | 5        |        | Non-Partisan | Y          | 0         | 2011-02-02T07:57:46 | 
| CC10314 | Agor, Ron             | Friends of Ron Agor       | 4374 Kukui Grove                | #204      | Lihue      | HI    | 96766    | 808-245-4550   | Agor, Ronald        | 4374 Kukui Grove            | #204            | Lihue      | HI          | 96766          | 808-245-4550         | Murray, Michael J.   | 4437 Anonui St                 |                     | Lihue          | HI              | 96766              | 808-639-8098             | Kauai Council  | 15       |        | Republican   | Y          | 0         | 2007-07-02T17:09:53 | 
| CC10499 | Agor, Ron             | Friends of Ron Agor       | 4028 Rice Street                | Suite C   | Lihue      | HI    | 96766    | 245-6883       | Lucas, Jon T.       | 4028 Rice Street            | Suite C         | Lihue      | HI          | 96766          | 245-5877             | Raco, Alicia         | 4028 Rice Street               | Suite C             | Lihue          | HI              | 96766              | 245-4550                 | Kauai Council  | Kauai    | Kauai  | Non-Partisan | Y          | 0         | 2008-07-30T11:21:12 | 
| CC11062 | Agustin, Jaci         | Friends of Jaci Agustin   | 98-252 Hekaha St                |           | Aiea       | HI    | 96701    | 808-295-3057   | James, Jack         | 350 Ward Ave #106           |                 | Honolulu   | HI          | 96814          | 808-386-8608         | Santiago, Monisha G. | 98-382 Kaonohi St #2           |                     | Aiea           | HI              | 96701              | 808-348-6436             | House          | 34       |        | Republican   | N          | 0         | 2014-04-11T20:15:31 | 
| CC11099 | Ahu Isa, Lei          | Friends of Lei Ahu Isa    | P.O. Box 22539                  |           | Honolulu   | HI    | 96823    | 808-537-4880   | Keaulii, Raylene I. | 217 Prospect Street         | #F4             | Honolulu   | HI          | 96813          | 808-537-4880         | Isa, Roderick K.     | 1255 Nuuanu Avenue             | #2207               | Honolulu       | HI              | 96813              | 808-573-4880             | OHA            | At-Large |        | Non-Partisan | Y          | 0         | 2014-05-30T15:00:19 | 
```