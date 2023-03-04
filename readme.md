# MyWebClass.Org Project - Agile Documentation Assignment

## Overview

For this assignment, you need to develop an initial draft of project documentation based on the principles of the [Agile
Manifesto - MUST READ](https://agilemanifesto.org/principles.html)
and [Lean - READ ALL THE  PARTS 1-7 THAT ARE LINKED ON THE LEFT](https://www.planview.com/resources/guide/lean-principles-101/).
The purpose of this assignment is to help you
develop the mindset required take an idea and turn it into a product that people value. This is an open ended assignment
meaning that you need to think and create and not just follow a set of instructions. You are the one creating
instructions for yourself and the development team that you will be part of and/or possibly leading in the future. For
this assignment, you should use ChatGPT as much as possible to help you write good documentation. It is very good at
taking what you mean to say and turning into this type of documentation.
# Videos
* **[Agile Lean Part 1](https://youtu.be/e4FLisvf7vg)**
* **[Agile Lean Part 2](https://youtu.be/KIxQaWsG3vk)**

## Scope of the exercise

In the spirit of Lean and to start our project off using the "pull" approach to develompent we will only focus on the
following goal. MyWebClass is a website and we will need a development team that needs to work together in parallel
meaning that we eventually need to produce various content to support the objectives of the site. In order for this to
happen we need to create a basic web template that can be found using a search engine, addresses any legal requirements
that are relevant to our project, allows us to legally use Google Analytics to measure user behaviour on the site, and
passes [w3c validation](https://validator.w3.org), [Lighthouse](https://developer.chrome.com/docs/lighthouse/overview/), [GDPR Scanner](https://2gdpr.com).

In addition to planning the initial 0.1.0 release of the website template we also need a plan setup a DevOps process
that support the development of the project.

In general, you can expect that you have 3 major parts to your plan at this stage:

1. Basic Project Documentation and Project Management
2. DevOps
3. MyWebClass.org base website template with all technical and legal requirements satisfied to use Google Analytics and
   be appropriately listed in a search engine by implementing the basic on page SEO requirements.

To assist you with this project, I've included ALL of the code for required for a web page in
the [src/index.html](src/index.html) file and included comments as to why that line is in there, so that you can write a
user story and eventually a test for it.

## Things to consider:

1. Lean and Agile are both ideas that are complementary; however, neither is prescriptive in their implementation. Your
   project plan should be inspired by these ideas; however, how you implement them should be tailored to fit the
   particular project. Remember Lean's core idea is build, measure, and learn to create continuous improvement. Agile is
   essentially a way to organize within a software development team to make the development process sustainable and
   effective at producing working software with the least amount of waste.
2. In order to facilitate communication and provide a structure for project planning you must organize your project into
   themes, initiative, epics, user stories, and tasks, which are terms used within agile.
   **Themes:**
    * Themes are high-level categories of work that align with an organization's strategic objectives. They help to
      define and communicate the focus areas for a project or product. Themes can be used to organize and prioritize
      work, guide decision-making, and ensure that efforts are aligned with business goals.
      **Initiatives:**
    * Initiatives are a collection of related projects and activities that are aligned with a common goal or objective.
      They help to break down larger goals into smaller, manageable pieces. Initiatives are usually larger in scope than
      epics and are typically managed by a program or portfolio management team.
      **Epics:**
    * Epics are large pieces of work that can be broken down into smaller, more manageable pieces (i.e., user stories).
      They are larger in scope than user stories and often require coordination across multiple teams. Epics typically
      represent a major business or technical challenge that needs to be addressed.
      **User Stories:**
    * User stories are short, simple descriptions of a feature or piece of functionality from the perspective of a user
      or customer. They are used to communicate requirements and prioritize work. User stories are typically small in
      scope and can be completed in a single sprint (i.e., a short, time-boxed period of work). They help to ensure that
      development efforts are focused on delivering value to the end user.
      **Tasks:**
    * Agile Tasks:
    * Tasks are the smallest units of work in Agile development. They are specific, actionable items that need to be
      completed in order to deliver a user story. Tasks are usually estimated in hours and are used to track progress
      and identify obstacles. They are typically managed by individual team members and are part of the team's daily
      work.
3. Our goal is to develop a "pull" process for the development of the MyWebClass product and minimize or eliminate the
   amount of "push" in the MyWebClass.org
   project.  [Read this about the difference between push and pull to understand how these concepts relate to product development.](documentation/reading/push_vs_pull.md)
4. Every theme, initiative, epic, user story, and task needs a way to test that it is working. You can specify automated
   testing i.e. pytest for unit testing, Playwright for end to end testing, or manual testing. You may need to combine
   both manual and automated testing for themes, epics, and initiatives; however, tasks and user stories should us some
   type of automated testing as much as possible.
5. Every theme, initiative, epic, user story, and task should identify how you will measure it's effectiveness
   quantitatively. If you can't think of one now just put something in that might work in the future and this can be
   improved as things become more clear. YOu need to consider that to implement lean you have to build it, MEASURE IT,
   and LEARN, its not necessary or expected for something to be perfect, it is expected that any resources invested in
   something have some methodology to evaluate performance, and provide feedback for continuous improvement.

## Grading

For this assignment you will need to find a partner to review your project documentation and you will need to review
their documentation. Compare both of your project plans and create a list of the changes you decide to implement and
file them as issues on your repository. Resolve the issues using branches and merge the branch into main, so that you
have the best version of your project plan that combines the best ideas of you and your partner. Do not do the first
draft of the plan together, design it yourself and you should review your partners plan, and they should review yours.  Practice using the GitHub comment and review tool to review the agile tasks.  [Watch this video on how to do a code review using GitHUb](https://www.youtube.com/watch?v=8fx-EaOUK2E)

### Grading Rubric

1. 25 Points for having at least 5 comments on your code by your partner that result in 5 issues being created and  resolved.
2. 50 Points effective and sensible organization of your project that applies Agile and Lean ideas.   Use ChatGPT to help you with the writing, so that its written with a professional business tone and vocabulary. 
3. 25 Points for demonstrating that you understand that each activity needs to be measured and that each task needs some combination of manual and automated testing.

### Submission
Once you have the best version of your project plan after comparing it and resoling the issues turn the plan into Canvas.


## Overview

Looking to learn modern software development technologies and processes in a hands-on learning environment? Look no
further than MyWebClass! Our platform provides an integrated learning experience that contextualizes technology with
business processes to provide realistic scenarios for students to learn technology in a hands-on real world environment.

## Agile Project Documentation

### Templates - Modify these as necessary

* [Theme Template](documentation/templates/theme/theme_template.md)
* [Initiative Template](documentation/templates/theme/initiatives/initiative_template.md)
* [Epic Template](documentation/templates/theme/initiatives/epics/epic_template.md)
* [User Story](documentation/templates/theme/initiatives/epics/stories/story_template.md)
* [Task Template](documentation/templates/theme/initiatives/epics/stories/tasks/task_template.md)

## My Rough Draft

Here is an example of how I initially break down a project; however, I intend to change this in the near future, so that
i organize my themes by business activity instead of release schedule. Examples of these
themes include the DevOps and Search Engine Themes.

In practice, it is commonplace to adapt project documentation to meet evolving project needs early on in the process.
Therefore, please do not feel obligated to follow my approach. Instead, view it as an example of how to develop your own
documentation, based on your preferred methodology for breaking down the problem. Should you find that it does not meet
your needs, it can be adjusted, given that we are still in the early stages of the project.

At this juncture, the efficacy of the documentation is measured by how well it enables us to manage the project. We will
review this effectiveness before the next iteration of the project.
# Your  plan should replace the content below

[Project Setup](documentation/theme_1/theme_project_setup.md)

# Theme 1.0: Students Course Forum

## Overview
My objective is to create a highly visible forum presence for “mywebclass.org" using lean and agile principles that
develops a strong foundation for students to uncover their learning journeys during courses with Professor Williams.
By completing the initiatives outlined in this theme, we can establish a solid path forward that ensures our web page
meets our business requirements throughout the life of the project, setting us up for long-term success.

## Initiative(s)
* Provide students accessibility to fellow students at NJIT in class lectures by Professor Keith Williams for
interactive support and comments regarding their coursework.
* Develop camaraderie amongst classmates.
* Enable in-depth knowledge of the work in courses.

## Epic 1: User Registration
* User story 1.1: As a user, I want to be able to register for an account on the website, so that I can create forums
and post comments.
* User story 1.2: As a user, I want to be able to log in to my account, so that I can access my forums and comments.
[What authentication method you will be using, when a user resets their password (ex. authenticator application, SMS, one-time code, etc)]

  * Initiative 1.1: Implement user registration and login functionality using secure authentication methods.
  * Initiative 1.2: Implement password reset functionality using secure authentication methods.
    * Task 1.1.1: Design user registration and login pages.
    * Task 1.1.2: Implement user registration and login functionality.
[For Epic 1 - can you specify the parameters that will be require in order for user to login (For ex. username, email address, password, etc)]

## Epic 2: Forum Creation and Management
* User story 2.1: As a user, I want to be able to create a new forum, so that I can start a discussion on a topic of my
choice.
* User story 2.2: As a user, I want to be able to edit and delete my own forums, so that I can manage the content of my
forums.
* User story 2.3: As a user, I want to be able to search for forums based on keywords, so that I can find forums on
topics that interest me.
  * Initiative 2.1: Implement forum creation and management functionality.
  * Initiative 2.2: Implement forum search functionality.
    * Task 2.1.1: Design forum creation, editing, and deletion functionality.
    * Task 2.2.1: Design forum search page.
 [For task 2.2.1 - it would be good to provide more information on how the search page will work, such as what search criteria will be available. Ex. author, keywords, date, etc.]

## Epic 3: Comment Creation and Management
* User story 3.1: As a user, I want to be able to post comments on forums, so that I can participate in discussions.
* User story 3.2: As a user, I want to be able to edit and delete my own comments, so that I can manage the content of
my comments.
* User story 3.3: As a user, I want to be able to reply to other users' comments, so that I can have conversations with
other users.
[Consider adding a feature to report a comment if it is inappropriate]

  * Initiative 3.1: Implement comment creation and management functionality.
  * Initiative 3.2: Implement comment reply functionality.
    * Task 3.1.1: Design comment creation, editing, and deletion functionality.
    * Task 3.2.1: Design comment reply functionality.

## Epic 4: Legal Compliance
* User story 4.1: As a website owner, I want to ensure that all content on the site is properly attributed and licensed
to avoid copyright violations.
* User story 4.2: As a user, I want the website to be transparent about how my data is collected and used, so that I can
make informed decisions about using the website.
  * Initiative 4.1: Research and identify relevant legal requirements, such as GDPR, CCPA, and cookie consent regulatory
laws.
  * Initiative 4.2: Develop a privacy policy that outlines how user data will be collected, used, and protected.
    * Task 4.1.1: Ensure Legal Compliance with GDPR, COPPA, Copyright, and other applicable laws.
    * Task 4.2.1: Adopt Lean Thinking and Agile Development processes to be efficient and customer-focused.

## Epic 5: SEO Optimization
* User story 5.1: As a website owner, I want to improve website discoverability by search engines, so that more users
can access the website.
* User story 5.2: As a website user, I want to easily find the website using search engines, so that I can access the
website easily.
  * Initiative 5.1: Research and identify relevant keywords and phrases for the website.
  * Initiative 5.2: Properly structure with appropriate HTML tags, headings, and meta descriptions.
    * Task 5.1.1: Test website discoverability using search engine tools such as Google Search Console.
[In initiative 5.2 - it would be helpful to clarify how the keywords and phrases will be used on the website. For ex. will they use page titles, URLs, or in the content itself]

## Epic 6: Performance Optimization
* User story 6.1: As a website owner, I want to be able to track user behavior and analyze user data using
Google Analytics.
* User story 6.2: As a website owner, I want to establish a pull process for product development to ensure that we are
meeting customer needs and wants.
* User story 6.3: As a development team member, I want to use Agile development processes to ensure that our work is
efficient and customer-focused.
* User story 6.4: As a development team member, I want to be able to automate deployment and testing processes to
support continuous integration and deployment.
* User story 6.5: As a user, I want the website to be responsive and work well on different devices, so that I can
access the website from my desktop or mobile device.
  * Initiative 6.1: Implement Google Analytics to Measure User Behavior.
  * Initiative 6.2: Establish a Pull Process for Product Development to ensure customer needs and wants are addressed.
  * Initiative 6.3: Use Lean Thinking and Agile Development Processes to continuously improve the website.
  * Initiative 6.4: Automate deployment and testing processes to support Continuous Integration and Deployment.
  * Initiative 6.5: Implement responsive design.
    * Task 6.1.1: Develop an Initial Web Page Template that meets technical and legal requirements.
    * Task 6.1.2: Ensure website passes w3c validation for HTML and CSS.
    * Task 6.1.3: Ensure website passes Lighthouse audit for performance, accessibility, best practices, and SEO.
    * Task 6.2.1: Conduct Customer Research to Identify their Needs and Wants.
    * Task 6.2.2: Establish a Pull Process for Product Development based on Customer Feedback.
    * Task 6.2.3: Regularly Review and Analyze Customer Feedback to Ensure Customer Needs are Addressed.
    * Task 6.3.1: Establish a Development Process with Continuous Integration and Deployment to Support DevOps
Functionality.
    * Task 6.4.1: Identify and Automate Deployment Processes.
    * Task 6.4.2: Identify and Automate Testing Processes.
    * Task 6.4.3: Integrate Automated Deployment and Testing Processes.
    * Task 6.5.1: Develop Responsive Design Templates for Website.
    * Task 6.5.2: Test Responsive Design on Different Devices.
    * Task 6.5.3: Ensure Website Content is Optimized for Mobile Viewing.

## Result
By following the theme, initiatives, epics, user stories, and tasks outlined above, we can create a basic forum that
meets legal requirements, is optimized for search engine discoverability, and passes validation and scanning tests.

## Test plan
N/A

## Release Schedule

| Release Version | Release Date | Features |
|-----------------|--------------|----------|
| 0.1.x           | TBD          | TBD      |

