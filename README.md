# Work-as-Tasks

## TL;DR

Years of experience with a given technology is a poor proxy for a person’s ability to contribute to a project’s success. Ultimately, project success is the goal, and knowledge workers are the conduit to that goal. How do we effectively manage people’s knowledge and ability to their fullest potential.The proposed solution is to use this formula:

**Skill = Task * Ability**


## Overview

Given the "equation":

**Skill = Task * Ability**

where

**Task** = “Coded a user authentication workflow in React”

**Ability** is one of the set:
1. Beginner: Studied / Researched it
2. Apprentice: Performed successfully with help from a mentor
3. Independent: Performed successfully without help from a mentor
4. Mentor: Successfully mentored someone

Besides Ability, there may be a need to capture more features in order to fully appreciate the scope of what we consider to be a Skill, for example:

Recency: How recently did you employ this Task at the given Ability? This is just a proxy for measuring how quickly a person could implement this Skill, i.e. would they need a day or two to get reacquainted with it, or can they hit the ground running. There may be better approaches to answering this question.

Efficiency: How quickly can you accomplish the given Task relative to your peers, with an equivalent level of quality?

Such that:

**Skill = Task * Ability * Recency * Efficiency**

These are just some of features that attempt to approximate an accurate answer to the question:

If I put these individuals on to this project, will it succeed?

Which is an impossible question to answer with perfect accuracy, but, we can certainly do better than we have been doing thus far. Further enhancements could be trialled, including capturing domain knowledge (e.g. Real estate, Insurance, Banking) that an individual may have been exposed to, and qualifications (e.g. Degrees, courses, etc.) as well as soft skills (e.g. empathy, organisation, creativity, etc.)

## Problem Definition

Most organisations have a lack of knowledge around employee skills. This manifests itself as projects that run over budget/time, leading to unnecessary loss in revenue, negative brand reputation and overall stress on the business and its employees. Businesses that utilise knowledge workers in order to function, generally know very little about what knowledge their employees have and how they practically implement that knowledge.


### History

This is not a novel idea, but rather a combination of multiple ideas and implementations that already exist.
Ascribing abilities to specific people is a millennia-old concept, or at least as old as when some cultures created family names to disambiguate between people, e.g. `Schumacher` (Shoe maker).

Personally, I think the kernel of this approach started in the early 2000's, where I happened on Microsoft's consulting practice, where they would attempt to help organisations map their capabilities to technology, ostensibly as a means to replace or augment at least some of the business's outdated technologies (fax, call centre, etc.) with one of their products.


### Solution Success Criteria

We should be able to answer all of these questions:

- What skills do we have?
- What skills do we need?
- How do we grow/improve skills?
- Which skills are no longer needed?
- How do we make skills more visible?
- Which skills should be internal versus external, temporary versus permanent?
- Do we currently leverage our strengths?
- What is our skills roadmap for the next 1-2 years?
- How are skills tied to career paths?
- What does the business need in terms of specific skills, now and in the future?
- How can leaders and employees work together toward supporting specific skills in future?
- Who can mentor me to improve my skills?
- Who would be the most effective people to have on a project?
- Do we have any gaps in certain skills?
- Do we have a way to manage succession planning?



**Terminology:**

- User: A specific Person with a personally identifiable set of data captured in the system. It is assumed that every User has a one-to-one relationship with a real Person.
- ManagerUser: A User who is a direct manager of at least one other User, within the scope of their current project or globally as part of the organisation structure
- AdminUser: A User with elevated privileges that has the ability to manage higher level entities in the system.
- ProjectManagementUser: A User with specific responsibilities around ensuring the delivery of a project or set of projects.
- HumanResourceUser: A User with specific responsibilities around ensuring the alignment of expectations between the business, its employees, and contractors.
- Mentor: A Person who has the ability (and potentially, temperament and time) to guide another Person in completing a task. We would possibly need to utilise courseware as a proxy for a real Person, if we need to scale this beyond how many people we have available.
- Task: A specific unit of work, worded in the past tense to help ensure accurate data capture, i.e. "I have done this" vs "I can (will) do this" (helps to minimise "Future bias"). The scope and granularity of these Tasks would be one of the keys to successful adoption of this system. Too high-level and the data points might not be valuable. Too low-level and the sheer amount of data would be too much for Users to manage and maintain over time.
- Skill: A User can complete a Task at one or more Ability.
- Ability: One of the following:
  - Beginner: Studied / Researched the given task
  - Apprentice: Performed the given task successfully with help from a mentor
  - Independent: Performed the given task successfully without help from a mentor
  - Mentor: Successfully mentored someone in the given task


**High-Level User Stories:**

- As a User, I want to create a Task, so that I and other Users can add it to our Skills lists
- As a AdminUser, I want to verify a new Task before it can be added to a Skills list, so that Tasks can remain at roughly the same level of granularity
- As a User, I want to Tag a Task, so that I and other Users can filter Tasks based on a user-defined taxonomy
- As a User, I want to add a Skill to my profile, so that it can be visible to other Users
- As a User, I want to track the changes in my Skills over time, so that I can see my progress
- As a User, I want to see which Users could mentor me in a specific Task, so that I can request their help in order to increase my Ability for that Task
- As a User, I want to see what Skills a specific User has, so that I can help to direct their learning
- As a User, I want to capture my interest to increase my Ability for a specific Task so that this information can be used in my personal development plan
- As a ManagerUser, I want to see all the Skills of a specific User, so that I can liaise with that User to design a personal development plan for them
- As a ManagerUser, I want to see the changes in a specific User’s Skills over time, so that I can make informed decisions about their personal development plan and their suitability for a specific project
- As a User, I want to receive regular feedback about the progress of my personal development plan, so that I can ensure that I either: meet the pre-defined expectations or, have the opportunity to redefine expectations in a timely manner
- As a ProjectManagementUser, I want to see all the Skills in my organisation, so that I can make an informed decision about what type of client projects to accept
- As a HumanResourceUser, I want to see all the Skills in my organisation, so that I can make an informed decision about who to hire
- As a User, I want to verify or challenge another User's Skills, so that the captured Skills can remain accurate over time
- As a ProjectManagementUser, I want to find Users that have a specific Skill or set of Skills, so that I can manage which people to assign to which projects


### Solution Approach

#### Phase 1
- Kick-off session
- Skills definition workshop(s)
- Start with defining hard skills
- Once hard skills are defined, start working on soft skills
- Ability/Fluency wheel overview
- Decide on software to use for capturing and reporting on skills
- Populate the skills matrix
- Create personal development plans
- Operationalise
- Run it with one team as a start. Gather feedback as to what is working and what isn’t. This is vital. It will help you get buy-in and will help optimise the process over time.


#### Phase 2
- Reflect on Personal Development Plan progress each month
- Coordinate skills matrix with another similar team
- Repeat with other teams
- Regularly gather feedback to optimise the implementation over time


### Some Potential Pitfalls

- Some people may find the process of gathering data about their skills upsetting or tedious. There may be some individuals who do not want to be involved in this process. A decision would need to be made about whether this is mandatory or whether it is acceptable that some individuals do not capture their skills.
- Imposter Syndrome may cause some individuals to interact with the implementation phase in unforeseen ways. For example, either under- or over-estimating their skill levels, etc.
- Continuous improvement is necessary for this solution to be fruitful in the long-term, there is a risk that it will not last, unless there is a constant drive from the business.
- People will cheat the system, this is inevitable. Steps can be taken to minimise this risk, e.g. making everyone’s skills visible to the entire organisation, some sort of peer review process, etc. Ultimately, by actually using the system, i.e. using a person’s skills profile to match them to projects, will probably make them less likely to inflate their abilities, lest they be put on a project on which they know they will not be able to cope.
- Using a single source of truth for skills also makes it a single point of failure. In the attempt to serve multiple stakeholders, when those stakeholders have different requirements in future, the underlying structure may not be able to accommodate their new requirements.


### Notes

- The term competency should probably be avoided, as it may have some negative connotations for some people.


### Some Useful Resources

- https://www.youtube.com/watch?v=4QlPQeJFjH0
- https://circleci.com/blog/7-steps-to-building-an-engineering-competency-matrix/
- https://docs.google.com/spreadsheets/d/131XZCEb8LoXqy79WWrhCX4sBnGhCM1nAIz4feFZJsEo/edit#gid=0
- https://circleci.com/blog/why-we-re-designed-our-engineering-career-paths-at-circleci
