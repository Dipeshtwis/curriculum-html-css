# HTML/CSS & JavaScript capstone project - Conference page

## Learning objectives

- Use semantic HTML tags.
- Apply best practices in HTML code.
- Use CSS selectors correctly.
- Use CSS box model.
- Use industry-standard tools (Flexbox) to place elements in the page.
- Able to create UIs adaptable to different screen sizes using media queries.
- Use GitHub pages to deploy web pages.
- Apply JavaScript best practices and language style guides in code.
- Use JavaScript to manipulate DOM elements.
- Use JavaScript events.
- Use objects to store and access data.
- Communicate technical concepts to other technical people.

### Estimated time: 19.5h

## Description

The project you are going to build is based on an *online website for a conference*. We provide some design guidelines for you to create the website, but **you must personalize the content**, i.e., instead of a conference you can build a website for a concert or for a web development course. It's very important the you personalize your project, so that you have something unique in your portfolio to share with potential employers during job searching.

<p align="center">
  <img src="./images/conference_page.png" alt="Form" />
</p>

*IMPORTANT NOTE: Read **all** requirements before you start building your project.*

### General requirements

- Make sure that there are [no linter errors](https://github.com/microverseinc/linters-config).
- Make sure that you used correct [GitHub flow](https://github.com/microverseinc/curriculum-transversal-skills/blob/main/git-github/articles/github_flow.md).
- Make sure that you documented your work [in a professional way](https://github.com/microverseinc/curriculum-transversal-skills/blob/main/documentation/articles/professional_repo_rules.md).

### HTML/CSS & JavaScript requirements

- Follow our list of [best practices for HTML & CSS](https://github.com/microverseinc/curriculum-html-css/blob/main/articles/html_css_best_practices.md).
- Follow our list of [best practices for JavaScript](https://github.com/microverseinc/curriculum-html-css/blob/main/articles/javascript_best_practices.md).

### Project requirements

- You should personalize the content of you page: choose a topic and build the web around it
- You should build only these 2 pages:
  - the *home page*
  - the *about page*
- Each of these pages should have versions for 2 different screen sizes: 
  - mobile: up to 768px
  - desktop: from 768px
- You should follow the [design guidelines](https://www.behance.net/gallery/29845175/CC-Global-Summit-2015), including
  - colors
  - typographies: font face, size and weight
  - layout: composition and space between elements
- Interactions
  - links
    - the *home page* have a link in the menu to the *about page*
    - the logo in the header links to the *home page*
  - mobile menu
    - when the user clicks (or taps) the hamburger button on the header, the mobile menu appears over the page
    - there are no guidelines for the mobile menu in the docs, but you should implement it so it is consistent with the design (colors, typography, spacings, etc.)
    - the mobile menu has a close (X) button that closes the menu
- Dynamic page
  - the section "Featured speakers" should be created dynamically in JavaScript
  - you should use a JavaScript variable with the data of the speakers and use it when the page loads to create the HTML of the section dynamically

Original design idea by [Cindy Shin in Behance](https://www.behance.net/adagio07).

The [Creative Commons license of the design](https://creativecommons.org/licenses/by-nc/4.0/) requires that you give appropriate credit to the author. Therefore, you must do it in the README of your project.

### Project documentation

Once you have finished the development of the project, you should record a video presenting the features of the project you built. It is a video with a **maximum length of 5 minutes**. The content of the video should include:

- a description of the project
- a demo of the project features (different pages and different screen sizes)
- you should also highlight some interesting piece of code or something you built that you are very proud of

For recording the video you can use tools like [Loom](https://www.loom.com/), that let you share a private link to the recording, and configure a shot that shows your computer screen and your face at the same time in a small picture.

## Challenge breakdown

In order to tackle this challenge, you need a plan! We created high-level milestones for you. Your job is to make them more detailed.

### Day 1

**Milestone 0 - project setup (0.5h)**

- Set up the repository and tools.

**Milestone 1 - content (1h)**

- Choose the topic for your website.
- Choose images, text, icons, fonts.

**Milestone 2 - mobile first (5h)**

- Create the 2 pages for mobile
- Deploy the project

### Day 2

**Milestone 3 - desktop version (5h)**

- Adapt the 2 pages to desktop

**Milestone 4 - interactions (1.5h)**

- Implement the user interactions: link, mobile menu
- Deploy the project

### Day 3

**Milestone 5 - dynamic page (5h)**

- Implement the section "Featured speakers" with dynamic HTML
- Deploy the project, and test for final details

**Milestone 6 - documentation (1.5h)**

- Record a video for your project
- Create a good README and PR description

### Need a big picture?

Remind me about [what it is a capstone project](TBD).

## Code review

You will get a code review when you build the complete project, not after each milestone. You you have it ready, follow [these steps](https://github.com/microverseinc/curriculum-transversal-skills/blob/main/code-review/articles/how_to_ask_for_a_code_review.md) to request a code review of your project.

## Submit your project

After the final approval from a code reviewer, you need to submit your project.
[Read this FAQ for a reminder on how to submit your project](https://microverse.zendesk.com/hc/en-us/articles/360061344234).

Now go to your Student Dashboard and submit your project.

## Additional requirements

*These are all optional, but if you're interested in exploring this topic further, feel free to implement them. Any exploration here should be done outside program time.*

*If you decide to implement these requirements you should do it in a separate pull request. As always, remember to clearly document your decision in GitHub comments.*

- You could implement some UX improvements: the "More" button in the home page, include transitions and/or animations, etc.
- You can implement additional pages, like the *tickets page* and the *schedule page*. Make sure that you have a decent mobile design for them.
