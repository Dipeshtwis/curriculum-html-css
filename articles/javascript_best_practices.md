# JavaScript best practices

## General practices
1. Keep all the JavaScript code in JS files, not in the `script` tag.
2. Keep your [code clean](https://devinduct.com/blogpost/22/javascript-clean-code-best-practices) following these advices about
  - type checks
  - naming
  - simplicity
  - DRY
3. If you use node modules - .lock files should be in the repository to avoid problems with future versions of the dependencies.
4. Use ES6 object destructuring to get the values from an object. This way you can avoid repeating a lot of code.

## JavaScript in the browser
1. Do not commit `console.log` to your repo. It’s ugly, it kills performance and it can make confidential data be visible in the browser tools.
2. Do not use `window.alert()` or `window.confirm()`. It’s ugly, impossible to style, stop code execution and display differently on different browsers. Use custom modal instead.
3. Keep the number of changes/updates to the DOM as low as possible, they are very expensive for the browser.
4. Keep the application logic separated from DOM manipulation tasks.
5. Do not use `document.write` or `eval`
