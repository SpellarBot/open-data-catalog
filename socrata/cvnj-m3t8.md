# Registered Retirement Facilities

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/licensed-continuing-care-retirement-communities) |
| Metadata | [Link](https://data.iowa.gov/api/views/cvnj-m3t8) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/cvnj-m3t8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/cvnj-m3t8/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | cvnj-m3t8 |
| Name | Registered Retirement Facilities |
| Attribution | Iowa Insurance Division |
| Category | Economy |
| Tags | continuing care, retirement communities |
| Created | 2015-07-02T19:40:50Z |
| Publication Date | 2015-08-06T14:46:03Z |

## Description

This dataset contains a listing of registered continuing care retirement communities in Iowa.

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type | Render Type |
| ======== | ============== | ================ | ================ | ========= | =========== |
| No       | time           | :updated_at      | updated_at       | meta_data | meta_data   |
| Yes      | numeric metric | tracking         | TRACKING         | number    | number      |
| Yes      | series tag     | company_name     | COMPANY NAME     | text      | text        |
| No       |                | mailing_address1 | MAILING ADDRESS1 | text      | text        |
| No       |                | mailing_address2 | MAILING ADDRESS2 | text      | text        |
| No       |                | mailing_address3 | MAILING ADDRESS3 | text      | text        |
| Yes      | series tag     | mailing_city     | MAILING CITY     | text      | text        |
| Yes      | series tag     | mailing_state    | MAILING STATE    | text      | text        |
| Yes      | series tag     | mailing_zip      | MAILING ZIP      | text      | number      |
| Yes      | series tag     | business_phone   | BUSINESS PHONE   | phone     | phone       |
| Yes      | series tag     | business_email   | BUSINESS EMAIL   | email     | email       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = mailing_address1,mailing_address2,mailing_address3
```

## Data Commands

```ls
series e:cvnj-m3t8 d:2015-07-03T04:31:24.000Z t:phone_number=712-722-4846 t:mailing_zip=51250 t:company_name="AMERICA'S CHOICE COMMUNITY OF SIOUX CENTER" t:business_email=lesw@ambankiowa.com t:mailing_state=IA t:mailing_city="SIOUX CENTER" m:tracking=126785

series e:cvnj-m3t8 d:2015-07-03T04:31:24.000Z t:phone_number=515-233-0383 t:mailing_zip=50010 t:company_name="AMES SENIOR LIVING" t:business_email=info@windsoroaksseniors.com t:mailing_state=IA t:mailing_city=AMES m:tracking=126808

series e:cvnj-m3t8 d:2015-07-03T04:31:24.000Z t:phone_number=515-838-3000 t:mailing_zip=50249 t:company_name="ATHENS WOODS ESTATES INC" t:business_email=kcarlson@agri-ed.com t:mailing_state=IA t:mailing_city=STRATFORD m:tracking=130297
```

## Meta Commands

```ls
metric m:tracking p:integer l:TRACKING t:dataTypeName=number

entity e:cvnj-m3t8 l:"Registered Retirement Facilities" t:attribution="Iowa Insurance Division" t:url=https://data.iowa.gov/api/views/cvnj-m3t8

property e:cvnj-m3t8 t:meta.view v:id=cvnj-m3t8 v:category=Economy v:averageRating=0 v:name="Registered Retirement Facilities" v:attribution="Iowa Insurance Division"

property e:cvnj-m3t8 t:meta.view.license v:name="Public Domain"

property e:cvnj-m3t8 t:meta.view.owner v:id=ym8t-nug5 v:profileImageUrlMedium=/api/users/ym8t-nug5/profile_images/THUMB v:profileImageUrlLarge=/api/users/ym8t-nug5/profile_images/LARGE v:screenName="Iowa Insurance Division (Commerce)" v:profileImageUrlSmall=/api/users/ym8t-nug5/profile_images/TINY v:displayName="Iowa Insurance Division (Commerce)"

property e:cvnj-m3t8 t:meta.view.tableauthor v:id=sg3p-k8mj v:profileImageUrlMedium=/api/users/sg3p-k8mj/profile_images/THUMB v:profileImageUrlLarge=/api/users/sg3p-k8mj/profile_images/LARGE v:screenName="Iowa Insurance Division (Commerce)" v:profileImageUrlSmall=/api/users/sg3p-k8mj/profile_images/TINY v:roleName=editor v:displayName="Iowa Insurance Division (Commerce)"
```

## Top Records

```ls
| :updated_at | tracking | company_name                               | mailing_address1       | mailing_address2 | mailing_address3 | mailing_city | mailing_state | mailing_zip | business_phone       | business_email               | 
| =========== | ======== | ========================================== | ====================== | ================ | ================ | ============ | ============= | =========== | ==================== | ============================ | 
| 1435897884  | 126785   | AMERICA'S CHOICE COMMUNITY OF SIOUX CENTER | 1900 SOUTH MAIN        |                  |                  | SIOUX CENTER | IA            | 51250       | [712-722-4846, null] | lesw@ambankiowa.com          | 
| 1435897884  | 126808   | AMES SENIOR LIVING                         | 1100 ADAMS STREET      |                  |                  | AMES         | IA            | 50010       | [515-233-0383, null] | info@windsoroaksseniors.com  | 
| 1435897884  | 130297   | ATHENS WOODS ESTATES INC                   | PO BOX 497             |                  |                  | STRATFORD    | IA            | 50249       | [515-838-3000, null] | kcarlson@agri-ed.com         | 
| 1435897884  | 126838   | AMERICA'S CHOICE COMMUNITY OF RED OAK      | 1300 SENATE AVENUE     |                  |                  | RED OAK      | IA            | 51566       | [712-623-9678, null] | haysacct@heartland.net       | 
| 1435897884  | 126782   | BARTELS LUTHERAN HOME                      | 1922 FIFTH AVENUE NW   |                  |                  | WAVERLY      | IA            | 50677       | [319-352-6104, null] | tbright@bartelscommunity.org | 
| 1435897884  | 128082   | Rose Vista/Rose Court                      | PO BOX 6               |                  |                  | Woodbine     | IA            | 51579       | [null, null]         | jsherer@sherermanagement.com | 
| 1435897884  | 128519   | Kahl Home for the Aged and Infirm          | 6701 JERSEY RIDGE RD   |                  |                  | DAVENPORT    | IA            | 52807       | [563-324-1621, null] | rachel@kahlhomedav.com       | 
| 1435897884  | 126831   | WESLEY RETIREMENT SERVICES INC             | 1200 BROOKRIDGE CIRCLE |                  |                  | ATLANTIC     | IA            | 50022       | [515-271-6896, null] | cshelangoski@wesleylife.org  | 
| 1435897884  | 126817   | BETHANY LIFE COMMUNITIES                   | 212 LAFAYETTE AVENUE   |                  |                  | STORY CITY   | IA            | 50248       | [515-733-4325, null] | alaine@bethanylife.org       | 
| 1435897884  | 128027   | KEOKUK VILLAGE DRIVE LLC                   | 285 S FARNHAM ST       |                  |                  | GALESBURG    | IL            | 61401       | [319-524-5772, null] | rjwilson@rfmsinc.com         | 
```