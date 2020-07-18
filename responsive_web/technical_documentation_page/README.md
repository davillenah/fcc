# Responsive Web Design Projects - Build a Technical Documentation Page

**Objective**: Build a CodePen.io app that is functionally similar to this: [Technical Documentation Page](https://codepen.io/freeCodeCamp/full/NdrKKL).

Fulfill the below user stories and get all of the tests to pass. Give it your own personal style.

You can use HTML, JavaScript, and CSS to complete this project. Plain CSS is recommended because that is what the lessons have covered so far and you should get some practice with plain CSS. You can use Bootstrap or SASS if you choose. Additional technologies (just for example jQuery, React, Angular, or Vue) are not recommended for this project, and using them is at your own risk. Other projects will give you a chance to work with different technology stacks like React. We will accept and try to fix all issue reports that use the suggested technology stack for this project. Happy coding!

**User Story #1**: I can see a _main element_ with a corresponding `id="main-doc"`, which contains the page's main content (technical documentation).

**User Story #2**: Within the `#main-doc` element, I can see several _section elements_, each with a `class="main-section"`. There should be a minimum of 5.

**User Story #3**: The _first element_ within each `.main-section` should be a _header element_ which contains text that describes the topic of that section.

**User Story #4**: Each _section element_ with the `class="main-section"` should also have an id that corresponds with the text of each header contained within it. Any spaces should be replaced with underscores (e.g. The section that contains the header "JavaScript and Java" should have a corresponding `id="JavaScript_and_Java"`).

**User Story #5**: The `.main-section` elements should contain at least _10 p elements_ total (not each).

**User Story #6**: The `.main-section` elements should contain at least _5 code elements_ total (not each).

**User Story #7**: The `.main-section` elements should contain at least _5 li items_ total (not each).

**User Story #8**: I can see a _nav element_ with a corresponding `id="navbar"`.

**User Story #9**: The _navbar element_ should contain one _header element_ which contains text that describes the topic of the technical documentation.

**User Story #10**: Additionally, the navbar should contain _link (a) elements_ with the `class="nav-link"`. There should be one for every element with the `#main-section`.

**User Story #11**: The _header element_ in the navbar must come before any _link (a) elements_ in the navbar.

**User Story #12**: Each element with the `#nav-link` should contain text that corresponds to the _header_ text within each _section_ (e.g. if you have a "Hello world" section/header, your navbar should have an element which contains the text "Hello world").

**User Story #13**: When I click on a _navbar element_, the page should navigate to the corresponding section of the _main-doc element_ (e.g. If I click on a _nav-link element_ that contains the text "Hello world", the page navigates to a _section element_ that has that id and contains the corresponding header.

**User Story #14**: On regular sized devices (laptops, desktops), the element with `id="navbar"` should be shown on the left side of the screen and should always be visible to the user.

**User Story #15**: My Technical Documentation page should use at least _one media query_.

You can build your project by forking this CodePen pen. Or you can use this CDN link to run the tests in any environment you like: [Test](https://cdn.freecodecamp.org/testable-projects-fcc/v1/bundle.js)

Once you're done, submit the URL to your working project with all its tests passing.
