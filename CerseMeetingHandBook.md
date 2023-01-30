# CERSE Meeting Handbook

## Contents

* [Overview](#overview)
* [Infrastructure](#infrastructure)
* [Process](#process)
  * [Venue requirements](#venue-requirements)
  * [Before the event](#before-the-event) 
  * [Lead up to the event](#lead-up-to-the-event)
  * [After the event](#after-the-event)
  * [Timeline](#timeline)

  
## Overview

This is an evolving document - if you have something to add or change please contribute.

This document offers guidance on how to orgonise a Community of *Edinburgh Research Software Engineers* (CERSE) meeting. We believe that these meetings should be inclusive and available to all. We have adopted the Carpentries [Code of Conduct](https://docs.carpentries.org/topic_folders/policies/code-of-conduct.html), please make yourself familiar with this and inform participants at the meeting that they should observe this.

## Infrastructure

We have set up some infrastructure to help organise such meetings:

* [CERSE GitHub Organisational account](https://github.com/cerse/) - to join this organisation send your GitHub id to [mario](mailto:mario@epcc.ed.ac.uk?subject=Add me to the CERSE GitHub org.) or one of the other admins.
* [Twitter account](https://twitter.com/cerse7) - as a means to publicise such events or to learn of them.
* [JISC mailing list](https://www.jiscmail.ac.uk/cgi-bin/webadmin?A0=ED-RSE-COMMUNITY) - a growing list of members you can publicise the meeting to.
* Slack channel - you will have to join the [UK RSE](https://docs.google.com/forms/d/e/1FAIpQLSc9LqOWGwA1xDvSgy81eimcb9s0cNBFso0zv0_HoZz16G1M5w/viewform?c=0&w=1) slack and then join the `#edinburgh` channel.

We have made these institution independent so as to be available to all interested parties in Edinburgh.

## Process

### Venue requirements

First task is to have a good venue. A good venue should have where possible:

* Capacity usually for up to around 50 people (registrations vary depending on time, day and location where the meeting will take place and advertising).
* *Research Software Engineers* (RSEs) tend to carry laptops around so it would be nice to try to have an adequate number of power sockets and/or power extensions available.
* Have sufficient space or adjoining areas where break-out groups, if you are going to have any, so they can interact without affecting other breakout groups.
* Have a projector at the front with a screen or other equipment that allows content to be projected.
* Have amplification/induction loops.
* Be wheelchair accessible.

The venue should be available for around two hours - this has been the typical duration for the meetings up to this point.

### Before the event

This starts from the premise that a suitable venue has been booked for this event.

Before you can do anything get yourself added to the GitHub CERSE Organisational. We are assuming that you are going to be coordinating a future CERSE meeting in Edinburgh. We use [GitHub.io pages](https://pages.github.com/) to publicise meetings and log outcomes so it is important that you have a GitHub id with sufficient privileges within the CERSE Organisation to be able to do this.

1. Create a repository with a name that uses the `yyyy-mm-dd-venue` pattern for your meeting. Make sure you create under the `cerse` organiation and that it is a `Public` repository.
2. Go into your repository and click on `Settings` (Gear icon). 
  * Choose the `Pages` menu item on the left-hand menu.
  * Change the `Source` to `main branch` (your io pages will be generated from your [markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) pages in the repo starting from a `Readme.md` file).
  * When you make this change GitHub will inform you where your GitHub io pages are published. It will follow the pattern: `https://cerse.github.io/YourRepoName`. Take a copy of your io pages URL.
  * For the `Theme Chooser` below this, click on the `Change Theme`. Changed to use the Cayman theme as that gives a better accessibility score - we have previously been using the `Midnight theme`. If you think there is a better one for your event use that instead.
  * Go back to your repo page.
3. Click on the `Edit` button to modify the message `No description, website, or topics provided.`. If you do not see this button ask for your privileges to be increased. Add a short description for your event but more importantly add the GitHub io pages URL for your website. 
4. Create a `Readme.md` file. Populate with the contents of a previous event. Begin to edit with the corresponding content for your event.
5. Go to the [cerse.github.io](https://github.com/cerse/cerse.github.io) repository which contains the `main` pages for the organisation. Add your event, in reverse chronological order, to the list of existing events. Make sure you point to the GitHub io pages and not the repository. 
6. It can be useful to set-up a registration process to know how many people are coming to the event (especially if catering is being provided) and to generate an attendee list. For this you could use:
   * [Edinburgh University events booking](https://www.ed.ac.uk/information-services/computing/comms-and-collab/event-booking) - make sure that externals to Edinburgh University can register for the event.
   * [Eventbrite](https://www.eventbrite.co.uk/)

### Timetable for the day

The programme for the day will depend on how you want to shape the day. See the [template](Template.md) file you can use to seed your repository - you need to name this file `Readme.md` in your repository.

Typically we have used the following pattern:


|Time  | Activity      |
|------| ------|
|13:00 | Welcome  |
|13:05 | Presentation possibly from the venue volunteer |
|13:25 | Ice breaking session (opportunity to get to know your fellow attendees) or a group activity|
|13:45 | Lightning talks or discussion breakout groups |
|14:00 | An RSE focused presentation |
|14:30 | Coffee and biscuits |
|15:00 | Close |

where the times are flexible depending on the content. In more detail:

* The **Welcome** is probably something you should do unless you can find someone else to do it.
* It might be a good idea to let the person who volunteered the venue to give a **short presentation**.
* It is nice to have an **ice breaking session**. 
  * Get people to form into groups of roughly 5 to 6 people
  * Get them to join groups where they know the least number of people and then get them to introduce themselves to each other (about a minute per person). 
  * Give each group a topic to discuss for around 10 minutes. 
     * Get them to nominate someone to chair and another person who will be the scribe. Either give them a pertinent topic to discuss or get them to select from a list that you will have prepared when generating the table. 
     * At the end of the session get the chair person and/or the scribe to report the main salient points of their discussion. 
     * If at all possible get the scribe to send you a summary of the discussion after the event - do not rely on notes that may/may  not have been written up on the day. The main point of this session is to get people to get to know each other but some useful material may also be generated that would benefit from being recorded.
* **Lightning Talks** have proved to be of interest on the day but this requires people to volunteer this afore the meeting. We want these to be light for the speaker to write and for the audience to listen to. We have had a rule of only one slide and two minute per speaker (having a count down timer helps here). You will need people to register and express a desire to do a lightning talk on their research, a service, a cool tool, etc ... they can do more than one lightning talk but must be on different topics. Gather the slides BEFORE the meeting and put on one laptop. Ask for permission from the presenters if the slides can be made available from the web site after.
* An **RSE focused presentation** - this should be a presentation that would be of wide interest to the RSEs. 
* **Coffee and biscuits** this session gives you some spill over time if things have over run and you are running a bit late but in general people like to wind down with coffee and biscuits.

This is only an example timetable - please feel free to change so that it best fits your needs. Coming up with the timetable for the day can be one of the hardest things to sort out for your meeting. 

### Lead up to the event

Once you have a first draft complete version of the GitHub pages for your event and a registration page,if you are going to use one, it is time to advertise, advertise, advertise. Hopefully, you can get some advice on good channels from existing member to do this.

Some suggestions are:

* [The CERSE mailing list](https://www.jiscmail.ac.uk/cgi-bin/webadmin?A0=ED-RSE-COMMUNITY).
* [The CERSE twitter account](https://twitter.com/cerse7).
* Edinburgh University's [itforum](https://www.wiki.ed.ac.uk/display/itpfwiki/ITPF+Mailing+lists) internal mailing list for IT professionals at the University of Edinburgh.

Keep a log of where you publicise and when. You do not want to SPAM the same people too many times.

### On the day

For the day you will need:

* Signage and some non-damaging way to stick your signs if the room is difficult to find.
* A sign up sheet (with a pen) if you set up a registration process (good to know who actually turned up on the day and also those that did not register) so add a couple of extra blank rows for those that wish to sign up on the day. 

At the end of the meeting ask the audience if anyone would like to volunteer the next or a future venue. Give priority to venues that have not been used before or that are in separate geographical location in Edinburgh.

### After the event

Make sure that you have copies of any material that was presented and that you have permission from the content providers that it is ok to add their content online through your event repository. Note the names and email addresses of any scribes so you can get content from them afterwards.

### Timeline

At the third CERSE meeting it was thought that scheduling a bimonthly meeting would work best. This section attempts to give a suggested timeline on how to proceed. Assume an 8 week span between meetings which may be a bit optimisitic but you can compress (or expand) the suggestion to fit the time that is available to you. We start from an assumption that the venue for the next CERSE meeting is decided on, or soon after, one of these meetings.

* **week 0**: 
  * Have a room booked for the next meeting.
* **week 1**: 
  * First draft complete version of the timetable.
  * Have a registration process in place (if you are going to use one).
* **week 2**:
  * First round of advertising. Spam the mailing list, twitter, etc available to you.
* **weeks 3 and 4**:
  * More nuanced targeted advertising - send emails to individual people and get them in turn to spread the word. Keep a record of who you contacted and when.
* **week 5**:
  * Hit the mailing lists and other mass channels available to you publicising the meeting.
* **weeks 6 and 7**:
  * Continue with your targeted advertising.
  * Put an order for catering if you have a budget for this.
* **week 8 (final week)**:
  * One final mass mailing.
  * Have your meeting.    

The amount of advertising you have to do should be informed by the number of (or lack of) registrations you have already (another good reason why you should have a registration process). Expect about 30% of no shows on the day as well as some shows that did not register.
