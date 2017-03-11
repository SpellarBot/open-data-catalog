# Multi-Family Housing FY 2011-2016

## Dataset

* [Dataset URL](https://data.maryland.gov/api/views/cadm-spqd/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/multi-family-housing-fy-2011-2015)
* [Metadata URL](https://data.maryland.gov/api/views/cadm-spqd)
* Id = cadm-spqd
* Name = Multi-Family Housing FY 2011-2016
* Attribution = Department of Housing & Community Development
* [Attribution Link](http://dhcd.maryland.gov/HousingDevelopment/Pages/default.aspx)
* Tags = [dhcd, department of housing & community development, multi-family housing, cda]
* Created = 2016-07-01T15:26:31Z
* Publication Date = 2017-02-27T21:40:08Z
* Rows Updated = 2017-02-27T21:39:18Z

## Description

The Maryland Department of Housing and Community Development offers multifamily finance programs for the construction and rehabilitation of affordable rental housing units for low to moderate income families, senior citizens and individuals with disabilities.

Our multifamily bond programs issues tax-exempt and taxable revenue mortgage bonds to finance the acquisition, preservation and creation of affordable multifamily rental housing units in priority funding areas.

By advocating for increased production of rental housing units, we help create much-needed jobs and leverage opportunities to live, work and prosper for hardworking Maryland families, senior citizens, and individuals with disabilities throughout the state.?

DISCLAIMER: Some of the information may be tied to the Department?s bond funded loan programs and should not be relied upon in making an investment decision. The Department provides comprehensive quarterly and annual financial information and operating data regarding its bonds and bond funded loan programs, all of which is posted on the publicly-accessible Electronic Municipal Market Access system website (commonly known as EMMA) that is maintained by the Municipal Securities Rulemaking Board, and on the Department?s website under Investor Information. The links are: http://www.mdhousing.org/Website/Investor/Default.aspxhttp://emma.msrb.org/

## Columns

```ls
| Name            | Field Name      | Data Type | Render Type | Schema Type    | Included | 
| =============== | =============== | ========= | =========== | ============== | ======== | 
| updated_at      | :updated_at     | meta_data | meta_data   | time           | No       | 
| Project Name    | project_name    | text      | text        | series tag     | Yes      | 
| Project Address | project_address | text      | text        |                | No       | 
| Project City    | project_city    | text      | text        | series tag     | Yes      | 
| Project Zip     | project_zip     | text      | text        | series tag     | Yes      | 
| Project County  | project_county  | text      | text        | series tag     | Yes      | 
| Units           | units           | number    | number      | numeric metric | Yes      | 
| ProjectType     | projecttype     | text      | text        | series tag     | Yes      | 
| FY              | fy              | number    | text        |                | No       | 
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = fy,project_address
Annotation Fields = 
```

## Data Commands

```ls
series e:cadm-spqd d:2017-02-27T21:39:12.000Z t:project_name="Park View at Colonial Landing" t:project_county=Howard t:projecttype=Acq./Rehab. t:project_city=Elkridge t:project_zip=21075 m:units=100

series e:cadm-spqd d:2017-02-27T21:39:12.000Z t:project_name="Park View at Bladensburg" t:project_county="Prince George's" t:projecttype=Acq./Rehab. t:project_city=Bladensburg t:project_zip=20710 m:units=101

series e:cadm-spqd d:2017-02-27T21:39:12.000Z t:project_name="Burwood Gardens Phase I" t:project_county="Anne Arundel" t:projecttype=New t:project_city="Glen Burnie" t:project_zip=21061 m:units=100
```

## Meta Commands

```ls
metric m:units p:integer l:Units t:dataTypeName=number

entity e:cadm-spqd l:"Multi-Family Housing FY 2011-2016" t:attribution="Department of Housing & Community Development" t:url=https://data.maryland.gov/api/views/cadm-spqd

property e:cadm-spqd t:meta.view d:2017-03-07T16:48:21.088Z v:id=cadm-spqd v:attributionLink=http://dhcd.maryland.gov/HousingDevelopment/Pages/default.aspx v:averageRating=0 v:name="Multi-Family Housing FY 2011-2016" v:attribution="Department of Housing & Community Development"

property e:cadm-spqd t:meta.view.owner d:2017-03-07T16:48:21.088Z v:id=pugw-9r35 v:screenName=Jessica v:roleName=editor v:displayName=Jessica

property e:cadm-spqd t:meta.view.tableauthor d:2017-03-07T16:48:21.088Z v:id=pugw-9r35 v:screenName=Jessica v:roleName=editor v:displayName=Jessica
```