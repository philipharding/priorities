% USDS Master Project List

In the interest of maximizing the usefulness of our scarce resources,
and managing the team in a sustainable way, USDS makes the deliberate
choice to fully support a smaller number of projects, rather than
partially support a larger number.  As much as possible, we avoid
committing staff to a project unless we can quickly follow through
to establish a large enough team to move at "hull speed."  "Hull
speed" is a concept that applies to boats, which have a maximum
speed of travel, beyond which adding more energy only creates more
waste.

With this staffing strategy, it follows that prioritization decisions
are critical.  Knowing that we will be unable to get to them all,
we apply three criteria to evaluate potential projects relative to
one another

+ Most importantly: what will do the greatest good for the greatest
number of people in the greatest need?

+ Secondly, but sometimes still critical: How ready is the incumbent
team, and how much potential is there for raising the bar or
catalyzing necessary change?  (This is a way of saying "how cost
efficient will a USDS investment be?")

+ Finally, what potential exists to scale or reuse a technological
solution across the Government?

This master list lives in the WhiteHouse github repository here:  
https://github.com/usds/usds/blob/master/administration/priorities.md

The prioritization system depends on the following conventions being
observed with this document:

+ Any effort consuming more than 20 person-hours per week of USDS
staff should be represented here.  (TODO: This version is known to be
incomplete.)

+ Project leaders should keep their mission statements, success
criteria, and staffing list up to date by editing and committing
directly.  Project leaders may also subdivide projects either to
represent separate work streams or different phases, as appropriate.

+ Anyone may append a new project description at the bottom of the
"Projects On Hold" group.

+ Projects in the "Open for Allocations" group **must** have (1) an
owner, (2) a well defined mission and (3) exit criteria with concrete
metrics of success.  The total of open staffing requests in this
group must not be more than 20.

+ Project owners are responible for updates to project missions,
descriptions, metrics, and team composition and should keep the "Last
updated" field current with the date of the last update.  This
document is **NOT** intended for status updates and should only
changes as missions, descriptions, metrics, and team change.

+ Changes to the ordering of the projects, or changes that move a
project from one Group to another, must be reviewed by the USDS
Administrator and Deputy Administrator.


# Projects underway with a fully staffed team

## Dept. of Education: Project Inform College Choice

*Mission:* Engage and educate potential college students of any age or
background and those who support and advise them to find schools best
suited to them.

Success is defined by:
1. Engage a diverse set of students and their supporters
2. Educate the marketplace on key outcome metrics and institutional
      performance
3. Enable “best” college matching
4. Foster continuous improvement

*Team:*  
1x Lead Lisa Gelobter  
0.5x Hacker Erie Meyer  
1x Design Jess Teal  

Temporary:  
0.25x Project manager 18F Holly Allen  
0.5x Ruby Dev 18F Sarah Allen  
0.25x Front End 18F  
0.25x Front End 18F  

Needs:  
1x Product Manager - TBH (Sabrina Williams temporarily filling role)
1x CSS, HTML, Javascript - TBH  
0.25x Ruby Dev - TBH

*Contact:* Lisa Gelobter, lisa.gelobter@ed.gov

*Last updated:* 2015-11-20

## U.S. Web Design Standards

*Mission:* Create a library of open source UI components and a
visual style guide for U.S. federal government websites, to address
inconsistency, poor usability, cost and 508 accessibility.  Make
the shared library availabe to all Digital Service teams to avoid
inconsistent and suboptimal UI across an increasing set of products
touched by USDS teams. Cclose ollaboration with 18F, where this
project was funded through the GSA Seed Fund process.  MVP released Sept 28, 2015. Current project work: internal + external communication campaign, and internal transition to full time product team inside of the GSA.

*Team:*  
0.25x Product/Design Mollie Ruskin (USDS HQ)  
0.5x Product John Yuda (18F)

*Contact:* Mollie Ruskin, mruskin@omb.eop.gov

*Last updated:* 2015-11-15

## Dept. of Veterans Affairs: VBMS SDK

*Mission:* We will develop an SDK for VBMS.  The Board of Appeals
(~X00k claims) and other parts of the agency like VHA would use this
SDK.  For instance, we could give veterans the ability to get the
contents of their claim.  That was recently the subject of a lawsuit
(~45k veterans).  A longer-term solution to putting STRs and health
data into claims could use this SDK.  Make appeals more complete by
making basic information from VBMS available.

*Team:*  
1x SWE Amos Stone (18F)  
1x SWE Jacob Harris (18F)  
0.5x SRE/Devopsen Alex Gaynor (DS at VA)  

*Contact:* Marina Martin, marina.martin@va.gov  

*Last updated:* 2015-10-29

## Dept. of Veterans Affairs: Enterprise Health Management Platform (eHMP) Development Performance

*Mission:* Understand, characterize, and eliminate performance issues
with eHMP. Particular focus on front-end performance e.g. JavaScript,
reported IE issues.

*eHMP POC:* David Waltman

*Digital Service POC:* Joe Stewart

*Deliverable:* Action plan to include identification of gaps in
performance metrics, remediation options, recommendations, &
timeline. Concrete before and after performance metrics showing
statistically significant improvement.

*Exit Criteria:*
+ Lack of support for action plan
+ Lack of resources to incorporate recommendations

*Team:*
+ 1x SWE Joe Stewert (DS at VA)  
+ 0.25x SWE Gajen (USDS HQ)  
+ 0.25x PM Dave Waltman  

*Contact:* Marina Martin, marina.martin@va.gov  

*Last updated:* 2015-10-25  

## USDS HQ: Rapid Response Team: Rogue Squadron

*Mission:* Provide a standing rapid response capability at USDS HQ. Team's
capability and response style in the manner of the eQIP/OPM and visa processing
engagements. Team builds and sustains education and training for USDS-at-large.
Details here:
https://github.com/usds/usds/blob/master/administration/rapid-response-team.pdf

*Team:*  
1x SRE/Lead Matthew Weaver  
1x SRE Open (potentially staffable by reserves)  
1x SRE Open (potentially staffable by reserves)  

*In team matching phase:*  
2015-11-17 Eng Holly French  
2015-11-24 Eng/SRE Samantha Schaevitz  

*Contact:* Matthew Weaver, Matthew.Weaver2@va.gov

*Last updated:* 2015-11-02

## Dept. of Defense: Defense Travel System

*Mission:* Provide DoD with support as they prepare to implement the
recommendations of the DTS sprint team.  The Defense Travel spend is
over $8B per year of which over $3.5B is handled through the Defense
Travel System, with a per-transaction cost around $10.  The DoD sprint
team recommends vastly simplifying the 1600 pages of DoD travel
regulations in order to transition to a commodity expense accounting
system.  We expect this to save hundreds of millions of dollars per
year, unlock indirect cost savings (via travel analytics), and improve
satisfaction with DoD customers (current system is widely disliked).
The Deputy Secretary of Defense (Bob Work) has directed the relevant
HR and travel offices to work towards completing the policy review and
the initial technical transition in 120 days.

*Team on Recommendation 1: Simplify Policy*  
1x Acq Jonathan Mostowski (USDS HQ)  

*Team on Recommendation 2: Use COTS*  
1x Acq Jonathan Mostowski (USDS HQ)  
1X SWE TBD  

*In team matching phase:*  
2015-11-24 Eng Amy Quispe  

*Team on Recommendation 3: Invest in Data Science*  
1x Acq Jonathan Mostowski (USDS HQ)  
1X DS TBD  

*Contact:* Jonathan Mostowski, jmostowski@omb.eop.gov

*Last updated:* 2015-09-18

## Dept. of Health and Human Services: Institutionalize healthcare.gov

*Mission:* healthcare.gov is a key enabling component of the Affordable Care Act, which allowed over 16M previously uninsured Americans to obtain health insurance, many through healthcare.gov.  It is also the primary consumer-facing website in the government healthcare space.  It is essential that the site support current needs through this Open Enrollment.  In addition, the site has been plagued with problems and an expensive and outdated implementation.  In order for the policy to continue being effective, the site must be improved to provide a more sustainable solution.

Success is defined by:
1) Ensure healthcare.gov remains operational for the duration of open enrollment season, by any means necessary, with a bias toward training CMS & contractor teams to manage the technology themselves.    
2) Guide the development of a sustainable long-term future for the site.  This will require a mini-sprint to understand priorities and trade-offs.  Key solutions may include one or more of the following: Assisting with the deployment of next-gen components such as Standalone Eligibility Service (SES) or a healthcare.gov API; Moving to a "lights-out" XOC-less operations model; Moving more components of healthcare.gov to the cloud.

*Team:*
1x Lead Mina Hsiang (USDS HQ)  
1x SWE Joe Crobak (USDS HQ)  
1x SWE Lori Thomas (USDS HQ)  
1x SRE Shauni Deshmukh (USDS HQ)  

*Contact:* Mina Hsiang, mina_k_hsiang@omb.eop.gov

*Last updated:* 2015-11-17

## GoodGov-UX

*Mission:* Lead the RFP Language initiative within GoodGov UX,
http://goodgovux.com/, which is a public/private partnership to
drive the adoption of a common set of UX best practices.  Create
an "Acq-athon" to produce RFP templates and services which will
streamline acquisition for digital services.  Work products will
be placed in the TechFAR Hub and will be available to all agencies
trying to implement Playbook strategies.

*Team:*  
0.2x Acquisitions Specialist Jonathan Mostowski (USDS HQ)  

*Contact:* Jonathan Mostowski, jmostowski@omb.eop.gov

*Last updated:* 2015-11-05

## USDS HQ Operations

*Mission:* Complete any requirements that pop up for HQ on an ad hoc
basis. This includes various administrative or reporting requirements
(e.g. GAO), the President's budget, compliance reporting or policy
review. These projects do not fall under a specific area of expertise,
but are required to be completed.

*Team:*  
0.2x Raph Majma (open source policy)  
0.5x Mary Lazzeri (GAO, 2017 budget)  
1x Stephanie Grosser (GAO, 2017 budget)  
1x Natalie Moore (travel, events, onboarding, HR)  

*Contact:* Raphael Majma, rmajma@omb.eop.gov

*Last updated:* 2015-11-05

## Common Platforms/Scaling Services

*Mission:* In conjunction with the digital coalition, prioritize and deliver common components that improve the quality and efficiency of developing, testing and delivering services. 

*Team:*  
1x Lead Ginny Hunt  
1x Project Manager Lucy Brady  

*Contact:* Ginny Hunt, hhunt@omb.eop.gov

*Last updated:* 2015-11-18

## Dept. of Justice: National Instant Criminal Background Checks (NICS)

The National Instant Criminal Background Check System (NICS),
operated by the FBI, is the system they use for determining eligibility
to buy firearms or explosives. Recently, NICS was identified in the
news, and by the FBI, as a point of failure that allowed the
Charleston shooter to purchase a gun, citing issues with a failure
in how data is shared between local authorities and the federal
government.

CJIS (Criminal Justice Information Services Division) of the FBI
is launching a new NICS system in January. The initial sprint will
evaluate the new system and steps that need to be taken to ensure
a successful launch. The DOJ team will also be assessing the overall
program, including barriers to receiving necessary data from state
courts and law enforcement agencies.

*Team:*  
1x Lead Vivian Graubard (USDS HQ)  
1x PM (tech+policy) Clarence Wardell (USDS HQ)  
1x Data/SWE Dav Zimak (USDS HQ)  
1x SWE Ron Gorodetzky (USDS HQ)  
0.6x UX Dana Chisnell (USDS HQ intermittent)  
**1x Design Open - after Dana leaves week of 11/16**  
**1x UX Research Open - also partially filling Dana's role**  
**1x Data/SWE Open - replace Dav come mid-December**  
**1x Eng Open - replace Chuckr, preferably familiar with release and large-scale launches.**  

*In team matching phase:*  
2015-11-17 Data Brandon Bouier  
2015-11-17 Frontend Eng David Holmes  
2015-11-17 Design Misty Cripps  

*Contact:* Viv Graubard, vgraubard@omb.eop.gov

*Last updated:* 2015-11-18

## Digital Service Contracting Officer Training Challenge/Pilot

*Mission:* Create a training and development program for the Federal
Government Contracting Officers to enable them to be placed in an
agency Digital Service team or work on agency Digital Service
Procurements.

*Success Defined by:*
- Creating and launching a challenge on Challenge.gov to run a pilot
  of the program
- Successfully running the pilot with at least 30 Contracting Officers
  starting in 2015
- Conducting a retrospective of the pilot and turning the results over
  to Federal Procurement
- Training institutions to be implemented in 2016
- Defining the requirements for a Digital Service Contracting Officer
  Certification as a FAC –C Core plus specialization

*Team:*
1x Procurement Advisor Traci Walker
0.75x Procurement Advisor: Mike Palmer
0.5x Procurement Advisor: Jonathan Mostowski
1x OFPP Representative: Joanie Newhart
0.25x Pilot Project leads (TBD)

*Contact:* Traci Walker twalker@omb.eop.gov

*Last updated:* 2015-11-05

## Acquisition Data Research Project

*Mission:* To determine how to reduce barriers to entry for new and
qualified companies to participate on Digital Service acquisitions,
research is going to be conducted to look at the major problems with
the acquisition process (time, costs, certifications, bad
requirements, etc.) in order to help inform the Procurement team. This
data will be used to formulate best practices for market research and
conducting streamlined acquisitions while getting to competent
companies.

*Success Defined by:*
- Utilizing IDA – an FFRDC –to collect the data
- Reviewing the information and providing outputs to OMB and Agencies
- Getting clear understanding of how much “money” antiquated
  Procurement methods cost the government
- Giving new “plays” to agencies to get to new and innovative
  companies who can support Digital Service investments

*Team:*
.5 x Procurement Advisor: Mike Palmer
.25 x Procurement Advisor: Jonathan Mostowski
.25 x Procurement Advisor: Traci Walker

*Contact:* Mike Palmer, mpalmer@omb.eop.gov

*Last updated:* 2015-11-05


# Projects open for current allocations

_Maximum 20 open FTE total across projects in this group._

## Dept. of Homeland Security: ELIS Operations

*Mission:* Manage the regular releases of ELIS, help set development
priorities, and support the performance and availability of the
production system.  This will ensure that USCIS Transformation
continues to make progress in the move to ELIS.  Poor releases or
production instability might undermine confidence and delay the
transition of future product lines.

Success criteria include:

+ Over 90% of ELIS weekly releases (11/12 a quarter) are deployed on
  schedule, without downtime, and without any disruptions requiring
  USDS involvement

+ ELIS has 99% uptime.

+ ELIS provides reporting that meet the needs of operations centers
  and executive leadership.

*Team:*  
1x SWE Nick Lesiecki (USDS HQ)  
1x SWE Offer Accepted, Pending Security (DHS)  
1x SWE Offer Accepted, Pending Security (DHS)  
**1x SRE Open (Needed Q1 2016)**  

*In team matching phase:*  
2015-11-17 Eng Holly French  
2015-11-24 Eng/Lead Guy Hussussian  
2015-11-24 Eng/SRE Samantha Schaevitz  

*Contact:* Eric Hysen, Eric.Hysen@hq.dhs.gov

*Last updated:* 2015-11-02

## Dept. of Veterans Affairs: Disability Claim Appeals

*Mission:* We would develop an end-to-end technology pipeline for
veteran appeals.  This would impact the backlog in appeals, which is
X00k claims.  The pipeline could serve as a short-term solution
proving requirements.  Some claims are X000 days old.  Will be a proof
of concept for ideas that could be repurposed on the primary VBMS
claims process.

Success is defined by:

+ Electronic evidence review is faster than paper (current
productivity standard is 3 appeals per week per judge)

+ Zero appeals lost into the "seam" between VBA and BVA

+ Less than 1% appeals returned to VBA for missing documents
(currently 88%)

+ Veterans can see accurate appeals status on vets.gov

*Team:*  
1x PM Giuseppe Morgana (DS at VA)  
0.5x SRE/SWE Alex Gaynor (DS at VA)  
1x SRE/SWE Jeff Maher (DS at VA)  
1x SRE/SWE Paul Tagliamonte (DS at VA)   
1x UX/Design Kavi Harshawat (DS at VA)  
1x SWE Frontend Open (offer pending)  
1x SWE Frontend Tiffany Brown (USDS HQ)  
1x UX/Research Mary Anne Brody (USDS HQ)  
**0.5x Interaction Designer Open**  

*Contact:* Marina Martin, marina.martin@va.gov  

*Last updated:* 2015-10-17

## Dept. of Veterans Affairs/Dept. of Defense: STR Pipeline

*Mission:* The successful and timely transfer of Service Treatment
Record (STR) records between the DoD and VA is a critical part of
delivering veteran benefits to service members.  To meet the agreed
target of adjudicating veteran benefit claims in 125 days or less,
a complete and certified STR record must be made available by the DoD
to the VA in 45 days or less.  This project, jointly staffed at the
VA and DoD, will assist engineers and process managers at both
agencies to inspect STR transfer requests, identify potential errors,
and support the construction and deployment of tools and process
for the correct and timely transfer of STRs.

*Team:*  
1x Product/Project Manager Chris Lynch (USDS HQ)  
1x SWE/Generalist Brian Lefler (USDS HQ)  
**1x SRE/Devops Open**  
1x SWE Backend Justin Tansuwan (USDS HQ)  
1x SWE/Generalist Nick Small (USDS HQ)  
0.5x Frontend Eng/UX (5 Weeks) Alex Ose (USDS HQ)  

*Contact:* Evan Cooke, Evan_M_Cooke@omb.eop.gov

*Last updated:* 2015-11-05

## Dept. of Homeland Security: USCIS Transformation/Naturalization

*Mission:* Drive USCIS development and product priorities, including
implementing a peer code review process, redesigning the customer
application experience (through myUSCIS and application wizards),
improving business processes and redesigning internal services to
increase adjudication efficiency, and building design capacity
within the agency.  Generally includes all engineering, product,
and design work outside of core ELIS operations.  Includes tracking
of visa modernization from DHS. Also includes building out design
capacity at DHS to mature design processes for both ELIS and myUSCIS.  

Success criteria include:

+ Processing cases in ELIS is more efficient than on paper, resulting
  in shorter cycle times and lower fees.

+ Adding a new form type to ELIS without significant new functionality
  can be done in <3 months.

+ Customers spend less time completing applications and navigating
  USCIS processes.

*Team:*  
1x SWE Andy Nacin (USDS HQ)  
1x SWE Victor Garcia (USDS HQ)  
1x PM Aalok Shah (DHS)  
0.4x Design Lead Dana Chisnell (USDS HQ)  
1x Design Lead Offer Accepted, Pending Security (DHS)  
1x Research Lead Offer Accepted, Pending Security (DHS)  
1x PM Offer Accepted, Pending Security (DHS)  
1x Visual Designer Open (Needed Q1 2016)  
1x Visual Designer Open (Needed Q2 2016)  
1x Interaction Designer Open (Needed Q1 2016)  
1x Interaction Designer Open (Needed Q2 2016)  
1x Production Designer Open (Needed Q2 2016)  
1x User Researcher Open (Needed Q1 2016)  
1x Content Specialist Open (Needed Q2 2016)  

*In team matching phase:*  
2015-11-17 Design Anne Kainic  
2015-11-17 Frontend Eng Casey Klebba  
2015-11-17 Design Misty Cripps  

*Contact:* Eric Hysen, Eric.Hysen@hq.dhs.gov

*Last updated:* 2015-11-02

## Dept. of Education: Student Loan Default Discovery Sprint

*Mission:* In June 2014, U.S. student loan debt exceeded $1.2
trillion, with over 7 million debtors in default, or 13.7% of
borrowers. We propose to conduct a 5 person, 2 week discovery sprint
to get clarity on the current status of Federal student loan defaults,
and what digital service solutions could be implemented to eradicate
defaults.

Success is defined by:

+ There is a set of credible recommendations that could end Federal
student loan defaults

+ FSA/Ed adopts most or all recommendations

*Team:*  
1x Lead Lisa Gelobter (USDS HQ)  
0.5x Hacker Erie Meyer (USDS HQ)  
1x Design Jess Teal (USDS HQ)  
1x SWE Sabrina Williams (USDS HQ)  
**1x SRE/SWE Open (ideally with a strong data science background) by HQ**  
**1x PdM Open (via ED-hiring)**  

*In team mathing phase:*  
2015-11-24 Eng Amy Quispe  

*Contact:* Lisa Gelobter, lisa.gelobter@ed.gov

*Last updated:* 2015-11-20

## Dept. of Homeland Security: CBP Single Window

*Mission:* Conduct a discovery sprint to determine what (if any) USDS
involvement is appropriate in the Single Window effort, which has the
potential to generate significant economic value through streamlining
how traders submit information to multiple government agencies.

*Team:*  
**1x Project Lead Open (Needed Q4 2015)**  
1x Eng Amine Raounak (DHS)  
1x Eng Chris Frommann (USDS HQ)  
**1x Design / PM Generalist Open (Needed Q4 2015)**  

*Contact:* Eric Hysen, Eric.Hysen@hq.dhs.gov

*Last updated:* 2015-12-01

## Internal Revenue Service: Secure Accounts

*Mission:* Deliver the ability for taxpayers to create secure accounts:
strongly identity proofed and protected by 2-factor authentication.  Secure
accounts are expensive to defraud and are persistent through time.  These
accounts form the basis for everything the IRS wants to do online in the
future: customer self-service to drive down call volume, access to new
services, and replacement of current paper-based access with automated
processes.  Secured accounts are also fundamental to authorized sharing of
information with third parties, such as API income verification necessary for
the Dept. of Education's student loan automatic recertification.

Success Criteria include:

+ Taxpayers can create a Secure Account within 15 minutes from
  starting the process.

+ Taxpayers can easily recover their accounts if they forget their
  password or lose their phone.

+ Secure Accounts launch by the end of March 2016 which sheds some
  load at IRS call centers this filing season.

*Team:*  
1x Lead/SWE David Chang (USDS HQ)  
0.5 Policy Mary Lazzeri (USDS HQ)  
**1x Backend SWE Open**  
**1x Senior UX Architect Open**  

*Contact:* Kim Rachmeler, Kimberly_A_Rachmeler@omb.eop.gov

*In team matching phase:*  
2015-11-24 Eng Raquel Romano  
2015-11-24 Eng/SRE Samantha Schaevitz  

*Last updated:* 2015-11-03

## Identity infrastructure

*Mission:* Lead, align and accelerate implementation of secure, simple access to high value digital services and personal information stored by the federal government. Deliver successful implementation of key digital service launches (e.g. IRS Secure Accounts) that depend on common infrastructure, high quality products and service design patterns for effective identity-proofing, multifactor authentication and authorization.

*Team:*  
1x Lead Open

*Contact:* Ginny Hunt, hhunt@omb.eop.gov

*Last updated:* 2015-11-18

## Joint Talent Team

*Mission:* Build a rich, diverse, sustainable pipeline of 500 top tech
and design folks to serve in the USG by January 2017.  Top Silicon
Valley recruiters bring in 1-2 top Line hires each month (per
recruiter) and 1 top tech leader each quarter (per recruiter).  As of
July our rate was approx 11 hires/month/per recruiter and is
unsustainable.  To reach this goal for the Joint Talent Pipeline, we
are building out a team of 20. (12 tech recruiters x 24 line hires per
year each is 240 candidates.)

*Team:*  
1x Head of Talent Jennifer Anastasoff  
1x Outbound Recruiter 1 Rachelle Gupta  
1x Outbound Recruiter 2 Megan Snider  
1x Outbound Recruiter 3 Dennis Gilbert  
**1x Outbound Recruiter 4 Open**  
**1x Outbound Recruiter 5 Open**  
**1x Inbound Recruiter 1 Open**  
**1x Inbound Recruiter 2 Open**  
**1x Inbound Recruiter 3 Open**  
**1x Inbound Recruiter 4 Open**  
**1x Inbound Recruiter 5 Open**  
1x Recruiting Coordinator 1 Lucy Shaw  
1x Recruiting Coordinator 2 Jenny Smith  
1x Recruiting Coordinator 3 Onboarding pending security  
1x Recruiting Coordinator 4 Onboarding pending security (Start: 12/14/15)  
1x Recruiting Coordinator 5 Onboarding pending security  
1x Strategic Partnerships Cat Posey  
1x Talent Operations Lead (replace by Jan 2016) Charles Worthington  
1x Talent Operations 1 Chase Kimball  
**.5x Talent Operations 2 Open**  
**.5x Talent Coordinator Open**  

Likely will need 2 additional technical recruiters in early 2016 to
account for turnover.

*Contact:* Jennifer Anastasoff, janastasoff@omb.eop.gov

*Last updated:* 2015-11-06

## Dept. of Homeland Security/Dept. of State: Visa Modernization

*Mission:* Implement technical and design recommendations from our
past assessment.  Ensure the success of the August pilot of modernized
immigrant visas.

Executive support has been clarified.  Charter has been signed by Mikey and Heather Higgenbottom. 

Success criteria include:

+ The immigrant visa process is entirely paperless.

+ USDS key recommendations are implemented or on a clear track to
  implementation.

+ CCD is a stable, well-managed system.

*Team:*  
0.5x PM Raphael Majma (USDS HQ)  
1x SWE Marianne Bellotti (USDS HQ)  
**1x SRE at DoS Open**  

*In team matching phase:*  
2015-11-24 Eng/Lead Guy Hussussian  

*Contact:* Raph Majma, rmajma@omb.eop.gov

*Last updated:* 2015-11-05

## Dept. of Veterans Affairs: Vets.gov

*Mission:* Plan and develop a platform for veteran products, like
websites.  Help develop those products. An example would be a single,
simple site where a veteran deals with disability benefits.  They
could apply for a disability benefit, check its status, choose where
to deposit it, or file an appeal. This includes a lot of
infrastructure work in order for the platform to be useful.  For
example, the VA has 6+ login systems, and 40+ systems storing veteran
addresses.  Reduce the population of 1000+ separately maintained
websites.  Make it easy for multiple teams to build on the platform
via APIs and re-usable assets.

*Team:*  
1x PM Kelly O'Connor (DS at VA)  
1x Platform Tech Lead (pending)  
1x Design Lead Emily Wright-Moore (DS at VA)  
1x UX Rick Lee (DS at VA)  
1x SWE Backend Marc Harbatkin (DS at VA)  
1x SWE Backend Eric Schles (DS at VA)  
**1x Information Architect Open**  
**1x Digital Content Lead Open**  
**1x UX Open - role includes user test support**  
**1x Visual Designer Open**  
**1x SWE Frontend Open**  
**1x SWE Frontend Open**  
**1x SWE Backend Open**  
1x SRE Open (Q2 2016)  
1x SWE Frontend Open (Q2 2016)  
1x SWE Frontend Open (Q2 2016)  
1x SWE Backend Open (Q2 2016)  
1x SWE Backend Open (Q2 2016)  

*In team matching phase:*  
2015-11-17 Design Anne Kainic  
2015-11-17 Eng Casey Klebba  

*Contact:* Marina Martin, marina.martin@va.gov

*Last updated:* 2015-11-18

## Dept. of Homeland Security: DS Team Front Office

*Mission:* Build and lead the Digital Services Team at DHS.  

*Team:*  
1x Executive Director Eric Hysen (DHS)  
1x Deputy Executive Director Open (Needed Q1 2016)  
1x Program Manager Katy Haynes (DHS, Start Date 12/14)  
**1x HQ Liaison Open (Needed Q4 2015)**  
1x Special Assistant Open (Needed Q2 2016)  

*Contact:* Eric Hysen, eric.hysen@hq.dhs.gov  

*In team matching phase:*  
2015-11-24 Hacker Amy Barker  

*Last updated:* 2015-11-02
  
## Social Security Administration: Disability Claims Processing System

*Mission:* Assist SSA at taking over program management for DCPS.
Current DCPS is a project about 7 years old, hundreds of millions of
dollars, contractor-led, and about 60% complete.  Critical decisions
about how to build the future versions of DCPS will be made in the
next 1-2 months.  The USDS estimate, via Rob, is that taking program
management in-house could be an order of magnitude savings in money
and time.  The team is using the MEAN stack, but using Postgres
instead of MongoDB.

*Team:*  
1x PM Michael Plasmeier (DS at SSA)  
1x Sr. SWE Eng Infra/Agile consultant Eric Benson (USDS HQ)  
1x SWE Hung Nguyen (USDS HQ)  
**1x SWE Open** (Preferred skills: experience with Case Management Systems, knowledge of AWS, Node.js, React, Express, PostgreSQL, database architecture.)  
0.1x Design (occasional advising) Mollie Ruskin (USDS HQ)  
1x Sr. SWE/Eng Lead Alex Ose (USDS HQ)  
1x Frontend Engineer Alan Ning (DS at SSA)  
1x Automated Testing Engineer. (SSA Engineer.  USDS backfill requested for early 2016)  
  
*Contact:* Charles Worthington, cworthington@omb.eop.gov

*In team matching phase:*  
2015-11-24 Eng/Lead Guy Hussussian  

*Last updated:* 2015-11-18

## Internal Revenue Service: Event Driven Architecture

*Mission:* Modernize IRS tax return processing systems to accelerate
the rate at which electronic returns are processed and improve the
error-resolution for improper returns.

*Justification:* Currently, electronic returns are batched together
and sent through a monolithic processing system. The IRS is proposing
to extract the processing system into modules that can process
individual returns. This is expected to allow processing tasks to run
concurrently, to provide visibility into the state of a return, to
allow individual modules to be scaled indepedent of the needs of the
other systems, and to prevent issues with one return from impacting
the processing of another.

*Team:*  
1x Product Manager Ben Getson (IRS)  
**3x SWE Open**  

*Contact:* Kim Rachmeler, Kimberly_A_Rachmeler@omb.eop.gov

*Last updated:* 2015-11-17

## Small Business Administration: Small Business Certifications

*Mission:* Support SBA in managing the agile contract to redo the web
apps used by disadvantaged small businesses to certify themselves for
government contracting programs.  Ensure the implementation of the
USDS sprint recommendations. Contractor has started work as of August
19, 2015. SBA has open headcount and is ready to hire people directly
to agency.

*Success Defined by:*
- Contractor team currently implementing the new certifications
  application successfuly ships the first release in February 2016,
  supporting the application of women-owned small businesses.
- SBA adopts whatever authentication system USDS believes should be
  the standard implementation for citizen-facing services
- SBA successfully decomissions the applications, databases and
  hardware currently supporting the certifications application, and
  replaces these with modern applications by the end of 2016.

*Team*:  
1x Project Manager (Mary O'Toole)  
**1x UX/Design Open**  
**1x SWE (Ruby / Rails Application Developer) Open**

*Contact:* Charles Worthington, cworthington@omb.eop.gov

*Last updated:* 2015-11-06

# Projects on hold

_Keep in order of likely promotion to Group 1._

## Dept. of Veterans Affairs: Enterprise Health Management Platform (eHMP) Design and User Experience

*Mission:* Lead the eHMP product design team, at the request of
current lead Jonathan Nebeker, to build and deliver a user focused
eHMP product. Development is underway with a contracting team, but
there are concerns with the product meeting user needs. We will
provide support in end to end user testing, and leading the design
teams to create a product that is delightful and usable by all the
different users and use cases of the eHMP system.

*Team:*  
1x Product Manager Kathy Pham (USDS HQ)  
1x Design Lead Usability Craig Harrington (DS at VA)  
1x Design User Experience/Interaction Designer Open  
1x Design User Experience/Interaction Designer Open  
1x SWE Frontend Open  

*Contact:* Marina Martin, marina.martin@va.gov

*Last updated:* 2015-11-18

## CMS/HHS: Discovery Sprint (likely focus: Modernizing Medicare/Medicaid Payment & Data Systems)

Ideally to begin Mid November

*Mission:* CMS processes 1.2B claims annually, totalling almost $1 trillion.  That purchasing power makes CMS a key driver for healthcare innovation and improvement, which require changes in incentives and data management.  However, all of those claims are currently processed on antiquated systems with poor documentation, significant interdependencies and single points of failure, and which do not allow for changes, updates, analytics, etc.  In addition, new payment rules such as MACRA require new capabilities in terms of data collection, analysis, and return to providers, as early as 2017.    

Success is defined as:  A prioritized and creditable plan for the USDS HHS team which most effectively enables data-driven payments and care, and facilitates IT transformation at CMS, thereby enabling further healthcare delivery system reform. 

*Team:*  
1x Lead   
1X Product Manager or Hacker Open  
1x SWE Open  
2x SWE with Data expertise Open  

*Contact:* Mina Hsiang, mina_k_hsiang@omb.eop.gov  

*Last updated:* 2015-11-17

## VA/HHS: Building PMI: Product management and technical consulting on MVP/PMI

*Mission:* Ensure that the software tools (and underlying IT) for PMI
and MVP result in strong user engagement and enable outstanding new
scientific discovery.

*Team:*  
0.5X System Architect/Senior Engineer (limited engagement)  
1x Product Manager TBH  
1X SWE TBH (potentially 18F)  

*Contact:* Mina Hsiang, mina_k_hsiang@omb.eop.gov

*Last updated:* 2015-11-17


## Small Business Administration: BusinessUSA

*Mission*: BusinessUSA was originally conceived by the President in
2011 to be a "single front door" to the business services of the
federal government. A site was built focusing on helping "direct"
businesses to the appropriate agency service depending on their
needs. The White House, SBA and Commerce now agree that the usefulness
of a "portal" site is limited, and that future efforts should focus on
improving the transactional services businesses use to interact with
the government.

SBA is staffing a team to focus on improving some of these key
transactions, including determining eligibility and applying for a
government-backed business loan, receiving small business counseling
services, and using a popular government-provided tool to aid in
business plan creation. The digital service team working on this
initiative will have a high degree of autonomy to guide the direction
of the team and determine which products it focuses on. The team will
also be responsible for guiding the work of an existing contractor
development team.

*Team*:  
**Note: Team size reflected here is notional, requires further verification**  
1x PM Open  
1x UX interaction/visual designer Open  
1x UX researcher Open  
2x SWE application developers Open  

*Contact:* Charles Worthington, cworthington@omb.eop.gov

*Last updated:* 2015-11-24

## VA/DoD Interoperability: Getting data back from external providers

*Mission:* Make sure veteran and service member health records are
complete and available for care and better system management. 60% of
care for the DoD is delivered in the external market. 70% of veterans
receive some of their care in the private market. Currently, the data
which comes back from these transactions does not come quickly
(sometimes more than 30 days) and comes in PDF form.  The goal of this
sprint is to build a way to get them back more quickly and easily, in
a way that is useful in the long term- with capabilities for both the
current and future EHR.

*Team:*  
0.5x Lead (Mina Hsiang)  
0.5x Procurement expert (Traci)  
1x SRE  Open (possible: DDS?)  
1x Project/product Manager Open (possible: Rachel Gordon?)  
3x SWE  Open (possible: DDS?)  
Optional 1x test engineer Open  

*Contact:* Mina Hsiang, mina_k_hsiang@omb.eop.gov  

*Last updated:* 2015-10-04  

## VA/DoD/HHS: API-based interoperability at VA and DoD: plus tools and standards for Health Record Interoperability

*Mission:* Create reference implementations at VA and DoD (maybe HHS)
of API-based interoperability in a health system, and in doing so
generate the toolkit and playbook for implementation elsewhere.  This
will put VA and DoD at the forefront of interoperability, will advance
and accelerate the most likely model for EHR interoperability, and
create the tools and playbook for implementation and testing which
will be required by HHS to push it out across the industry.

*Team:*  
0.5x Lead (Mina Hsiang)  
1.5x SWE with healthcare experience Open  
2x SWE without healthcare experience Open  
Optional 1x test engineer Open  

*Contact:* Mina Hsiang, mina_k_hsiang@omb.eop.gov  

*Last updated:* 2015-09-17  


## Dept. of Veterans Affairs: Enterprise Health Management Platform (eHMP) API Validation

*Mission:* We will validate the usability of and drive completion and
productization of the eHMP API, which is essential for the success of
eHMP/Vista Evolution (VE) as an advanced platform for healthcare
delivery. We will do this by using the current eHMP API to connect an
existing production application, DEAP-CUI (Disability Exam Clinician
User Interface), to eHMP. This will allow disability exams to consume
interoperable health data, potentially eliminating the need for some
disability exams, potentially automating some disability claim
decisions, and potentially increasing the accuracy and speed of
disability claim processing. It will also allow DEAP-CUI to write a
patient to VistA, an incomplete current requirement, using the eHMP
API instead of current, disparate services. Success of eHMP/VE paves
the way for vastly improved health records interoperability at a
national level. This project allows us to test and provide actionable
feedback on multiple parts of the eHMP API. There is a pending
DEAP-CUI development support contract that can provide additional
assistance for overall DEAP-CUI development, allowing us to focus on
the eHMP API specifically.

*Team:*  
1x PM Angela Gant-Curtis (VA)  
1x SWE Christine Feeney (DS at VA)  
1x SWE Open  
0.25x SWE Frontend (Minimal need since app already exists; will borrow from Vets.gov design team as needed)  

*Contact:* Marina Martin, marina.martin@va.gov  

*Last updated:* 2015-10-25  

## Dept. of Defense: HR IT Modernization

*Mission:* Reduce inefficiency in the DoD's $11B/year spent on HR
management.  Recent consulting report found the DoD paying 870% more
than the second costliest organization.  Integrate 15 time and
attendance systems for civilian employees, consolidate civilian
service history records to help OPM with pension processing.  Note
that the hull-speed cost will change if the plan to buy COTS SaaS
proves infeasible.  Similar precedent is DIMHRS, an integration
project that ran from 2003-2010 at a cost of $1B with minimal results
(per GAO).

*Cost to reach hull speed:* 3.5 FTE.  1x product manager, 1x data
scientist, 1 engineer, 0.5 acquisition specialist.

*Contact:* Mikey Dickerson, mdickerson@omb.eop.gov

*Last updated:* 2015-11-01

## Dept. of State: Knowledge Management

*Mission:* Department project to better articulate and share expertise
across the organization.

*NOTE* This project does not need dedicated staff. The State team will
work on this as needed in a part-time basis.

*Contact:* Raphael Majma, rmajma@omb.eop.gov

*Last updated:* 2015-11-19

## Dept. of Commerce: Census Bureau Decennial Census Discovery Sprint

*Mission:* The U.S. Census Bureau is preparing for the 2020 Census of
the United States. The key technology systems required to support
Census will need to be in place by 2018. Key systems include field
logistics/rate planning, data management, and -- perhaps most
importantly -- online census response (this will be the first
decennial census where citizens are asked to respond online instead of
by mail). The Bureau will also be building systems to support the
hiring and training of 3 million temporary workers (the largest
peacetime workforce mobilization in government history).

The first step for engaging with the Census will be to conduct a 3-4
person, 2-3 week discovery sprint that will be used to gain clarity on
possible Census projects as a prerequisite to any other Census
projects, foster buy-in and build awareness.  This sprint will focus
on the Adaptive Survey Design, Census Enterprise Data Collection and
Processing (CEDCAP) as well as Census Enterprise Dissemination
Services and Consumer Innovation (CEDSCI) programs.

Update per Jen Tress: 18F Hiring and Consulting is taking this on as a
project. As such, USDS should not consider this a significant
priority.

*Team*:
1x Product Manager/Team Lead Open
1x SWE/SRE Open
1x Data Engineer Open
1x UX Open

*Contact:* Mary Lazzeri, Mary_A_Lazzeri2@omb.eop.gov

*Last updated:* 2015-09-17

## Social Security Administration: Business Intelligence

*Mission:* Develop an enterprise data warehouse to subsume several
purpose-built data marts serving various information rep¬orting
requirements. Extend the quality and quantity of data available to
static reports, ad hoc queries, and research projects. Integrate a
warehouse DBMS, Hadoop staging area and sandbox, and one or more
business intelligence tools for end users. Integrate or obviate the
existing partly overlapping reporting systems.

*Team:*
1x Product Manager
1x Data Architect
1x Data Scientist

*Contact:* Charles Worthington, cworthington@omb.eop.gov

*Last updated:* 2015-09-25

## Social Security Administration: Reduce the hearings backlog

*Mission:* Reduce the nearly 1 million cases in the hearings backlog
by developing a more efficient hearings process. Provide automation in
the process where possible and provide a system for documenting
decisions to ensure consistency.

*Team:*
1x Senior SWE
1x Data Scientist

*Contact:* Charles Worthington, cworthington@omb.eop.gov

*Last updated:* 2015-09-25

## Social Security Administration: Risk and Fraud Detection

*Mission:* Develop a system to model fraud, and then to detect fraud,
in any of the agencies benefit programs in order to reduce the
incidence of improper payments.

*Team:*
1x product manager
1x data scientist

*Duration:* 18 months +- 6 months

*Background*: The SSA has funded a new Office of Anti-Fraud under the
CFO in order to reduce the incidence of improper payments. This
program is the direct result of pressure from Congress.

*Justification*: A more effective system could save multiple billions
of dollars per year. A small number of expert resources are required
to get the program to hull speed. The key expertise required, a data
scientist, is not in high demand across the other projects on the USDS
Master list. As a result, this has a high-ROI with little impact on
competing projects.

*Contact:* Charles Worthington, cworthington@omb.eop.gov

*Last updated:* 2015-09-25

## Social Security Administration: IT Modernization

*Mission:* Replace our aging infrastructure and provide for a modern,
robust environment. Efforts include data modernization, infrastructure
modernization, and code modernization. Retire IDMS databases and
create an enterprise data model, create a modern development
environment to increase developer efficiency, and retire COBOL in
favor of modern languages. Establish policies and procedures for
operating a cloud computing infrastructure. Design several
development, test, and product subsystems. Create a strategy for
migrating legacy applications as appropriate. Initiatives will reduce
technical debt.

*Team:*
1x Technical Program Manager/SRE
1x Product Manager
1x Data scientist
1x Senior SWE

*Contact:* Charles Worthington, cworthington@omb.eop.gov

*Last updated:* 2015-09-25

## Social Security Administration: Notice Modernization

*Mission:* Update our legacy notice architecture and eventually phase
out the aging back-end processing systems that trigger the creation of
personalized notices in favor of template driven notices based on
events in customers’ lives. Enable 508 compliant online notices.

*Team:*
1x Product Manager
1x Data scientist
1x SWE

*Contact:* Charles Worthington, cworthington@omb.eop.gov

*Last updated:* 2015-09-25

## Social Security Administration: Death Data Analysis

*Mission:* Develop a system to retrieve and collate death data from
external sources in order to make the SSA Enumeration Data more
valuable across the Government.

*Background:* The SSA Enumeration database stores accurate death data
for persons who are receiving SSA benefits and approximate data for
others. We have been requested by OMB to upgrade the database to store
accurate data for all persons in support of the missions of several
other agencies. The plan is to find other new, outside, sources of
death data and use data science to find the most accurate reporting.

*Justification*: A more accurate Enumeration database provides the
basis for decisions across the Government, so one project helps
multiple agencies. The key expertise required, a data scientist, is
not in high demand across the other projects on the USDS Master
list. As a result, this has a high-ROI with little impact on competing
projects.

*Team:*
1x Product Manager
1x Data scientist

*Contact:* Charles Worthington, cworthington@omb.eop.gov

*Last updated:* 2015-09-25


## Internal Revenue Service: Income Verification and Third Party Services

*Mission:* Create an API that would allow a client (ex: bank) to run
an income-verification check for a taxpayer in realtime. Will require
supporting the IRS authorization framework and systems to provision
and authenticate access to the API. Ensure the services created can be
used for future third party services that require authorized access to
taxpayer data. Sample services: Get Transcript API; tax compliance
check for federal agency employment.

*Justification:* The first client for the Income Verification API would
be SBA. Income Verification is currently handled via a paper-based
process that requires 7-10 business days to complete and employs a
large staff to manually verify, access, and upload PDF copies of a full
taxpayer transcript in order to provide a single data element to the
requesting bank. An automated system not only improves the customer
experience but will allow lenders to make more informed decisions and
offer improved services/rates to their customers.

*Cost to reach hull speed:* 3 FTE.  2x Backend Engineer, 1x Product Manager.

*Contact:* Kim Rachmeler, Kimberly_A_Rachmeler@omb.eop.gov

*Last updated:* 2015-11-18

## Internal Revenue Service: Portal Integration and irs.gov Relaunch

*Mission:* Architect how a new CMS would serve static content for all
of irs.gov and integrate with the existing portal infrastructure. Aid
in the procurement of the new CMS to ensure the product can support
modern best practices (ex: responsive page designs; APIs to access
published content).

*Cost to reach hull speed:* 2.5 FTE.  1x Technical Project
 Manager, 0.5x Backend/Web SWE, 1x Procurement/Contract Specialist.

*Contact:* Kim Rachmeler, Kimberly_A_Rachmeler@omb.eop.gov

*Last updated:* 2015-11-18

## Acquisition Best Practices/Plays

*Mission:* To create the Digital Service Acquisition best practices
for use by Procurement Officials. This includes templates for RFQs,
Past Performance guidelines, Agile Framework documents, Case Studys,
etc.

*Success Defined by:*
- Publishing these guides/templates on a knowledge portal or a digital
  service page
- Use by agencies when conducting digital service acquisitions

*Team:*
4x Procurement Advisors

*Contact:* Traci Walker, twalker@omb.eop.gov

*Last updated:* 2015-09-18

## Creation of an 1102 Technical Job Series

*Mission:* Creation of a specialization job series for Contracting
Professionals (and others) in the Fedeeral Hiring authorities to allow
the Government to train Contracting Officers in IT.

*Success Defined by:*
- Working with OPM to define the requirements for the job series
- Getting the authority created for this position

*Team:*
2x Procurement Advisor
1 x Policy

*Contact:* Traci Walker, twalker@omb.eop.gov

*Last updated:* 2015-09-18

## National Aeronautics and Space Administration: Grant Management

*Mission:* Review and update the NSPIRES and RAPTURE systems which
manage research announcements and peer review of grant proposals.

*Cost to reach hull speed:* TBD.

*Contact:* Mikey Dickerson, mdickerson@omb.eop.gov

*Last updated:* 2015-11-01

## National Aeronautics and Space Administration: Open Data

*Mission:* Make NASA's mission and business data universally
accessible and useful.  Take inventory of data scattered across the
agency, and build or enable analytics that make data mining easier.
Examine mission data, currently all in different mission-specific
formats, and create an architecture that allows discovery and
interoperability of these data sets.

*Cost to reach hull speed:* TBD.

*Contact:* Mikey Dickerson, mdickerson@omb.eop.gov

*Last updated:* 2015-11-01

## DHS: NPPD TIC/Einstein/CDM Discovery Sprint

*Mission:* Conduct a discovery sprint to determine what (if any) USDS
involvement is appropriate in supporting DHS's cybersecurity products.

*Cost to reach hull speed:* 4 FTE. 1x PM, 2x Eng, 1x Designer (2 week
 sprint)

*Contact:* Eric Hysen, Eric.Hysen@hq.dhs.gov

*Last updated:* 2015-12-01

## DHS: FEMA National Flood Insurance Program (NFIP) Discovery Sprint

*Mission:* Conduct a discovery sprint to determine what (if any) USDS
involvement is appropriate in supporting modernization of the National
Flood Insurance Program. USDS involvement in this project was discussed
at the recent DHS FedStat session with Beth and Tony.

*Cost to reach hull speed:* 4 FTE. 1x PM, 2x Eng, 1x Designer (2 week
 sprint)

*Contact:* Eric Hysen, Eric.Hysen@hq.dhs.gov

*Last updated:* 2015-12-01

## DHS: ICE Student and Exchange Visitor Information System (SEVIS) Discovery Sprint

*Mission:* Conduct a discovery sprint to determine what (if any) USDS
involvement is appropriate in supporting SEVIS. USDS involvement in
this project was discussed at the recent DHS FedStat session with Beth
and Tony.

*Cost to reach hull speed:* 4 FTE. 1x PM, 2x Eng, 1x Designer (2 week
 sprint)

*Contact:* Eric Hysen, Eric.Hysen@hq.dhs.gov

*Last updated:* 2015-12-01

## DHS: USCIS ELIS Development Team

*Mission:* Create a federal development team to work alongside
contract teams on ELIS and demonstrate best practices to contract and
federal staff.  Improve development processes, including implementing
a peer code review process and improving automated testing. This team
could also work to genericize parts of the ELIS codebase for use in
other projects (ie TSA TIM).

*Cost to reach hull speed:*  
2x Senior Delivery SWE Open  
5x Junior Delivery SWE Open  

*Contact:* Eric Hysen, Eric.Hysen@hq.dhs.gov

*Last updated:* 2015-12-01

## Police Data Initiative: Better community policing through data.

*Prerequisite:* DoJ discovery sprint, which is completed.  Report and
memo with DoJ recommendations to be completed by Kim/Viv and reviewed
by EOP Digital Council.

*Mission:* Make policing data open, available, useful, and
understandable.  Our modern democracy requires trust between
communities and their police.  Better, more open data can foster trust
and efficacy.  PDI will accomplish this by managing the building of
open tools for communities and police departments to collect, manage,
and analyze police data.  Provide a central data common for
aggregating data, and do some analytics on that data common.  This
project announced by the President in Camden, New Jersey was started
by two Presidential Innovation Fellows and has mobilized 24 leading
jurisdictions across the country, bringing police leaders together
with top technologists, researchers, data scientists, and design
experts to use data and technology to improve community trust and
enable a shift towards data-driven community policing. PDI is centered
around two key components: (1) increasing transparency so communities
have clear visibility into police actions in their neighborhoods, and
(2) using data science and technology to analyze data on
police/citizen encounters to help police departments identify officers
having problems early and provide them with training and supervision
to decrease inappropriate uses of force.

*Near-term deliverables:*

+ Infrastructure. Continue to build infrastructure, with philanthropic
and NGO support, to scale the data initiatives of PDI, including
a central portal for open police data and the development of
technology tools to help police departments extract and share their
data. A number of jurisdictions already have begun to put their
data online through their central portals.

+ Data science tools and training strategies. Through commitments
from academia, rapidly prototype and evaluate a predictive analytics
tool that can identify police behaviors most likely to lead to
negative police/citizen encounters, and identify effective training
intervention strategies.

+ Video analytics tools. Work with leading researchers to help
police departments create and deploy tools to help analyze body
worn camera footage and assess which police behaviors are most
likely to lead to negative police/citizen encounters.

+ Data discrimination. Issue a White House report about the risks of
algorithmic and data discrimination as a follow on to the
Administration’s Big Data report.

*Team:*  
1x Gov Hacker Open (Denise)  
1x Lead Lynn Overmann (OSTP)  
0.25x Data DJ Patil (OSTP)  
1x PM Open (Clarence?)  
1x SWE Open  

*Contact:* Vivian Graubard, vgraubard@omb.eop.gov

*Last updated:* 2015-11-01

## VA/DoD/PMI: Identify a strategy for a data management platform and for health data analytics.

*Mission:* DoD and VA have both requested help them with analytics-
both with the technology and governance needed, and with the data
science.  This problem is also widespread across the industry.  A
third of all Americans receive less than the standard of care when
they interact with the healthcare system.  Also, 10-25% of costs can
typically be taken out of a healthcare system, through data-driven
choices, reducing duplicate tests, and better standardized processes
based on data.

This project will identify the approach and strategy for building
analytics tools and a core competency at a system, in a concrete way.
It is likely that this project and team may roll-over into
implementation of such a strategy.

*Success Criteria include:*

+ An efficient analysis of needs at DoD and VA for analytics, data
  sources, existing tools

+ Analysis of Alternatives for existing market solutions,
  implementations

+ Strategic plan for execution, who will execute TBD

*Team:*  
0.5x SWE Backend with data systems expertise Open  
1x health data analytics expert Open  
0.5x Data architect Open  
0.5x Product manager Open  

*Contact:* Mina Hsiang, mina_k_hsiang@omb.eop.gov

*Last updated:* 2015-09-23

## Office of Personnel Management: Systems review and audit

*Mission:* Evaluate OPM network security posture in general.  Examine
transactional and data-warehouse applications one by one for
reliability or security concerns.  There are many such systems (a few
dozen at least), but the OPM CIO (Donna) has prioritized the list.

At present, OPM will rely on its own staff, to include a security
advisor to the Administrator to be hired.  USDS continues to work with
NSC and others via the "blue sky" security group to improve
cross-government support for agency security.

*Cost to reach hull speed:* 2x security specialists, or backend
engineers with relevant experience.

*Contact:* Mikey Dickerson, mdickerson@omb.eop.gov

*Last updated:* 2015-11-01

## DHS: ICE Enforcement Integrated Database

*Mission:* Continue the work of the Immigration Statistics Project to
enable DHS to automatically report on immigration enforcement based
on the Priority Enforcement Program. Work at OIS revealed that underlying
data problems at ICE must be addressed before DHS-wide data can be
automated.

*Contact:* Eric Hysen, Eric.Hysen@hq.dhs.gov

*Last updated:* 2015-12-01

## Executive Office of the President: WhiteHouse.gov Infrastructure Review

*Mission:* Have a fresh set of eyes review the infrastructure behind
WhiteHouse.gov and make a series of recommendations to bring it in
line with current industry best practices.  WhiteHouse.gov has been
managed by Acquia since 2009 when a sole source contract was issued
with strong justification based on their knowledge of Drupal and the
ability to provide hosting. The site is fully managed by Acquia (who
sub-contracts some of the work) and is hosted within their environment
on Amazon Web Services behind Akamai. There have been recent security
issues on the site from old Adobe Flash players and an increased
external interest. The incident response processes in place did not
feel robust which and suggests that we need to look deeper into how
the site is managed. Further, the readout from a recent meeting with
Akamai suggests that they not being utilized to their full capacity as
would be the case in the private sector.  With ODS hiring their first
Director of Product, and WH IT hiring our first Chief Information
Security Officer, and the person responsible for this leaving OA, this
feels like the right time to ask USDS for help.

*Note: I'd suggest carving this out as a short term few week project
in the style which rapid response is being discussed. From a skills
perspective, I believe that Tom Cook would be one great person on the
team given that he managed Dropbox’s AWS environment and a large scale
PHP (which Drupal is built in) hosting environment while at Facebook.*

*Team:*  
1x SRE/Backend

*Contact:* David Recordon, David_B_Recordon@who.eop.gov

*Last updated:* 2015-09-26

## Dept. of Justice: Controlled Equipment Database/21st Century Policing

*Dependency: Should complete DoJ discovery sprint first. (Done.)*

*Mission:* Support President's task force on policing and law
enforcement, which seeks to increase data collection on controlled
equipment, as it relates to militarization of police departmens.
Contribute to place-based partnership between OSTP and Code for
America.

*Cost to reach hull speed:* TBD after discovery sprint.

*Contact:* Vivian Graubard, vgraubard@omb.eop.gov

*Last updated:* 2015-11-01

## Dept. of Justice: Criminal Records Dispositions

*Dependency: Should complete DoJ discovery sprint first. (Done.)*

*Mission:* Reduce the population of open arrest records that are
missing their disposition, which currently stands at 94 million.
Non-disposed arrest records, and inaccurate criminal records
generally, are likely to cause the individual to fail a background
check for employment, state licenses of various types, citizenship,
or firearms.

*Cost to reach hull speed:* TBD after discovery sprint.

*Contact:* Vivian Graubard, vgraubard@omb.eop.gov

*Last updated:* 2015-11-01

## Dept. State and Dept. of Homeland Security: Refugee Admissions

*Mission:* Follow up on sprint report by staffing a small team to drive
implementation of process and technology reforms in the US. Refugee
Admissions Program in order to hit aggressively increased admissions
targets in FY16 and FY17. Work will include increasing the technical
capacity of the WRAPS system at State and the CAMINO system at DHS in
order to serve as effective case and workflow management tools,
driving interagency collaboration to streamline time-intensive paper
handoffs, and directing an outside process engineering consultant in
developing a detailed process model and clear SLAs.

*Success:* The US Refugee Admissions Program hits its admissions targets
for FY16 and FY17.  

*Team:*  
1x PM Open (State or DHS, Overall Lead)  
1x SWE Open (State, Working with WRAPS)  
1x SWE Open (State, Working with WRAPS)  
1x Data Scientist Open (State)  
1x SWE Open (DHS, Working with CAMINO)  
1x SWE/PM Open (DHS, Working across projects)  

*Contact:* Eric Hysen, eric.hysen@hq.dhs.gov

*Last updated:* 2015-11-16

# Completed projects

## Dept. of Justice: Discovery Sprint

*Mission:* Conduct a 4-5 person, 2 week discovery sprint that we have
used to gain clarity on possible DoJ projects, in the same model as
has been useful at DHS, Ed, etc.  A prerequisite to any other DoJ
projects.  Skipping the discovery phase would increase the risk of
misallocating staff or choosing the wrong goals.

*Team:*  
1x Eng/Lead Kim Rachmeler (USDS HQ)  
1x PM Viv Graubard (USDS HQ)  
1x Dev Infra Eng Chuck Rossi (USDS HQ)  
1x Data/Backend Eng David Nesting (USDS HQ)  

*Completed:* Full report delivered to Roy Austin and DoJ contacts so far.

*Contact:* Kim Rachmiler, kimberly_a_rachmeler@omb.eop.gov

*Last updated:* 2015-07-24

## Dept. of Justice: Universal Crime Reporting

*Dependency: Should complete DoJ discovery sprint first. (Done.)*

*Mission:* Drive adoption of NIBRS (National Incident-Based Reporting
System), a 27-year-old mandate that will improve fidelity of crime
statistics but has poor adoption.  Identify likely state and local
LEAs that are high value and can be moved to NIBRS.  Figure out a
strategy for how to address the other tens of thousands of LEAs.
Likely opportunity to partner with Code for America.  Move past
hand-reported summary crime statistics.

*Complete:* USDS conducted a NIBRS-focused discovery sprint in summer
2015, then decided to prioritize NICS for future effort.  Contact Viv
or Kim Rachmeler for the sprint report.

*Contact:* Vivian Graubard, vgraubard@omb.eop.gov

*Last updated:* 2015-11-01

## Office of Personnel Management: Notification Web Page

*Mission:* Make sure that the informational website regarding the OPM
breach will be reliable in the face of the expected traffic spike and
help OPM create content that is clear and actionable for individuals
affected by the two breaches.

*Team:*  
1x Design Mollie Ruskin (USDS HQ)  
1x SRE/SWE David Chang (USDS HQ)  

*Completed:*
The web team was technically compotent and able to execute - the proposed
plan of using Akamai Netstorage was identical to USDS ideal solution.
Content was a much more difficult task - the master song sheet was not
finalized until the last minute and the resulting language was not consumer
facing which required a significant overnight rewrite.

For more information, see the
[after action report](../engagements/opm/website-after-action.md)

*Contact:* David Chang, liyan_d_chang@omb.eop.gov

*Last updated:* 2015-09-15

## Office of Personnel Management: e-Quip Return to Service

*Mission:* Safely restore e-QIP to service. OPM had removed e-QIP from
service in the wake of OPM security incidents. Most federal hiring
ground to a halt.

*Team:*  
1x SRE/Lead Matt Weaver (DS at VA)  
1x SRE/SWE Alex Gaynor (DS at VA)  
1x SRE/SWE Andy Nacin (USDS HQ)  
1x SRE/SWE Margaret McKenna (USDS HQ)  
1x SWE/Neteng Evan Cooke (USDS HQ)  

*Completed:* The team restored e-QIP to service in a matter of
weeks. Original estimates of service restoration measured in
months. The team worked in concert with OPM, e-QIP contractors, NSA,
DoD, and DHS/CERT. The team established a minimal perimeter around the
system, helped fix bugs and address concerns.

A full after-action report is [here](../engagements/opm/201507-CY/after-action-20150716.md).

*Contact:* Matthew Weaver, matthew.weaver2@va.gov

*Last updated:* 2015-09-17

## Dept. of State: Consular Consolidated Database Return to Service

*Mission:* Assist State in bringing the CCD system back online. A
critical database has been destroyed and recovery efforts are
underway. Visa application processing has been put on hold until this
is remedied.

*Team:*  
1x SRE/Lead Eric Maland (USDS HQ)  
1x SRE/SWE Nick Lesiecki (USDS HQ)  
1x PM Viv Graubard (USDS HQ)  

*Completed:* System brought back online weeks after engagement
began. The database was recovered from a much older copy and
supplemented by data stored locally. We made recommendations for how
State should maintain this critical system going forward.

*Contact:* Viv Graubard, vgraubard@omb.eop.gov

*Last updated:* 2015-09-15

## Office of U.S. Trade Representative: TPP Web Site Launch

*Mission:* Evaluate launch plan and serving capacity for USTR's
upcoming static web site hosing Trans-Pacific Partnership trade
agreements.  Recommend any necessary changes.

*Team:*  
1x SRE/SWE David Chang (USDS HQ)  

*Completed:* Conclusion was that USTR.gov would not be able to scale easily
but could handle the traffic. USTR.gov is hosted on Max.gov - a single VM
running Drupal. It had been fronted by Cloudflare, but the use of SNI
on the free plan means that they turned it off as it was not supported by
Windows XP. Traffic was expected to be within range of the machine - further
validation of this was never completed as the trade agreement stalled and
no impetus for a traffic spike.

*Contact:* Mikey Dickerson, mdickerson@omb.eop.gov

*Last updated:* 2015-09-15

## Dept. of Homeland Security: Immigration Statistics/Enforcement Priorities

*Mission:* Enable the DHS Office of Immigration Statistics to deliver
accurate reports on the President's executive actions on immigration.
Prior to USDS engagement, OIS had just 2 staff out of a prior size of 17
and was reliant on manual data requests from DHS components. Explore
automation of data collection and processing.

*Team:*  
1x SWE Nadav Zimak  
1x SWE Margaret McKenna  
1x PM David Chang  

*Completed:* OIS now delivers the monthly internal EIR report regularly
with accurate data and is less reliant on manual data collections and
processing. We also created a proof-of-concept data warehouse in AWS
that shows a new model for data collection and aggregation is possible,
and worked with DHS Immigration and Customs Enforcement (ICE) on a plan
to make their data compatible with such a system going forward. USDS
will continue to provide ad-hoc consulting support to OIS, likely in
advance of major report deadlines.  

*Contact:* Eric Hysen, Eric.Hysen@hq.dhs.gov

*Last updated:* 2015-09-03  

## SBA Digital Service Acquisition

*Mission:* Support the development of a Request for Quote and the
acquisition for services to support the Digital Service plan as
defined in the Report delivered to SBA following the Discovery Sprint.

*Team:*
2x Procurement: Jonathan Mostowski, Traci Walker

*Completed:* Acquisition was conducted and completed in 3.5 months
with Kick off in July and a Product Manager identified.

`TODO(Traci): How do we know the RFQ was better because of our involvement?`

*Contact:* Traci Walker, twalker@omb.eop.gov

*Last updated:* 2015-09-17

## Recreation.Gov Acquisition

*Mission:* Support USDA/DOI in their joint agency acquisition for the
Recreation.gov website and support service contract. Includes defining
requirements, acquisition strategy, and technical consultation.

*Team:*  
1 x Procurement Advisor Traci Walker (USDS HQ)  
0.2 x Technical Lead Charles Worthington (USDS HQ)  

*Completed:* DOI released the Request for Quote on FedbizOps August 2015

`TODO(Traci): How do we know the RFQ was better because of our involvement?`

*Contact:* Traci Walker, twalker@omb.eop.gov

*Last updated:* 2015-09-17

## Dept. of Defense: Defense Travel System

*Mission:* Complete a 2 week sprint on DOD Defense Travel System
recommendation 3: Invest in Data Science. Spend time with Defense
Travel Management Office to understand how they use data and how
they'd like to use data.

*1 Week Sprint Team on Recommendation 3: Invest in Data*  
1x Acq Jonathan Mostowski (USDS HQ)  
1x Data Dav Zimak (USDS HQ)  
1x SWE David Chang (USDS HQ)  
1x Policy Mary Lazerri (USDS HQ)  
1x Policy Lucy Brady (USDS HQ)  

*Completed:* Delivered a
[report and presentation](../discovery-sprints/Defense/DTMO-09-2015/)
to the Undersecretary of Defense on Personnel & Readiness Brad Carson
on September 30, 2015.

*Contact:* Jonathan Mostowski, jmostowski@omb.eop.gov

*Last updated:* 2015-11-02

## Dept. of Veterans Affairs: Spinal Cord Injury [Interim] Application

*Mission:* Build an application for the Spinal Cord Injury (SCI)
Centers. This application will replace both a poorly regarded
vendor-developed tool (SCIDO) that is minimally used and a menagerie
of spreadsheets. The application will support improved patient care,
population health analytics, and operations/management. In addition,
since SCIDO will be sunsetted in October, this application will
provide a solution to short-term patient data management. More
importantly, this will lay the foundation of requirements and
relationships required to start work on the main eHMP project, which
will affect the entire VA's electronic health record system. The
design and requirements from this application will be the foundation
to building the first application using the SDK to demonstrate the
capabilities of eHMP as a platform.

*Team:*  
1x PM Kathy Pham  
1x SWE Albert Wong (DS at VA in Seattle)  
1x Design - Usability Craig Harrington (DS at VA)  
1x Frontend / Design Emily Wright-Moore (DS at VA)  

*Completed:* TODO(Marina)

*Contact:* Albert Wong, albert.wong@va.gov

*Last updated:* 2015-10-17

## Internal Revenue Service: Discovery Sprint

*Mission:* Conduct a 3-4 person, 2 week discovery sprint that will be
used to gain clarity on possible IRS projects, in the same model as
has been useful at DHS, Ed, etc. A prerequisite to any other IRS
projects. Skipping the discovery phase would increase the risk of
misallocating staff, choosing the wrong goals, or failing to secure
support from IRS IT organization. This sprint will focus on the Identity
Management project.

Currently expected to launch in October 2015.  The USDS team is ready;
we are waiting for an appropriate moment to engage with the rest of
the agency on identity management.  Part-time consulting to help with
Event Driven Architecture is already underway.

*Team:*  
1x Agency Lead Kim Rachmeler (USDS HQ)  
1x PM/Lead Ben Getson (IRS)  
1x SWE David Chang (USDS HQ)  
1x Policy/Inception Mary Lazzeri (USDS HQ)  
1x Design Jess Teal (USDS HQ)  
1x Connect.gov SWE/PM LaChelle LeVan (GSA)

*Completed:* Reported to IRS Commissioner and executive team on Oct
30, 2015 with a [report](../discovery-sprints/IRS/USDS%20IRS%20Discovery%20Sprint%20Report%20v1.1.pdf)
and [presentation](../discovery-sprints/IRS/USDS%20IRS%20Discovery%20Sprint%20Presentation.pdf)

*Contact:* Kim Rachmeler, Kimberly_A_Rachmeler@omb.eop.gov

*Last updated:* 2015-11-02

## Dept. of Homeland Security and Dept. of State: Refugee Sprint

*Mission:* To create a report by Nov. 1st that makes short and
long-term recommendations for improving the refugee admissions
program. It will be important to understand the application process,
the underlying applicant data to pinpoint where people are in the
process and where they get bottlenecked, and the way the multiple
agencies involved in administering the application process overlap and
intersect.

*Success:* Drafting a report that articulates the short and long-term
improvements that could be implemented to the refugee application
process. Short-term improvements should focus on how we can save time
over FY 16 and FY 17 to admit more refugees, per the President's
commitment. Deadline for the report is Nov. 1st.

*Team:*  
1x Policy Open  
1x Data Open  
1x SWE Open  
1x SWE Andrew Nacin  
1x Policy Mary Lazzeri  
0.5x Policy Raphael Majma  
1x Policy Emily Tavoulareas  
1x Hysen Eric Hysen  

*Completed:* TODO(Hysen)

*Contact:* Eric Hysen, eric.hysen@hq.dhs.gov

*Last updated:* 2015-11-05

## Integrated Acquisitions Environment/SAM.gov Discovery Sprint

*Mission:* The goal of the IAE project is to integrate 10+ different systems that are central to the procurement process to create an streamlined, easier to use tool for the full lifecycle of procurement: from helping companies register for work with government and finding business opportunities, to reporting contract awards and performance.  The IAE project and overhaul of SAM.gov is critical towards the goals of lowering barriers for the right companies to do business with government and improving our governments procurement process. 

*Justification:* Following a failed revamp of SAM.gov, the IAE team is in the third year of hard work attempting to move the project to an agile process. The project has hit many unanticipated set backs, and the team is moving towards a launch in early 2016 pulling the first systems into the new “integrated acquisitions environment” (which is on track to still be called SAM.gov publically). GSA Leadership and the IAE Team is eager to have the USDS team do a 2-week assessment of the architecture, user experience, and devops as they prepare for the launch. There are currently over 17million transactions a year on SAM.gov, and roughly 30K announcements a day on FedBizOps.gov—two of the first systems to be impacted. 

*Team:*  
1x Product Manager/Or Procurement Lead (Traci?)
1x Procurement Specalist  (Jonathan?)
1x SWE (open)
1x Design (open)

*Contact:* Haley Van Dyck

*Last updated:* 2015-11-30