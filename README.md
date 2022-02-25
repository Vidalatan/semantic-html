# 01 HTML, CSS, and Git: Code Refactor

## Task

```
GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the icon and image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title
```

## Primary Changes

**Semantic** tags used to **replace** div tags for search engine optimization, reorganization of HTML and CSS structure, and ensure site functions as intendend


## What was Done

```
-Change div with class="header" to "header" for semantics

-Search Engine link on the navigation wasn't working due to refrence to id that wasn't stated in the appropriate div. Added appropriate id to allow link to jump to correct location on the page.

-Changed index.html div, as well as style.css ".header" nested selectors, to be nav instead of div to reflect the navigation area

-Put div with class="hero" inside of figure tag

-Changed div with class="content" to main tag to reflect that it is primary content

-Changed div with class="benefits" to aside to reflect that it is information aside from the main content

-Changed div with class="footer" to footer to reflect that it is the footer information (contains company and copyright info)

-Changed title tag's content to contain "Horiseon Social Solution Services"
```

## Finished Product

![Full Webpage Screenshot](./assets/images/horiseonpage.png)

Link to live [Horiseon Webpage](https://vidalatan.github.io/semantic-html/)

Link to [Code Repository](https://github.com/Vidalatan/semantic-html)