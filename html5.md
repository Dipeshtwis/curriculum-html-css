# Semantic tags, box model and developer tools

## Learning objectives

- Apply best practices in HTML code.
- Use semantic HTML tags.
- Use CSS selectors correctly.
- Use CSS box model.

### Estimated time: 2h

## Semantic tags

Semantic tags (also known as HTML5 semantic tags) are a set of HTML tags introduced in HTML5 that allow developers to more accurately describe the relationship between HTML elements on a webpage. For example, instead of using `div` tags to group elements we can use `header`, `nav` or `section` tags depending on what specific type of group of elements we are trying to make. 

### Why are they important?

Using semantic tags does not change the appearance of the website in the browser. So why is it important to use semantic tags? Quite simply, semantic tags more accurately describe the content that is on the page. Describing the contents of the page more semantically can have many benefits, such as:

- Making code easier for people to navigate when updating features or fixing bugs.
- Giving your page a higher Search Engine Optimization (SEO) score, which makes your content more visible on search engines.
- Allowing users with special needs to access your website using alternative means such as screen readers, which are devices that read the contents of a webpage aloud to users who have visual impairments.

### Learn more

Here is a complete guide on [how the new semantic HTML tags work](http://diveintohtml5.it/semantics.html).

And here is a guide on [how to identify the different parts of a typical website](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Document_and_website_structure).


## The box model and dev tools

Each HTML element behaves like a box that has the following properties:
- content width
- content height
- padding (top, bottom, left, right)
- border (top, bottom, left, right)
- margin (top, bottom, left, right)

These properties can be changed using CSS. Changing any one of those properties affects how the box appears on the page, and how that element interacts with the other elements around it.

The box model is not the only thing that can change the look of an HTML element. Every element also has a `display` property that defines how it stacks with the other elements, e.g., horizontally, vertically, hidden, etc. that can affect its appearance.

### Why is this important?

Understanding the box model and what properties can change the appearance of an HTML element can enable you to style HTML elements with CSS quickly and easily without having to attempt trial-and-error changes.

If trial-and-error does become necessary, it can be done using the browser's developer tools that make it easier to visualize the relationship between different HTML elements. The developer tools allow the developer to make rapid changes to the HTML and CSS running in the browser to see what those changes would look like immediately. This allows the developer to narrow down the problem much more quickly than is possible in a typical development environment where code files need to be opened, edited, and often even uploaded to a server, or possibly merged into the main branch of the project before a change can be viewed.

### Learn more about the box model

- Read [this tutorial by Shaye Howe](https://learn.shayhowe.com/html-css/opening-the-box-model/) and play around with the code examples. At the end of the tutorial you will get info on how to use the browser dev tools to better understand the box model.
- Watch this [10-minute video tutorial](https://www.youtube.com/watch?v=wcFnnxfA70g) about how to use developer tools.

## Additional Materials
- Read more about the CSS box model at [CSS tricks](https://css-tricks.com/the-css-box-model/) and [learnlayout's tutorial](https://learnlayout.com/box-model.html).
- Read more about the CSS [display](https://learnlayout.com/display.html) and [box-sizing](https://learnlayout.com/box-sizing.html) properties from learnlayout's tutorials.
- See [Mozilla's documentation on the Firefox developer tools](https://developer.mozilla.org/en-US/docs/Tools) or [Google's documentation on the Chrome developer tools](https://developers.google.com/web/tools/chrome-devtools/) to learn more about browser developer tools.

## Quiz

[Assess your learning with this quiz](https://docs.google.com/forms/d/e/1FAIpQLSczJp36Eeo1DflTJDQMiAdRMQcS4GLvdVGVVlQPxyJbA8tp_g/viewform)
