# Developer Notes
These are rough notes on what the application is aimed at, from the perspectve of user stories.

The overall aim is to create a website that will allow cub leaders to maintain their programmes.

The existing system is based on a Google spreadsheet.

# Tests
A comprehensive battery of tests is needed to ensure that
* All features work as designed.
* User access is limited to the details they are supposed to be able to see or edit. For example:
    * A parent can only see details of the young person/people they are identified as being responsible for (set up by either Group or Section admin).

## User Roles
This is an initial view of roles necessary.

Roles are
* Super Admin
    * Overall responsibility for running the site.
* Group Admin
    * Manages email registration for users within their section
    * Sets up access levels for group members
* Section
    * Sets up read/edit permissions for section planning
* Parent
    * This may not bedeveloped in the MVP
    * Can only view details for young people they are responsible for

## Login
* Users should be able to log into the site via a password.
* Users shall be able to request a new password via an email link.
* Users passwords shall be encrypted.

## Leader
As a user I want to be able to:
* See which nights I am planning (may be more than one leader planning the night)
* See summary of meeting nights
* See detail for meetings
* ? Mark register
    * This could be a _nice to have_ without being essential.
* Edit meeting night details, including
    * activities and approximate timings
    * tag badge work 

## Section Leader
As a section leader I want to be able to
* Do everything a Leader can do
* Assign planning for an event to one or more leaders
* Enable/disable leader access to the section
* ? Share a summary of a planned meeting to social media (eg a group Facebook page)
    * Must not include details of young people present

## Group Leader
As a group leader, I need to be able to:
* Set up section meeting nights
* Allocate section leaders to a section (there may be more than one of each type of section)
* Enable/Disable leader access to the group and sections
* See summary planning for sections
* See detail planning for sections
* Boast that they have the best ran group
* ? Enable Parent access to see their childs records (Data Protection Issue)
    * Possibly download as a PDF

## ? Parent
The parent role is possible, but not a key MVP item.  
As a parent, I need to see:
* Records pertaining to a young person that I am responsible for
* The planning summary for the meeting

## Sections
The main scouting sections are:
* Beavers
* Cubs
* Scouts
* Explorers
* Network

A leader may hold different roles within a goup.

## Meetings
Meetings can be either
* a regular scheduled meeting
* a meeting away from the hut
* an overnight/multi night camp

## Personal Data
To operate, the system needs user email addresses and a password for each user.

Passwords will be encrypted and resettable using the users email address.

If young person details are to be stored, then the following details.
* Name
* ? Gender
* Dates of meetings attended
* Badge work carried out
* Emergency contacts
* DOB

Name in order to identify on a register.

The DoB would be in order to help the group plan progression through sections.

Dates of meetings attended would allow a fire register to be viewed and identify which young people have completed work on badges.

Emergency contacts - although a leader in charge holds emergency contacts, there are occasions where they are not at a meeting.