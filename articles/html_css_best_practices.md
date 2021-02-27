# HTML & CSS best practices

1. Use the appropriate tags for each element (e.g., links, titles, etc.) and use HTML5 semantic tags (e.g., header, nav) over `div`s.
2. Avoid too long code lines.
3. Be careful with blank lines and indentation
    - Do not add blank lines, spaces, or indentations without a reason.
    - For readability, add blank lines to separate large or logical code blocks.
    - For readability, add two spaces of indentation. Do not use the tab key.
4. Close all HTML elements.
     - `<div>` always needs `</div>`
5. Use lowercase for elements and attribute names.
     - use `<div>` not `<DIV>`
     - use `<div class="striped">` not  `<div CLASS="striped">`
7. Always quote attribute values.
     - use `<div class="striped">` not  `<div class=striped>`
8. Use space-less equal signs.
     - use `<div class="striped">` not  `<div class = "striped">`
9. Do not use inline styles. Keep your style definition in a separate CSS file.
10. Do not overuse `!important` rule in your CSS style definitions.
11. Always use the class attribute for multiple elements (do not use ID selector for multiple elements).
