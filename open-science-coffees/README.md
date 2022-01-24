# About open science coffees
A series of discussions around various open science-related topics.

This folder contains documentation on how to organise a coffee, and assets/notes from past coffees.

## 2021 Coffees ☕
- Sep 2021: Research Code Review: Best Practices, Challenges and Opportunities ([report and recording](https://osc-delft.github.io/posts/2021/09/03/Research-Code-Review/))
- Oct 2021: Diversity and Inclusion in Research, Technology and Design (together with the [TU Delft Diversity and Inclusion Office](https://www.tudelft.nl/en/about-tu-delft/strategy/diversity-inclusion); [report and recording](https://osc-delft.github.io/posts/2021/10/29/diversity-and-inclusion-in-research-technology-and-design/))
- Nov 2021: Open Data and Software in Tackling the Climate Crisis (together with the [TU Delft Climate Action](https://www.tudelft.nl/en/climate-action/about-us); [report and recording](https://osc-delft.github.io/posts/2021/11/24/open-data-and-software-in-tackling-the-climate-crisis/))

## How to organise Open Science Coffees?
A timeline.

### 6-8 weeks ahead
- **Identify an interesting topic for discussion.** This could be suggested by the community (you can, for example, ask the community via Slack/GitHub issues to suggest interesting topics), or a topic with a larger communication campaign at TU Delft (e.g. the October 2021 coffee on diversity & inclusion was organised as part of the TUD Diversity and Inclusion week).
- **Identify and reach out to partners** who may be interesting in co-organising the session - these could be communities within or outside of TUD.
  - They could help suggest and connect with panellists, communicate the event widely and/or co-facilitate the session.
- **Identify interesting panellists to invite.**
  - Think about diverse perspectives: backgrounds, organisations, race and gender.
  - Invite at least 1 panellists affiliated with TU Delft - this help raise the profile of our community members.
  - You can have more than 3 panellists, but our experience with 3 panellists for 60 mins is that it's just a good balance between giving everyone enough space to speak, and being able to showcase a variety of perspectives.
  - You can use this [invitation email template](template/panelist-invitation-email.md).
- **Set date, time and venue**:
  - You can choose to invite panellists first and ask for their availabilities over a range of dates, e.g. in the first week of October; this can increase the chances of panellists saying yes, but can also make your job as an organiser more difficult
  - Venue: online/on campus.
    - Online allows panellists and more people to more easily participate from around the country and the world. It's also logistically more easy to organise.
    - On campus allows more in-depth interactions. It's also easier for participants to connect with each other. Logistically, there are more moving parts.

*The plan documented here is mainly application for online discussions.*

### 4-5 weeks ahead
- **Confirm with all panellists**; ask them to confirm their job title and affiliation which you will use in the communication materials.
- **Set up the Zoom event**: Set up a registration page for the Zoom event: use the [OSCD logo](https://github.com/osc-delft/branding-and-resources/blob/main/logos/OSCD-logo-fullname.png) as the banner; include the following custom optional questions to help you understand your participants and engage them:
    - Organisation
    - How did you learn about this event? (Choices: Social media, Open Science Community Delft Newsletter, Other Newsletters, Community Platforms (e.g. Slack, MS Teams), Word of mouth/emails from colleagues, Other)
    - Any question(s) you would like to ask/discuss with our panellists and audience?
- **Design a social graphic that you can use to advertise the event**: see the [Branding-and-Resources-repo](https://github.com/osc-delft/branding-and-resources) for the raw file, and [this example](2021-10/OS%20Coffee%20Oct%202021-%20Twitter.png).
- **Set up a communications plan** - see [this template](https://github.com/osc-delft/ideas-and-plans/blob/main/open-science-coffees/templates/comms-plan-template.md) and [this past example](2021-09/comms-pack.md).
- **Start writing an open facilitators' notes document** - see [this template](https://github.com/osc-delft/ideas-and-plans/blob/main/open-science-coffees/templates/facilitators-notes.md) and [this past example](https://github.com/osc-delft/ideas-and-plans/blob/main/open-science-coffees/2021-09/facilitators-notes.md).

### 2-3 weeks ahead
- **Send panellists the list of important logistic information**; see [this template](templates/panelists-logistics-email.md).
- **Execute your communication plan**: ask partners and panellists to help where appropriate!

### 1-2 Days before
- **Send reminder emails to panellists**: you should include the time, date and zoom link of the event, and a link to the facilitators' notes, so that they can check it beforehand.
  - Please remember to put them in bcc.

### 1 Hour before
- Download all the registrants data from Zoom
- Send all registrants a reminder email - you can use [this template](\templates\1-hour-reminder-email.md)
  - Remember to put all registrants in bcc
- On the downloaded data, you should also check if there are any questions that registrants have suggested they'd like to discuss. You can already document them in the facilitators' notes and try to incorporate them in the discussion.

### During the session
- Hopefully all co-facilitators and panellists join 10mins ahead of the session for the tech check; ask them to unmute and test sound. Address any questions that they haven't responded to via email (e.g. recording permissions); or their names' pronunciations. It's also good to ensure that all co-facilitators and panellists can see the Facilitators' notes.
- If you choose to not set waiting rooms, then participants will trickle in gradually - welcome them!
- Start the call: remind everyone to turn off their cameras if they'd like to not appear with their faces on the recording BEFORE you start recording.
- Follow the Facilitators' notes: read the housekeeping rules, introduce the speakers.
- As the session goes and questions appear in the chat, the co-facilitator document them in the notes. Facilitator should choose to ask panellists to address them when they see fit.

### After the session
- Thank panellists individually through email/on the call!
- **Recording**: Download the recording from Zoom, and upload it to the community YouTube account
  - Video title: YYYYMMDD Title of the session
  - Video description: Include the abstract and panellists of the event
  - Publish with CC BY 4.0 license
- Write a short summary of the event
- Post it on the Stories page of the website with the recording embedded!
  - In the header section of the post, include `youtubeId:` followed by the ID of the YouTube video (the bit in the video URL after `https://www.youtube.com/watch?v=` )
  - In the place where you want the embedded video to be, put `{% include youtubePlayer.html id=page.youtubeId %}`
- Share a link with all registrants of the Coffee, using the [post-event email template](template/post-event-email.md).
