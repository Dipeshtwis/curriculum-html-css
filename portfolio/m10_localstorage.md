# Milestone 10 - Preserve data in the browser

## Learning objectives

- Use local storage to save user input.

### Estimated time: 3.5h

## Description

For this final milestone of your portfolio website, you will save the form data in the `local storage` of the browser. That way when the user reloads the page the data they filled out in the form will be preserved.

*IMPORTANT NOTE: Read **all** requirements before you start building your project.*

### General requirements

- Make sure that there are [no linter errors](https://github.com/microverseinc/linters-config).
- Make sure that you used correct [GitHub flow](https://github.com/microverseinc/curriculum-transversal-skills/blob/main/git-github/articles/github_flow.md).
- Make sure that you documented your work [in a professional way](https://github.com/microverseinc/curriculum-transversal-skills/blob/main/documentation/articles/professional_repo_rules.md).

### HTML/CSS & JavaScript requirements

- Follow our list of [best practices for HTML & CSS](https://github.com/microverseinc/curriculum-html-css/blob/main/articles/html_css_best_practices.md).
- Follow our list of [best practices for JavaScript](https://github.com/microverseinc/curriculum-html-css/blob/main/articles/javascript_best_practices.md).

### Project requirements

- You should implement the following interactions:
  - When the user changes the content of any input field, the data is saved to the local storage.
  - When the user loads the page, if there is any data in the local storage the input fields are pre-filled with this data.
- You should use the following data model:
  - You must create **a single JavaScript object with all the data from the entire form** and save it in local storage. Do not create one local storage entry per input field.

- **You need to use pair-programming for this project. We will check to make sure that both partners have contributed to the project by looking at the commit history of the project. Therefore you need to select one of the portfolios in your pair-programming group in which you will implement the above features.**

### Need a big picture?

Remind me about [the big picture of this project](./sneak_peek.md).

## Code review

Follow [these steps](https://github.com/microverseinc/curriculum-transversal-skills/blob/main/code-review/articles/how_to_ask_for_a_code_review.md) to request a code review of your project.

## Submit your project

After the final approval from a code reviewer, you need to submit your project.
[Read this FAQ for a reminder on how to submit your project.](https://microverse.zendesk.com/hc/en-us/articles/360061344234)
Now go to your Student Dashboard and submit your project.

## Additional requirements

*These are all optional, but if you're interested in exploring this topic further, feel free to implement them. Any exploration here should be done outside program time.*

*If you decide to implement these requirements you should do it in a separate pull request. As always, remember to clearly document your decision in GitHub comments.*

- You can create a "Reset" button for the form that resets the input fields and deletes the data in the local storage.
- Follow the design guidelines about buttons from [the templates in Figma](https://www.figma.com/file/l7SqJ3ZfkAKih9sFxvWSR4/Microverse-Student-Project-1?node-id=0%3A1).
