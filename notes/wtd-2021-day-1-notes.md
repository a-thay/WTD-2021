---
title: WTD PDX 2021: Day 1 Notes
tags: [WTD]
---

# Write the Docs PDX 2021: Main Stage, Day 1

## Introduction

- Eric's nervous excitement is endearing as it was in my first conference. I appreciate that year after year the organizers expand and strengthen their commitment to a diverse, welcoming event with proper guardrails to keep things professional and inclusive.

- Interesting to hear about possible paid subscription options for WTD. It was made clear that most of what makes the community great would remain free, but the overhead and operational burden to keep things going while, up until 2020, relying on ticket sales to live events, is proving difficult. An optional, paid user base of dedicated members with the means to help keep the lights on makes sense. And I bet there are enough of us documentarians who appreciate how much WTD means to shell out a fee for goodies and the feeling that we did something to keep WTD around for the foreseeable future.

## Writing a Perfect Technical Tutorial: Jessica Garson (Developer Advocate @ Twitter)

- Why write a tutorial? Why bother? Who will read it?
  - Remember that it's always someone's first time performing a technical action. Want to guide someone through, say, coding and help them be successful and feel the joy of accomplishment like you have first time.
- Benchmark: Can this be easily Googled? No? Write a tutorial! Create content to make lives easier.
- Like any good writing, figure out who your audience is. Is this a company blog, or company docs, Medium, personal site, or a developer community, etc. Tutorials will differ based on output location.
- Questions to ask:
  - What will the reader accomplish from this tutorial?
  - Who am I writing for? (IE scaling the level of technical acumen and code exposure based on beginner to advanced)
  - What's the story? Solved an issue and are excited; or trying to prevent others from making the same mistakes/have same problems as you
- Drafts are the skeleton. (In my experience, and favorite way of saying it, this is the process to make your 'shitty first draft' per the immortal advice of my journalism professor, Melissa Hart.)
- Shared [an example](https://developer.twitter.com/en/docs/tutorials/twitter-api-google-sheets) -- more long form than I'm used to, more like a Medium post. Which is great! Not all documentation has to be truncated. I also see a shift away from the cut-and-dry task-based documentation to, especially for beginners, a conversational walkthrough and narrative to why you're doing A Thing.
- Reviewing is important! Should be shared openly and often with colleagues and others outside your immediate team.

## Always Complete, Never Finished: Daniele Procida (@ Divio)

- Minimizing useless documentation pain
- The easier part is in the doing, of turning out tutorials, writing the content; the hardest part is where and when to start, making a plan, starting over is painful
- Staring at a blank page, wondering how and where to start; a fear that the work won't be useful until it's complete and it can't be completed in a reasonable timespan
- Pain when ground is shifting around a project in flux, and the content you've started must be refactored while the product or item changes
- How do you avoid useless frustration? What's responsible? Planning.
- Complex projects lure us into complicated plans; then next thing we know there's a mountain of complicated plans that aren't useful results until totally finished. Until that WIP has hit a degree to enable publishing. Anxiety that results are indeterminate without total completion of the plan.
- Documentation is about a product that needs documentation now.
- There's anxiety that there's a gap between the need for documentation and the completion of the documentation.
- Work can become out of date and useless, a trap, not exclusive to documentation but it's vulnerable to it.
- Examples in work and workshops of sketching out complex structures of nested lists of articles to create and topics to draft. But that over-planning can be a trap. Makes us think we're reaching for the clear goal, but depending on complexity can be a trap.
- We confuse the "finished" with the "complete." As a living project, documentation won't be complete, won't ever be finished.
- Planning can take a back seat and documentation work can be successfully with concrete, iterative processes.
- Well-formed growth principle: Example of a plant growing, organically, at a cellular level without needing to adhere to a plan at the higher level.
- The sprout of a plant always has another step in development, which is never finished, but is always a complete entity at any time. An outcome not fixed, but growth that adapts to conditions unexpected. A living, growing, adapting mechanism. Always well-formed at each stage of growth and is correct.
- It doesn't have a big picture, it doesn't need a big picture.
- It builds itself from inside out, one cell at a time. Each cell must develop according to itself, its own individual cell. Not the overarching blueprint.
- **Iterative Evolution Workflow**
- Take an item, review it, observe it, think of the single thing, the small thing, the one thing that would make it better. License not to worry, to decide that all is needed is what's in my hands today. Removes the pain and stress of being responsible for unfinished work that isn't of value until it meets a larger plan.
- Instead, every action represents a single step toward growth, improving one single cell at a time.
- Example of creating a camera reference guide. It started with some basic articles. Then expanded. And expanded again. And at a certain point naturally "exploded" from a few files to a full Python-based Sphinx documentation project published to Read the Docs. It was natural, organic.
- Over planning can lead down a rabbit hole and fall behind on product features while chasing the plan.
- Another organic example of a tadpole to frog. A tadpole isn't incomplete, it is what it is. It's a young frog on its way! Trust the process to take us on a journey.

## A Guide to Getting Started in Open Source: Abigail McCarthy (@VMWare)

- Took an early MH break, then listened while updating my personal site and resume; not currently planning any OSS activities but bookmarked the talk for future needs.

## Beyond Metrics: Using Maturity Models to Develop a Docs Strategy: Sarah R. Rodlund (@Wikimedia)

- User like ratings, satisfaction surveys, analytics can all help.
- Maturity Models are a way to frame process and strategy, across industries.
- Illustrates levels of maturity across an org, continuously improve
- 5 levels of maturity: Ad hoc > Rudimentary > Organized/repeatable > Managed and sustainable > Superior
- A clear and common language about documentation; compliment traditional metrics; showing doc state over time
- MMs fall short in flexibility and rigidity because they depend on clarity of project within the org. Need to prepare for pivots. Maturity is not an end state.
- Borrow from others, work from the highest to the lowest, adjust expectations based on org and resources; bring in diverse perspectives; revisit and reevaluate.
- Focus on progress, not perfection.
- [Github resources](https://github.com/grammarbot/maturity-model-resources)

## Sashay Your Way to Clearer API Documentation: Rachael Stavchansky (@Netlify)

- Slides availanble at [slides.com/rstav](https://slides.com/rstav)
- API reference docs should be like a map to help the user figure out what to do, why, and how.
- Guidelines for consistency in API. Amplify a writer's work, opinionated in a good way, standardized if enforced. Linting tools can automate enforcement.
- To build guidelines: Identify elements, draft guidelines for each, achieve consistency for readers.
- An example of an API style guide for writing functions of get/post/put/etc.
- If there are need for API doc improvements, don't hold back! Take the courage and be audacious. Don't have to be an expert.

## Putting the "Tech" in Technical Writer: Swapnil Ogale (@Readocly)

- WYSIWYG to DAC audience
- Example of not getting a job bc of others with better coding and programming experience
- Showing the "tech" experience better even without DAC solutions which not all orgs may have
- Example of a DOCX file being XML based; can use Notepad and make changes in XML even without Word.
- Python devs can modify DOCX/XML
- Help Authoring tools allow behind-the-scenes and raw editors in XML content (most often)
- Vector images are at the base, XML files; can open and edit in text editor and make changes/resize
- Basic DAC toolchain: Issue Tracking > Plain Text Files > Version Control > Reviews and Automation
- Examples of common git commands, learning enough to collaborate
- Move to CLI
- Github Flow/Trunk-Based Development
  - Main branch, production-level, access control
  - For docs, make a feature branch, make content updates
  - Branch: clone > branch > checkout
  - Create/review: commit > push > pull
- Plain text is freeing for writers; not interruptive UI, no buttons to achieve basic formatting; learning curve to UIs
- Markdown and other plain text can leave rendering and design to the compilers you use.
- Automation allows for baked-in reviews. Toolchains are the same, docs are surfaced to devs more readily.
- Tools aren't so political under DAC. Using what devs use, like GH pull/review process, it's already approved and native to product development.

## The Secret History of Libraries: Paris Buttfield-Addison

- Great stuff, more for fun. Recommend catching the recording once it's posted.
