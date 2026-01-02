# Securing Open Source Communities Work Group

Hello and welcome to the work group! We are excited that you are
interested in what we're trying to accomplish to help open source
communities thrive.

> The following will be edited to an agreed upon state in the
> first sessions of the working group. After that point this block
> of text will be removed.

## Context, goals, how to join

### Quick explainer

Open source projects and organizations are experiencing an increase in
crisis events and stressful situations. I spent the last quarter of 2025
researching publicly available data around this trend, and noticed that
it started around 2014. I presented my research and recommendations at
the 39th Chaos Congress, which also highlights the urgency of addressing
these vulnerabilities:

[How to keep Open Source open without leaving our communities open to threats](https://media.ccc.de/v/39c3-how-to-keep-open-source-open-without-leaving-our-communities-open-to-threats) 

As a result of my findings, and the pervasiveness of them, I am also
spinning up a working group so we can work together to address these
issues. The two goals are:

*   Develop and community-test communication norms for managing social
    crises and security events.
*   Create guidance on how and where to create responsible friction
    within common governance and contributor patterns.

For a deeper dive into how we will be accomplishing these, please read on.

If you are interested in joining the working group, please reach out to Quintessence.
Once you join, you can be added to the CONTRIBUTORS file.


## Deeper Dive into the Two Phases

There are two phases to this work. First to establish, and publish
recommendations, for commuications standards for open source. The
second is to threat model and abuse test common open source
frameworks, using the communications guideance for internal and
public communication.

### Phase 1: Communications Standards

We need standardized communication practices in open source. It is
our belief that lack of this has led to some failure modes:

* When leadership doesn't know what to communicate, there is the
  stress of over/under communicating important information.
  *  For communities, this results in confusion from either too much
     of the wrong information or too little of the right
     information.
  * For leadership, this can lead to internal choas as different
    members, and different leadership bodies, do not know 1 ) what
    to disclose, 2 ) to whom, and 3 ) with what balance.

#### Scope

**In scope**

* Developing a decision framework for governance communications
* Adapting existing protocols (e.g. CISA TLP) for OSS
  communiction contexts
* Utilizing examples of successful and unsuccessful communication
  patterns to guide our work.
* Creating and publishing guidance for open source projects that
  are accessible to projects, even if they dont't have dedicated
  communications staff.

**Out of scope**

* Platform specific tooling recommendations or implementation
* More general forms of project marketing and/or community
  management
* Crisis response procedures
  * This is focusing on _how to communicate_, not _what to do_.
* Legal communications guidance

#### Deliverables

* Published communications norm guidance in the public domain
  * With agreed upon license, the default license here will be
    used if no other is agreed upon.
  * The guidance will include a decision framework
  * Adaption of TLP for OSS governance contexts
  * Templates and/or checklists for common scenarios

#### Work and timeline

**Meetings**

* To decide: weekly or bi-weekly meetings
* Schedule will be polled in inaugural session
* Notes / Minutes to be published
  * Applying our own initial norm: TLP:CLEAR by default.

**Communication**

* Primarily async in Matrix room
* Artifacts on Github and in Markdown
* Sensitive discussions to be flagged in advance
  * Applying our own norm: TLP:AMBER or higher will be assigned to
    these

**Participation**

* Seeking people who have some combination of:
  * Direct experience handling governance crisis and can speak to
    what did and did not work
  * Those already familiar with using TLP or similar frameworks
    for communications.
* Once drafts are created, also seeking:
  * People who can review drafts for clarity and broad
    accessibility, including ensuring that the document is
    accessible for use for volunteers and non-security
    specialists.
* To decide: preferred acknowledgement in final document.

**Decision-making**

* Rough consensus
* All amendments to core documents require explicit confirmation
  in async channel.
  * Core documents: any document that changes scope or
    deliverables.

**Estimated timeline for this project**

3-4 months, assuming the above.

### Phase 2: Abusability Testing and Threat Modeling OSS

Open source communities need to be able to proactively identify
and address governance and contributor vulnerabilities before they
are exploited, through shared frameworks for abusability testing
and threat modeling of these structures.

#### Scope

**In scope**

* Develop threat models for common open source governance
  structures
* Create abusability testing methodologies for community policies
  and processes
* Producing guidance for maintainers and leadership in OSS
* Collaboration with existing, relevant, security efforts
*
**Out of scope**

* Code security, supply chain security, or vulnerability
  disclosures
  * There are existing groups for these
  * Collaboration with these groups where we overlap is
  * recommended
* Incident response for an active crisis
  * This is about _how to notice_, not _what to do_
* Specific tooling or implementations
* Providing specific guidance to specific projects
* Legal advice

#### Deliverables

Each of these will be reviewed and clarified at the start of Phase
2 work.

* Foundational work
  * Agreed upon charter with input from Phase 1 work
  * Governance threat taxonomy
  * Review data / prior art survey
* Framework Development
  * Use abusability testing methodoly to guide<br />
    i.e. mock "stress test" of governance structures
  * Use working examples to apply to common structures
* Testing and Outreach
  * Pilot with volunteer projects
  * Discuss the outcomes in conferneces, blog posts, etc.
  * Recommendations for integration with existing frameworks

#### Work and timeline

Meetings, comms patterns, participation et al will be decided toward the
conclusion of Phase 1 as the group prepares to transition to Phase 2.
