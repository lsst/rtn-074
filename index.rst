#######################################
Developing a USDF Outage Planning Board
#######################################

.. abstract::

   We need a body to vet and approve service outages at the USDF. These can originate from S3DF or be internal to USDF. This may evolve into a more general CCB for the USDF and embedded in a group of CCBs across Operations.

Initial Purpose
===============

Collect representatives of the various USDF constituencies to evaluate and then approve outages affecting the USDF. For S3DF outages, this would entail Rubin agreement to proceed; there are other SLAC stakeholders as well.

It would be the responsibility of this group to alert their constituencies of the proposed schedule and impact of outages.

Scope
=====

Schedulable service outages that will require significant downtime, either globally or to specific groups are in scope. Significant is defined as greater than 2 hour disruption. Shorter outages will be handled at the USDF Lead’s discretion (while still ensuring all due negotiations and announcements are done).

As part of the S3DF Steering Committee (of which the USDF Lead is a member), we will be asked to sign off on S3DF-initiated outages. As S3DF is a shared facility, Rubin does not have final say on its outage content and scheduling.
Constituency Representatives

Three key stakeholders have been identified, and representatives proposed.


- Camera: Jim Chiang (TBD Aaron?)
- Campaign Management/Developers: Yusra Al Sayyad (Colin Slater)
- Commissioning: Robert Lupton (Keith Bechtol)



CCB Workflow and Implementation
===============================

The CCB would be driven by JIRA tickets, hopefully with a custom workflow.

Outage ticket is created (by the USDF Lead or delegate), describing the outage, proposed schedule, downtime and anticipated impacts on the USDF
CCB members (and anyone) can comment on the ticket as information is gathered and an outage time is agreed to
CCB members approve the ticket
The USDF Lead has final approval on the ticket.

Communications
==============

The actual approval process would be carried out via the JIRA ticket. Unless unusual circumstances require it, no meetings are envisaged.

Announcements go to #ops-usdf-announce.

Open discussion/planning of the outage go to #ops-usdf-outages (to be created). Perhaps workflow steps in the JIRA ticket (eg creation, final approval, close) could have notifications going to this channel.
