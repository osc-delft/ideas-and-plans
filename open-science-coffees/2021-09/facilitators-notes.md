---
tags: os-coffee
---

# OS Coffee sep 2021 - facilitor notes

Wed Sep 1, 10-11 CEST

Registration link: https://tudelft.zoom.us/meeting/register/tJwtcOypqzwpHNZPRVlObq8dK_DIGy0yWLrs

## Warm up
1. Session will be recorded and uploaded to YouTube, please switch off camera if you'd not like to be on the recording
2. Welcome, and Emmy's intro (OSCD coordinator and facilitator of this session)
3. CoC reminders
    > put this link in chat: Full Code of Conduct: https://github.com/osc-delft/osc-delft.github.io/blob/master/CODE_OF_CONDUCT.md
4. Format of the event:
    - We are very grateful to have 3 panellists join us today! 
    - I will start the session off with some questions for our panellists
    - Afterwards, we will open the floor to all of your questions and comments! 
        - Please use the raise your hand button if you wish to ask a questions/comment, I will ask you to unmute yourself
        - You can also type your questions/comments in the Zoom chat. 

## Panellists introductions
- Anton Akhmerov: Associate Professor, Department of Quantum Nanoscience & Kavli Institute of Nanoscience, TU Delft
- Stephen Eglen: Professor of Computational Neuroscience at the University of Cambridge, and Co-Founder of CODECHECK
- Djura Smits: Research Software Engineer, Netherlands eScience Center 


## Questions
> I'll start with this order: Djura, Stephen and then Anton, and then will rotate the order every 2 questions or so.
1.	Please introduce yourselves briefly to everyone!
    > Briefly highlighting your experience working with research code will be really helpful here. 
2.	What does code review mean to you, and why do you think it is important in research?
4.	What is one memorable code review experience you’ve had in the past (either as a reviewer, or having your code reviewed)? 
    > it doesn’t have to be “formal” review processes – could be anything from reviewing code within your lab/group, or reviewing PRs in open-source projects
6.	(To Djura) I understand you’ve also worked in industry – what are the similarities & differences between how code review is done in software/tech teams in the industry, and your current experience working with RSEs and researchers at the eScience Center?
7.	What are the key challenges you have observed/experienced for research code reviewers & reviewees?
8.	What would you suggest reviewees and reviewers do to make the code review experience easier, more effective and more rewarding?
9.	(To Anton) You’ve been a strong advocate for submitting data and code with your publications for review, how are your experiences with that so far?
10.	(To Stephen) You’ve co-founded CODECHECK – could you elaborate on CODECHECK? What were your motivations for starting it, the work you’ve done so far, and what kind of impact you hope you can have on the academic publishing & reviewing culture?
11.	How can various stakeholders: institutional research support, funders, publishers, technology developers, etc, help encourage/facilitate more collaborative code development and code reviewing?

## Relevant links to put in chat
- https://codecheck.org.uk/
- 

## Open Q&A
- Please use the raise your hand button if you wish to ask a questions/comment, I will ask you to unmute yourself
- You can also type your questions/comments in the Zoom chat

Audience Qs:
- [x] Nurlan: Question for panelists: Do you think there is a difference between code review process best practices in the industry va academia? (Priorities, available time etc.)
- [x] Santosh: Any estimates on time involved in completing code review?
- [ ] I can already see code review as 2 opinions -- one is review geared toward publication (Stephen, does it work - let's automate this) vs let's review code together and improve/learn in the process
- [x] Lisa: Any tips or resources on writing code to make it easier for others to review
- [x] Santosh Q: @StephenEglen : Were there Research Software Engineers involved in the development/management of the code during or after the publication? The Github engineers who helped, what was their role?
- [x] Simon Cross Comment: There is also a different kind of code review that is missing in the academic process (which Stephen is hinting at now). Unreviewed code is like an unreviewed paper, or a pile of algebra which no one has checked. It is simply not part of science.
- [ ] Cyril: @stephen validity in code often comes with nit test / ground truth (@djura can probably comment on that) - with complex models for complex data, one can often not have a ground truth - isn't simply rerunning in a way a bit circular? (= not enough)
- [ ] Simon: For review it's not sufficient to take a pile of code and confirm that it can be run and reproduce results. One also needs to convince oneself that the code is "correct" if one wants to consider the results part of scientific knowledge (in much the same way that one would check a mathematical analysis or an experimental apparatus).
- [ ] Manuel: Q. Does research software development needs its own version of the Software Development Cycle? Any ideas/ comments?
- [ ] Jose: It might be also interesting to consider that code is constantly reviewed at different levels, and for different purposes (for instance inspecting a library that you want to rely on, or simply get feedback from an idea you are developing, or actually quality assessment for high end products). Perhaps code reviews can be more defined as formal reviews to comply with a set of standards set by the group or community.
- [ ] Crstina: Regarding what Anton said : Indeed sharing code raises problems of intellectual properties, at least in academia, where I worked, scientists often do not want to share their code, because that is part of what let them achieved their results sooner than others. So it's good to have centres that can review code and give some sort of "approval"
- [x] Esther: Announcement by Nature Human Behaviour about code reviewing: https://www.nature.com/articles/s41562-021-01190-w
- [x] Pirouz: Speaking of resources and incentives, what is wrong with post-publication review?
- [ ] Daniela: Shameless promotion: Join/Organize a Reprohack at your group/institute/uni ;-)
- [ ] Andres Felipe: What code review environment is recommended? One to one, one to many, many to many?
- [ ] Hugo: What is the role of documentation in code-review? I guess reviewers need some annotations to understand what's happening, but what would be the detail that is necessary (e.g. documentation per class, per function, or even line-by-line)? Should there be kind of a 'standard' like we have manuscript templates and guidelines?
- [ ] Jose: Q: Do you differentiate reusability and reproducibility checks(including documentation) from code quality checks(modularity, code structure)?
- [x] Cristina: @Djura: can you make some example of the ways how one can push for open source ?






## Outro
- Thank you! We'll share a short summary of this discussion and the recording on our website. So please let your friends who couldn't make this in real time know. We'll also send all registrant an email when this is ready!

- Our next coffee is on Diversity & Inclusion in research, technology & design. Many of us research and prototype solutions aiming to solve global issues from climate to health - however, we also increasingly see technology having unwarranted consequences, esp on marginalised groups of society. We see society losing trust in experts. Are our research, technology development and design processes truely open for all to participate and engage in? If not, how could we change this? Join us on Oct 6, 12:45-13:45 Amsterdam Time. 
    > "Diversity & Inclusion in research, technolgy  & design", Oct 6, 12:45-13:45. Register: https://tudelft.zoom.us/meeting/register/tJUtcOCsrj8qGtRXTxv86bSZKOe_EQ_D_5cF


- We'd love to have more of these informal open science discussion - if there're open science related topics that you'd like to learn more about or discuss with others, please feel free to suggest your ideas on our GitHub issue. 
    > Share your coffee ideas with us: https://github.com/osc-delft/ideas-and-plans/issues/7
- We'd also love to work with other communities/people in organising these sessions on topics that we're both passionate about! Please email me if you're interested in discussing this further.
    > If you'd like to collaborate with OSC Delft to organise future coffees, please email Emmy.
- If you're from TUD and you'd like to receive updates on open science news, opportunities and events, please join our community
    > Join the Open Science Community Delft: http://osc-delft.github.io/join