# Bills That Passed 2013 Legislature

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/bills-that-passed-2013-legislature-bc151) |
| Metadata | [Link](https://data.hawaii.gov/api/views/pkba-543m) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/pkba-543m/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/pkba-543m/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | pkba-543m |
| Name | Bills That Passed 2013 Legislature |
| Attribution | Hawaii State Legislature |
| Category | Government-Wide Support |
| Tags | 2013 bills, legislature |
| Created | 2013-05-08T19:49:17Z |
| Publication Date | 2013-05-08T19:53:36Z |
| Rows Updated | 2013-05-08T19:49:26Z |

## Description

Bills that Passed the 2013 Legislature

## Columns

```ls
| Included | Schema Type | Field Name       | Name             | Data Type | Render Type |
| ======== | =========== | ================ | ================ | ========= | =========== |
| Yes      | series tag  | bill             | Bill             | text      | text        |
| Yes      | series tag  | subject          | Subject          | text      | text        |
| Yes      | series tag  | appropriation    | Appropriation    | text      | text        |
| Yes      | series tag  | title            | Title            | text      | text        |
| Yes      | series tag  | abstract         | Abstract         | html      | html        |
| Yes      | series tag  | status           | Status           | text      | text        |
| Yes      | series tag  | introducer_s     | Introducer(s)    | text      | text        |
| Yes      | series tag  | current_referral | Current Referral | text      | text        |
| Yes      | series tag  | companion        | Companion        | url       | url         |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Data Commands

```ls
series e:pkba-543m d:2013-01-01T00:00:00.000Z t:abstract="Deletes the &quot;one gallon per person per day&quot; exception to the prohibition against the removal of sand and other beach or marine deposits, except for materials inadvertently taken, and creates an exemption for public emergencies and traditional cultural practices. Ensures public lateral access along the shoreline by making permanent the requirement that landowners remove human-induced, enhanced, or unmaintained vegetation interfering with such access and maintaining DLNR's enforcement duty to maintain such access. Clarifies that Act 160, SLH 2010 does not alter or modify any agreement of the DLNR existing or executed on the effective date of Act 160. Effective 06/29/13. (SD2)" t:title="RELATING TO COASTAL AREAS." t:current_referral="WTL, JDL" t:bill="HB17 HD1 SD2" t:status="H 5/7/2013: Transmitted to Governor." t:introducer_s="EVANS, COFFMAN, HANOHANO, KAWAKAMI, C. LEE, LOWEN, NISHIMOTO, TAKUMI, THIELEN" t:subject="Coastal Areas; Public Access" m:row_number.pkba-543m=1

series e:pkba-543m d:2013-01-01T00:00:00.000Z t:abstract="Permits the board of directors of a condominium association to collect a six-month special assessment from the mortgagee or other purchaser of a unit with a recorded lien for delinquent common assessments. Specifies how excess rental income received by a condominium association shall be paid to existing lien holders. (CD1)" t:title="RELATING TO CONDOMINIUMS." t:current_referral="CPN, JDL" t:bill="HB21 HD2 SD2 CD1" t:status="H 5/6/2013: Transmitted to Governor." t:introducer_s=EVANS t:subject="Condominiums; Condominium Associations; Common Assessments; Liens" m:row_number.pkba-543m=2

series e:pkba-543m d:2013-01-01T00:00:00.000Z t:abstract="Allows a condominium association, as a junior lienholder, to commence or continue a nonjudicial foreclosure action on a property subject to a judicial foreclosure even if the lender has filed for foreclosure. Preserves the right of owner-occupants to require the foreclosing mortgagee to participate in the dispute resolution process in situations where an association forecloses on residential real property occupied by one or more owner-occupant mortgagors for whom the unit is and has been the person's primary residence for a continuous period of not less than two hundred days immediately preceding the date on which the notice is served and the mortgagee subsequently forecloses its lien on the same property. Effective July 1, 2013. (HB25 CD1)" t:title="RELATING TO SUSPENSION OF FORECLOSURE ACTIONS BY JUNIOR LIENHOLDERS." t:current_referral="CPN, JDL" t:bill="HB25 HD2 SD2 CD1" t:status="H 5/7/2013: Transmitted to Governor." t:introducer_s=EVANS t:subject="Foreclosure Actions; Junior Lienholders; Condominium Associations" m:row_number.pkba-543m=3
```

## Meta Commands

```ls
metric m:row_number.pkba-543m p:long l:"Row Number"

entity e:pkba-543m l:"Bills That Passed 2013 Legislature" t:attribution="Hawaii State Legislature" t:url=https://data.hawaii.gov/api/views/pkba-543m

property e:pkba-543m t:meta.view v:id=pkba-543m v:category="Government-Wide Support" v:attributionLink=http://capitol.hawaii.gov v:averageRating=0 v:name="Bills That Passed 2013 Legislature" v:attribution="Hawaii State Legislature"

property e:pkba-543m t:meta.view.license v:name="Public Domain"

property e:pkba-543m t:meta.view.owner v:id=tz3q-nbms v:profileImageUrlMedium=/api/users/tz3q-nbms/profile_images/THUMB v:profileImageUrlLarge=/api/users/tz3q-nbms/profile_images/LARGE v:screenName="Russell Castagnaro" v:profileImageUrlSmall=/api/users/tz3q-nbms/profile_images/TINY v:displayName="Russell Castagnaro"

property e:pkba-543m t:meta.view.tableauthor v:id=tz3q-nbms v:profileImageUrlMedium=/api/users/tz3q-nbms/profile_images/THUMB v:profileImageUrlLarge=/api/users/tz3q-nbms/profile_images/LARGE v:screenName="Russell Castagnaro" v:profileImageUrlSmall=/api/users/tz3q-nbms/profile_images/TINY v:roleName=publisher v:displayName="Russell Castagnaro"
```