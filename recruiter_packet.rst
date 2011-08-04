.. header :: ###Title###

.. footer :: ###Page###

=========================================
Recruiter Packet for Votizen Incorporated
=========================================


Preface::

    This packet is designed to assist contingency recruiters in placing 
    candidates with Votizen Incorporated.  It should provide sufficient 
    information for you to begin finding matches to our needs.  Please use 
    what you need from this packet to identify compelling candidates; however,
    do not share the packet itself.  This document is not meant for public 
    consumption.

Our Story
=========

*Votizen: Connecting Voters*

Votizen is about connecting voters: connecting voters to issues they care about, connecting voters to their officials, and connecting voters to other voters.  Votizen provides a specialized channel where voters can listen to one another, join with others,  and express themselves directly to their officials.  Most important, Votizen authenticates each voice as belonging to a registered voter ensuring that the real voices are the ones that really matter.

What we're looking for
======================

We are looking for backend engineers.  We want persons who have worked on low-level languages, have architected systems, or otherwise have built things from scratch that scaled.  We want persons who think elegant, well-documented code is as beautiful as anything you'd find in a museum.  

We are not looking for accidental hackers.  We want people who have written their own framework, rather than used one to create a website.  We don't specifically require a CS degree, but this usually is a strong indicator of a person who thinks like an engineer.  A great candidate will have a strong GitHub portfolio with lots of commits, not just lots of forks.  Inflated titles like CTO are not impressive to us; a well-followed blog is.  

Above all, we want A players.  Our standards are very, very high -- inordinately so -- but we are at the very early stages and want high-quality talent that will attract other high-quality talent.

What we offer
=============

Change the world potential
--------------------------
First and foremost, we're working on something that truly has the potential to change the world in profound ways.  We're helping repair Democracy, and we think that's a lot more important than building a revolutionary way to sell grilled cheese.  Social media is maturing beyond a mere entertainment medium and is helping to depose dictators and increase freedom across the globe.  We're trying to harness that power to improve how government serves its citizens and fix a broken system.  This should appeal to people far more than just another Groupon clone.

Hard technical challenges
-------------------------
We have huge challenges in machine learning, classification, and general scale.  Our database already has every voter in the United States plus their voting history -- in some cases going back thirty years.  This is a billion rows of data and we haven't even started.  We need to figure out how to process this information in way that is meaningful to each and every voter starting in the US (200 million voters) and eventually abroad (Democracy is a growth business.)  Moreover, we have a new approach to social networking that uses dynamic linking, meaning: forming and re-forming the interest graph as opinions change, accommodating new nodes and edges in realtime along the way.  No one has done this before, but it represents the future of social networks.

Real people, real usage, real important
---------------------------------------
As our success grows, more and more real people are going to rely on our tools to help form decisions about the future of our country.  This means that millions of voters will use the tools our engineers create, and will use them every day.  When someone learns that our engineer works at Votizen it will be a badge of honor that each person is working on something so important and fundamental to the lives of everyday citizens.

Top-notch team
--------------
Our team already has absolute top-notch talent:  David Binetti, our CEO, has ten years' industry experience and was the creator of one of the first examples of government e-transparency:  USA.gov.  Jason Putorti, our designer, was the lead designer for Mint.com and is one of the most highly sought-after designers in the valley.  Matt Snider, our engineer, is a front-end guru and has written a book on Javascript (literally).  We want to continue the tradition of only hiring the very best in a given person's field of expertise.

Agile process
-------------
We ascribe to agile development processes.  We are big believers in test-driven development.  We thoroughly document our code.  We engage in continuous deployment.  We don't have a QA department or a staging server -- when something escapes our test coverage and breaks we fix it immediately.  For us, it's all about reducing the iteration cycles.  Our processes favor quick identification of problems and fast recovery.  Speed is the best prevention.  

Great investors
---------------
Our lead investor is Peter Thiel who has one of the best track records in picking winners.  Our board member is Sean Parker.  We have some of the most prescient investors in the business, including Keith Rabois, Mark Goines, Ron Conway, Chris Dixon, and David Cowan.  These investors see a huge opportunity in a space ripe for disruption, and anyone thinking about participating in this space knows that the group we've assembled is second to none. 

Fantastic culture
-----------------
We have a great culture that rewards risk-taking and creativity.  We create features by taking the perspective of the user:  "A member should be able to do FOO in order to accomplish BAR as measured by BAZ."  After that, implementation is up to the engineer.  We are very flexible in our work hours, as long as the job gets done.  And we play hard as well -- the office is very competitive, particularly in Starcraft.

3:1 Engineer to Marketing
-------------------------
We are an engineering-driven company.  Our target is, and will remain, a ratio of 3:1 for engineers to marketers.  In general, we also want our engineers to contribute to marketing, both in ideas and customer interaction.  We think engineers make the best marketers.  We hold daily stand-up meetings and weekly updates, but the emphasis is on commits, not meetings.

Benefits, Perks
---------------
Our benefits and perks are quite light compared to other large companies.  We do have have full health coverage for families, offer commuter checks, and generally try to be as flexible as possible in responding to team members' needs.  But you can forget things like 401Ks, massage therapists and stuff like that.  Our goal is to make our equity so valuable that all those things become rounding errors in our personal net worth.

Compensation
---------------
Being a Peter Thiel funded company, we place a premium on equity participation and not cash salary.  We encapsulate this as, "Salary to live on; Equity to retire on."  Basically, we have a soft-cap on salary of $120K a year.  We can be competitive up to that point, but beyond that the discussion gets more difficult.  Candidates that expect salaries of $180K or more should be strongly cautioned to be prepared for lower rates than they might expect.  Our goal is to make the equity in the company as valuable as possible and we want to ensure that everyone is aligned accordingly.  

Tools
=====
We don't have religion on tools.  Our basic principle is to use the simplest tool that will get the job done.  While things may change, we currently use:

- Amazon Web Services
    - EC2 for front-end servers
    - S3 for serving content
    - RDS for backend MySQL databases
    
- Redis 
    - Use for our newsfeed and other streams

- Python
    - We use Django for our front-end CRUD
    - twisted (for our asynch API)

Business Model
==============
Our long-term business model mimics LinkedIn:  in the same way that LinkedIn charges recruiters for network access to candidates seeking jobs, so will Votizen charge advocacy groups for network access to voters seeking to donate/support causes or candidates.  In the near term, we charge for message delivery on a per-message basis, similar to the AdWords model of pay-per-performance.  

We are a network-effect business.  The more voters that participate in the system, the more valuable the overall system becomes.  These are notoriously difficult businesses to establish, but once established they are immensely valuable (Facebook, EBay, LinkedIn are other examples of network-effect businesses.)  

Bottom Line:  we are either going to be wildly successful, or we will fail totally.  Go Big or Go Home.  There is no middle ground.

Hiring Workflow
===============
Following is the hiring process we employ.

Source
------
Referrals may enter the workflow at any step depending on the nature of the recommendation.  However, all entries must be tracked through our Applicant Tracking System (ATS.)  

Portfolio Review
----------------
Review each portfolio for experience and qualifications.  This should take place within one business day.  After the review, there should be one of three outcomes:

    1.  Fast track to `Phone Interview`_
    2.  Schedule `Phone Screen`_
    3.  `No Match`_

Phone Screen
------------
The phone screen should be used to fill in the gaps in any portfolio items.  It is not designed to test any candidate's specific knowledge or experience as much as it is to find a good match on paper as presented.  The screen should last roughly ten minutes and the output of the screen should be captured as notes in the ATS.  After the screen, a decision should be immediately made according to one of two outcomes:

    1.  Schedule `Phone Interview`_
    2.  `No Match`_

Phone Interview
---------------
The phone interview should be used as a test to find an actual match.  The interview should test the candidate's knowledge and experience, specifically drilling down on any aspect of the portfolio to ensure appropriateness and accuracy.  The interview should last approximately 30-60 minutes and break down as 10 minute introduction of process and Votizen, 10-40 minutes of drill-down, and 10 minutes for any candidate questions.  After the interview, a decision should be immediately made according to one of three outcomes:

    1.  If above bar and local, schedule `On Site Individual`_
    2.  If above bar and remote, schedule `Coding Exercise`_
    3.  `No Match`_

Coding Exercise
---------------
The coding exercise is designed to filter out candidates who have a good portfolio but nonetheless are afflicted by CCD (can't code disease.)  This should be a fairly simple Fizz/Buzz or similar example and should be conducted in real-time to determine the person's skill level.  After the coding exercise, a decision should be immediately made according to one of two outcomes:

    1.  If passes, schedule `On Site Individual`_
    2.  `No Match`_

On Site Individual
------------------
The on site individual is an in-person interview that is meant to test general culture fit.  The person most likely to be the direct report should conduct this on-site.  It could take the form of a lunch, coffee, office sit-down, or other similar meeting.  It should last approximately 1-2 hours.  After the on site, a decision should be immediately made according to one of two outcomes:

    1.  If good fit, schedule `On Site Team`_
    2.  `No Match`_

On Site Team
------------
The on site team is the final step meant to give all team members an opportunity to review skills, culture, and general fit of the candidate.  The should be half- to all-day affairs for the candidate and sponsor, and should require at least 2-3 hours of each team members' time for lunch and individual interviews.  The preferred format is meeting with the sponsor in the morning, with all relevant team members individually in succession, ending with a lunch/dinner with all team members.  After the on site team interview, all team members should come together to make a determination as follows:

    1.  `Hire`_
    2.  `Learn More`_
    3.  `Hold`_
    4.  `No Match`_


Hire
----
Once the decision to hire has been made, the hiring manager must put together and present an offer package within one business day.  **No exceptions**.  

Learn More
----------
This should not be employed frequently; the onus is on the hiring manager to ensure that this process reveals all that is necessary to render a decision.  However, if there are occasions where getting additional information will help render a decision that should happen.  No candidate should stay in the `Learn More`_ category for more than a week; ideally, we should be able to get the information we need with two business days.

Hold
----
Periodically we might find good candidates that would be a good match aside from timing (on one side or another.)  These should be placed in a `Hold`_ status.  Ideally, when candidates are placed on hold there should be a defined trigger to bring them out of that state.  Examples include: vesting fully, finishing school, campaign ending, etc.  It should not be a catch-all category: the supposition should be that all candidates are either hired or declined.

No Match
--------
Most candidates will not be a match.  While each case may be handled individually, all candidates who have on site visits should be informed of no-match via phone.  Others may be informed via email.  All candidates should be treated respectfully.  

Applicant Tracking System
=========================

All recruiters are expected to use our applicant tracking system.  Our current system is *JobScore*, and our instance can be found at http://votizen.jobscore.com.  While JobScore lists positions for both engineers and marketers, only engineers are eligible for placement fees.

To submit a candidate via JobScore, please enter in the candidate's information as if you were the candidate him/herself, and be sure to include your firm's name in the "referred by" field of "Other Information" to ensure you are properly credited for placement.

Questions/Contact Information
=============================

If you have any additional information or questions please contact Marty Schneider at marty@votizen.com or 415.690.8683.


