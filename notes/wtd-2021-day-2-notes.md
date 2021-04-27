---
title: WTD PDX 2021: Day 2 Notes
tags: [WTD]
---

# Write the Docs PDX 2021: Main Stage, Day 2

Applause, gratitude, and every other manner of thanks go out to the WTD organizers for a resounding success on day one of the main stage. This is my first all-digital conference, and despite the obvious drawbacks to not being in the same room together, it felt like WTD. And that's the most important part.

Day two kicked off with a talk I hadn't noticed when the presenters list went live earlier this year. Laura Novich on documentation communities. Not something we're actively exploring at my job, but something I'd love to see implemented in the future.

## Documentation Communities: Sound Strategy or Documentarian's Gambit: Laura Novich (@ScyllaDB)

- Company moved from closed to open source docs. Examples of big OS companies like Gitlab, MS, Docker, Github, etc.
- Biggest challenge at the time was to get the devs to write docs
- Docs were in one repository, and were closed, meaning no community.
- Did have management knowing value of docs, training referring to docs, users of docs who opened support tix for doc issues, etc. Engagement!
- Wanted total commitment, version selection, more contributors, maintainers to have responsibility, automation
- Missed style guide and governance, a single source of truth, total buy in (including C Suite), a reward system, a higher view of the way to manage content and prevent duplication
- Challenge was constant release schedule, quality of docs, big fixes
- To combat concerns of no contribution/engagement, need to make a predictable structure, easy to add, self-service before checking-in, rewards at all levels of contribution!
- "Create a Docs Franchise" meaning every `/docs` directory should have the same structure; allows visibility into reuse.
- Add simple buttons for contributions, like `Documentation` button or `Easy Fix` or whatever. Every docs repo has a .readme; and an explanation of how to contribute to the docs; use git tags for docs (like helpwanted or fix tags); a Slack channel just for docs.
- Review with care: answer all contr. comms, timely nature, do in-line review with GH tools; constructive criticism and be kind/supportive; never assume contr. know all that you do; thank them as always
- Find friends of the docs, build bridges, make docs early in dev cycle, make docs part of feature dev and definition of "done."
- C Suite on board requires analytics, ROI, headcount (community contributors help keep employee numbers low), pilot projects if still not convinced.
- Rewarding contributors should be meaningful, personal, consistent, global, tiered. (Example of MVD: Most valuable documenter; after a year, look at most consistent contributor and they get a t-shirt award at their yearly conference; rotating design)
- Toolchain: Written in ReTxt/MD; test with Vale linter; Sphinx; issues reported with GitHub; hosted on GH Pages
- Sphinx overview and why chose it.
- All projects use one Sphinx theme.
- Challenges still lack of visibility on which content is in which repository and full reuse. Need a CCMS; which would help with training and marketing

## Building a Style Guide from the Ground Up: Lessons Learned from a Lone Writer: Deanna Thompson (@Tech Elevator)

- Do a gap analysis; focus on design, WC, structure, etc.
- Good docs project as an example -- ask them for a style template
- They started on Google Dev Guide and realized needs differ and wanted to add something to compliment Google's.
- Get buy in early, hold planning meetings regularly
- Build the guide with tools you already have
- Be kind to yourself and ask for help when workloads are excessive

## Almost None to Some: Driving DISQO's Doc Culture as a Solo Documentarian: Falon Darville (@DISQO)

- Finding comfort in incompleteness. Love this, reiterating, in a different context, from yday's talk by Daniele Procida.
- Another comparison like Daniele's, "Documentation is an organism."
- The act of documentation is description rather than limiting products or projects
- Prescription, as in prescriptive linguistics, piuts limits on documentation growing organically
- Controversial to our org: Comfort in incompleteness means using templates, acknowledge no immediate visibility over content, accept that errors in spelling and grammar may occur
- Unhelpful: I work towards perfect documentation v. Comfort motto: I work toward good enough documentation
- Influence others, provide immediate values, join Scrum ceremonies, join release channels, announce doc deployments, create surveys for anonymous doc feedback; blog about org's documentation (gain more exposure and visibility)
- Unhelpful: I force people to see how important documentation is v. Influence motto: I empower others to take responsibility for documentation
- Training materials for DAC toolchains, etc. Give onboarding to others.
- Key partnerships with friends of the docs!
- Find an ally per job title (as relevant), ie Engg with troubleshooting, PM with client needs in mind, Manager to see bigger org picture
- Formed a Tech Doc Guild to do a monthly meeting with key doc partners across org and those doing docs.
- For lone writers, be a presence and face in social events in the org; and not just doing tech docs in the org; ie do work for a ERG.
- Unhelpful: I'm a background player v. Empower: I'm a key member of my organization

## Is a Tech Writer a Tester, and Vice Versa, Is a Tester a Tech Writer?: Ines Stefanovic (@IBM)

- Listened, but mostly worked on my blog post. Sorry Ines! I'm coming back to your presentation when posted next week.

## Lightning Talks

- Ryan Macklin, 5 Things Game Design Taught me About Tech Writing
  - Former tabletop designer
  - Write instructions that sell products.
  - Layout has power; visual associations and print designs
  - Intermix context channels: instructions, examples, commentary; find multiple channels to explain the same material
  - Avoid bombarding with help: assume people are smart, separate the deeper help from those who need the quick push
  - Information architecture!
  - Accessibility! Designing for it makes all content better.
  - Use UX research for small budgets and compressed timelines.

- Kathryn Elliott, Content Experience Checklist
  - Part of content strategy tool framework at Microsoft
  - Suite of tools: Audience Analysis, Content Goals, Content Experience Checklist, Content Assessment, Content Execution Plan.

## Writing Documentation with Neurodivergent Open Source Contributors in Mind: Rin Oliver (@Camunda)

- Great content; not relevant for current role (b2b enterprise, not OSS) but the general tips on accessible info IS useful for within the org. Mental note to adapt our own internal documentation for accessibility basics and to assume neurodivergent colleagues want to be involved in doc activities but not likely encouraged or felt able to.

## Invisible Influence -- The Documentation Behind UX Copy: Katherine Karaus (@Squarespace)

- Good overview of content strategy work in UX terms
- Content strategy toolkit book recommended
- Still specific to UX writers and work vs what I end up doing daily atm.

## Level Up - Onboarding That Enables Writers to Thrive: Nicola Yap (@Google)

- Not a lot of onboarding for TW; content for Engg, Dev, Support, etc. TWs not specific
- Writer role and responsibilities unclear, common across her job roles
- Collab models often exclude writers and doc lifecycle is unclear/undefined, the writing is taken for granted
- Stakeholders unclear
- Career pathing can be affected without the definition early on, and goal setting/impact demonstration affected
- Piloted role education for new writers akin to how Engg/Dev gets educated on responsibilities
- Regional support added later for each geo where writers exist to give consistent experience (teachers, resources, social events for each writer geo)
- Focus now shifting to identify gaps for post-new-hire onboarding for ongoing education and resources for future growth
- Onboarding is a map: context, highlight importance, pathways and resources.
- Core values must be belonging, a community of support, and direction for their future
- What to include. Example: [Google onboarding toolkit](https://github.com/google/opendocs/tree/main/onboarding)
  - Doc input, deliverables
- Audience of who:
  - Users, stakeholders, leadership and org structure that can vary based on which team the writer reports to and works in
- How docs work:
  - Tools, style guide, templates
  - Doc lifecycle
- Career pathing:
  - Role expectations
  - Opportunities for impact
  - Learning and growth
- Establishing practices chart (Training Site Reliability Engineers: What Your Organization Needs to Create a Learning Program, from Google)
- Differences in growth/org size can dictate the level of practice. Smaller orgs can do direct shadowing and mentoring; larger orgs and high growth can have orientation instead, do a full training program with cataloged resources.
- Set onboarding goals of "what a writer should be able to do" IE goals by end of training:
  - Identify their stakeholders and share
  - Describe users of the writer's docs
  - Find a bug they own
  - Publish reviews
- When you have goals, can design the education platform. Will look different based on context and roles and writers and staffing
  - Google does 60m live virtual classes; two facilitators (one for chat monitoring); slide highlights with speaker notes including details; anonymous after class surveys
- Checklists for hires for first week, first month, 3 month laters
- Community of mailing lists, chat rooms for only new writers
- Individual teams with mentors, team specific education beyond onboarding, use of a friction log
  - A log of Y! (green); Eh (yellow); RQ (rage quit) and written as if you're saying it out loud; I did a task, these are the steps, oh this step sucked/was great/mediocre and can help with lightweight discussions or assign bugs from within the doc.
- Fostering a doc culture
  - Include writers in end-to-end processes
  - Shared ownership for significant doc tasks
  - Recognize range of contributions to user success
  - Recognize SME contribs
  - Provide templates and writing guidance to everyone
  - Support a learning culture of investment in training, knowledge sharing, failure is safe.
