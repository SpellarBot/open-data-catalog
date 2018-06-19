# OHLA Board Members

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ohla-board-members-d3aff) |
| Metadata | [Link](https://data.oregon.gov/api/views/x7pc-5mrn) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/x7pc-5mrn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/x7pc-5mrn/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | x7pc-5mrn |
| Name | OHLA Board Members |
| Attribution | Oregon Health Licensing Agency. |
| Category | Administrative |
| Created | 2013-11-26T22:39:07Z |
| Publication Date | 2016-02-22T22:09:54Z |

## Description

Members of citizen boards managed by the Oregon Health Licensing Agency.

## Columns

```ls
| Included | Schema Type | Field Name        | Name              | Data Type     | Render Type   |
| ======== | =========== | ================= | ================= | ============= | ============= |
| Yes      | series tag  | board_council     | Board/Council     | text          | text          |
| Yes      | series tag  | member_type       | Member Type       | text          | text          |
| Yes      | series tag  | member_first_name | Member First Name | text          | text          |
| Yes      | series tag  | member_last_name  | Member Last Name  | text          | text          |
| Yes      | series tag  | chair_vice_chair  | Chair/Vice Chair  | text          | text          |
| Yes      | series tag  | photo             | Photo             | photo         | photo         |
| Yes      | series tag  | bio               | Bio               | html          | html          |
| Yes      | time        | start_of_term     | Start of Term     | calendar_date | calendar_date |
| No       |             | term_expiration   | Term Expires      | calendar_date | calendar_date |
| Yes      | series tag  | recruiting        | Recruiting        | url           | url           |
| Yes      | series tag  | term              | Term              | text          | text          |
```

## Time Field

```ls
Value = start_of_term
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = term_expiration
```

## Data Commands

```ls
series e:x7pc-5mrn d:2014-03-01T00:00:00.000Z t:bio="<p>Ms. Blackman has worked in the hearing aid business for 16 years. She is the manager of Costco Hearing Aid Center, in Albany and has been a licensed hearing aid specialist for the last 11 years. Ms Blackman has been a member of the Oregon Hearing Society (OHS) and the International Hearing Society for the last 10 years. She currently serves as the president of the OHS board. She expresses a sincere interest in serving the public by ensuring best practices are met for testing hearing and fitting hearing aids.</p>
<p>&nbsp;</p>" t:member_last_name=Blackman t:member_type="Hearing Aid Specialist" t:term="1st Full" t:member_first_name=Cheryl t:photo=1BW0Zn-zdEYwEpnM4RwhPNLnzbHUIghQtldYQKHhbPo t:board_council="Advisory Council on Hearing Aids" m:row_number.x7pc-5mrn=1

series e:x7pc-5mrn d:2014-03-01T00:00:00.000Z t:bio="<p>Mr. Hvass is a licensed denturist working with Natural Dentures, in Eugene, Oregon. He has served as a board member, president, and vice president of the Oregon State Denturist Association.</p>" t:member_last_name=Hvass t:member_type=Denturist t:term="1st Full" t:member_first_name=Nels t:photo=L2wQp652EPiDBsQwGof3FcGwlWQ85fkXDQiYjXErDiM t:board_council="Board of Denture Technology" m:row_number.x7pc-5mrn=2

series e:x7pc-5mrn d:2011-01-01T00:00:00.000Z t:bio="Mr. Nelson Lomax has worked as a mortgage broker for Professional Mortgage Corporation since 1999 and previously was an independent contractor/owner for RPS/FedEX Ground in Salem. Mr. Lomax was a student athlete at Chemeketa Community College and Willamette University, where he graduated with a Bachelor's of Arts degree in Speech Communications in 1995. He has worked at basketball camps and clinics and as a referee at The Hoop athletic facility in Salem. Mr. Lomax also has served as Willamette University's assistant men's basketball coach under Gordie James for the past nine years and coached for youth organizations such as the Boys &amp; Girls Clubs and Pop Warner. &quot;I thoroughly enjoy the athletic environment and feel that I can offer valuable input gained from my experience,&quot; says Mr. Lomax." t:member_last_name=Lomax t:member_type="Public Member" t:term="1st Full" t:member_first_name=Nelson t:photo=Iz8mGfoVCmxdzvFCSCrSsuoipLxjIYqJKvqoBGn4chA t:board_council="Board of Athletic Trainers" m:row_number.x7pc-5mrn=3
```

## Meta Commands

```ls
metric m:row_number.x7pc-5mrn p:long l:"Row Number"

entity e:x7pc-5mrn l:"OHLA Board Members" t:attribution="Oregon Health Licensing Agency." t:url=https://data.oregon.gov/api/views/x7pc-5mrn

property e:x7pc-5mrn t:meta.view v:id=x7pc-5mrn v:category=Administrative v:attributionLink=http://oregon.gov/OHLA v:averageRating=0 v:name="OHLA Board Members" v:attribution="Oregon Health Licensing Agency."

property e:x7pc-5mrn t:meta.view.owner v:id=hfyt-zc65 v:screenName="Katherine Leamaster" v:displayName="Katherine Leamaster"

property e:x7pc-5mrn t:meta.view.tableauthor v:id=hfyt-zc65 v:screenName="Katherine Leamaster" v:displayName="Katherine Leamaster"
```

## Top Records

```ls
| board_council                                                           | member_type             | member_first_name | member_last_name | chair_vice_chair | photo                                       | bio                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | start_of_term       | term_expiration     | recruiting                                                                         | term     | 
| ======================================================================= | ======================= | ================= | ================ | ================ | =========================================== | ===================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================== | =================== | =================== | ================================================================================== | ======== | 
| Advisory Council on Hearing Aids                                        | Hearing Aid Specialist  | Cheryl            | Blackman         |                  | 1BW0Zn-zdEYwEpnM4RwhPNLnzbHUIghQtldYQKHhbPo | Ms. Blackman has worked in the hearing aid business for 16 years. She is the manager of Costco Hearing Aid Center, in Albany and has been a licensed hearing aid specialist for the last 11 years. Ms Blackman has been a member of the Oregon Hearing Society (OHS) and the International Hearing Society for the last 10 years. She currently serves as the president of the OHS board. She expresses a sincere interest in serving the public by ensuring best practices are met for testing hearing and fitting hearing aids.
                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    | 2014-03-01T00:00:00 | 2018-02-28T00:00:00 | [null, null]                                                                       | 1st Full | 
| Board of Denture Technology                                             | Denturist               | Nels              | Hvass            |                  | L2wQp652EPiDBsQwGof3FcGwlWQ85fkXDQiYjXErDiM | Mr. Hvass is a licensed denturist working with Natural Dentures, in Eugene, Oregon. He has served as a board member, president, and vice president of the Oregon State Denturist Association.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         | 2014-03-01T00:00:00 | 2017-02-28T00:00:00 | [null, null]                                                                       | 1st Full | 
| Board of Athletic Trainers                                              | Public Member           | Nelson            | Lomax            |                  | Iz8mGfoVCmxdzvFCSCrSsuoipLxjIYqJKvqoBGn4chA | Mr. Nelson Lomax has worked as a mortgage broker for Professional Mortgage Corporation since 1999 and previously was an independent contractor/owner for RPS/FedEX Ground in Salem. Mr. Lomax was a student athlete at Chemeketa Community College and Willamette University, where he graduated with a Bachelor's of Arts degree in Speech Communications in 1995. He has worked at basketball camps and clinics and as a referee at The Hoop athletic facility in Salem. Mr. Lomax also has served as Willamette University's assistant men's basketball coach under Gordie James for the past nine years and coached for youth organizations such as the Boys & Girls Clubs and Pop Warner. "I thoroughly enjoy the athletic environment and feel that I can offer valuable input gained from my experience," says Mr. Lomax.                                                                                                                                                                                                                                                                                      | 2011-01-01T00:00:00 | 2014-12-31T00:00:00 | [null, null]                                                                       | 1st Full | 
| Board of Direct Entry Midwifery                                         | Licensed Direct Midwife | Colleen           | Forbes           |                  | wMOsA_2jWpq2Nc8L3cpZIeMYp3uy7z2Rth3LBliX7E0 | Colleen Forbes has been sole proprietor and a licensed midwife of Midwifery Care, a homebirth practice, since 2001. Ms. Forbes served as President of the Oregon Midwifery Council in 2007-2008, and Advocacy Council/Regional Representative of the council from 2003-2007. Previously she was Clinic Supervisor at All Women?s Health Services in Eugene, Oregon; Director, Federation of Feminist Women?s Health Centers; and a volunteer in Honduras, Central America, for the United State Peace Corps. Ms. Forbes graduated from the University of Massachusetts, Amherst, with a Bachelor?s of Arts in Psychology. ?It is my firm belief that much of the safety of homebirth relies on a mutual respect and collaboration between midwives and physicians,? she says.                                                                                                                                                                                                                                                                                                                                         | 2013-03-15T00:00:00 | 2016-03-14T00:00:00 | [null, null]                                                                       | 1st Full | 
| Board of Direct Entry Midwifery                                         | Licensed Direct Midwife | Kelli             | McIntosh         |                  | syUEs2Mv2X28C-j0IWtU7qLDbNCfNmBkP2_Xn1z99hI | Kelli McIntosh works with Full Bloom Midwifery in Milwaukie, Oregon. She completed her B.S. degree at Birthingway College of Midwifery, in Portland. Ms. McIntosh looks forward to being involved in creation of policies that provide safe and positive outcomes for families. In addition to her work as a midwife, she volunteers with many organizations including the Planning Committee for the National MANA Conference, her church, and CASA (Court Appointed Special Advocate).                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              | 2013-11-22T00:00:00 | 2016-06-30T00:00:00 | [null, null]                                                                       | 1st Full | 
| Board of Direct Entry Midwifery                                         | Licensed Direct Midwife | Stephanie         | Elliott          |                  | yZAahi_pKIGQvadh-C-saJXvaQzkF3LoyoW727HZXTQ | Stephanie Elliott is a licensed direct entry midwife who has attended home and birth-center births at Alma Birth Center in Portland. She was raised in Ontario, Canada, and is inspired by the integration of midwifery into the Ontario health-care system in the last 10 years. Elliott thinks that access to safe and regulated midwifery care will reduce health-care costs, improve outcomes for women and babies and create healthy empowered foundations for new families. Stephanie coordinates Alma?s clinical training program and is a member of Oregon Midwifery Council.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 | 2014-09-19T00:00:00 | 2017-09-18T00:00:00 | [null, null]                                                                       | 1st Full | 
| Board of Cosmetology                                                    | Practitioner            | Franklin          | Whatley          |                  | 1v8JFLGR2ErYN1l5pk0eUBC6MIBvF0iLyHVDBA9h6NI | Franklin Whatley is a barber and educator who founded Mirror Vision, a new and innovative/interactive way of learning the art of clipper cutting, and who has been a barber at former NBA star Terrell Brandon?s barber shop since 2004. Mr. Whatley also was an instructor at Beaumonde from 2010 to 2012. Previously he was a barber at Will?s Barber Shop in Cleveland, OH, where he also received his barbering certificate from Lake Erie Barber College.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        | 2012-11-21T00:00:00 | 2016-11-20T00:00:00 | [null, null]                                                                       | 1st Full | 
| Respiratory Therapist and Polysomnographic Technologist Licensing Board | Public Member           | VACANT            |                  |                  | 5KOUcPYoNQmsEfkKEM-QXQnmtV95YSP0RIOGMqzhr0g |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |                     |                     | [http://www.oregon.gov/gov/admin/Pages/How_To_Apply.aspx, Apply for this position] |          | 
| Sex Offender Treatment Board                                            | Victim's Advocacy       | Michele           | Roland-Schwartz  |                  | cLpVU-DXwYctranUqNvnBqV1uxokBTC-pCIZY0o8QXw | Michele Roland-Schwartz is the executive director of the Oregon Attorney General?s Sexual Assault Task Force and former director of the Southern Arizona Center Against Sexual Assault Services in Tucson, Arizona. She has more than 10 years of experience as an advocate for survivors of sexual violence in Oregon, Tennessee and Arizona, and led the Sexual Assault Response Team in Southern Arizona. Michele earned her bachelor?s degree at the University of Oregon where she began her work to end violence against women, and her master?s degree at Oregon State University. She has worked with mental health providers, Sexual Assault Nurse Examiners and affiliated medical providers, law enforcement, the criminal justice system and sexual violence prevention educators. Michele is the staff liaison for the Legislative and Public Policy and the Offender Management Subcommittees of the Task Force, two of eight subcommittees that make up Oregon?s statewide representation on the task force.                                                                                           | 2014-04-01T00:00:00 | 2018-03-31T00:00:00 | [null, null]                                                                       | 1st Full | 
| Environmental Health Registration Board                                 | Physician               | Jonathan          | Schott           |                  | K6vfA1UcDKCq5Ir24CjTHeJuc9FD9KJVRK9GDFdOxsA | Dr. Jonathan Schott is Medical Director at Pine Eagle Clinic, Baker County Health Department, St. Luke?s Eastern Oregon Medical Associates, and Baker County Child Abuse Center, and is Rural Medical Director for St. Luke?s Health System. He was in private practice from 1999-2010. He has been a member of St. Luke?s Health System Clinical Leadership Council since 2011 and St. Luke?s Health System Diabetes Initiative Physician Lead since 2012.He obtained his medical degree from Oregon Health Sciences University School of Medicine and served a Family Practice residency at Idaho State University after obtaining a Bachelor?s of Science in Biology from Oregon State University. 
  ?With health care reform nationally and on the state level, how medical care is delivered is going to change not only in the public sector, but also in the public sector,? Dr. Schott says. ?Those changes and partnerships occur through relationship building and focused effort. I?m honored to be a part of the process by which that change occurs as it relates to public health at the state level.? | 2013-06-01T00:00:00 | 2017-05-31T00:00:00 | [null, null]                                                                       | 1st Full | 
```