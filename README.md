## Horiseon refactoring task
    As a marketing agency,
    Horiseon wanted a codebase that follows accessibility standards,
    so that their site is optimized for search engines.

## Refactoring the Horiseon website
    Existing code has been provided (index.html and style.css)
    We need to improve it without changing its actual functionality,]
    while meeting a certain set of acceptance criteria,
    among which the accessibility is highlighted

## Acceptance Criteria

GIVEN a webpage meets accessibility standards
1. WHEN I view the source code;
    THEN I find [semantic] HTML elements

2. WHEN I view the structure of the HTML elements
    THEN I find that the elements follow a logical [structure] independent of styling and positioning

3. WHEN I view the icon and image elements
    THEN I find accessible [alt] attributes

4. WHEN I view the heading attributes
    THEN they fall in [sequential] order

5. WHEN I view the title element
    THEN I find a [concise], [descriptive] title


## Repository organisation
[Repository]
git@github.com:heranYang93/Horiseon-Refactoring.git)

[Structure]
Horiseon-Refactoring/assets
    ./css (contains css stylesheet for the index.html)
    ./images (contains images to support the website)
Horiseon-Refactoring/assets
    ./requirements (contains client requests and acceptance criteria)
index.html (Refactored html file with increased accessibility)

## Access and review
Please review the website on a laptop device (width > 1060px),
using the following URL:
https://heranyang93.github.io/Horiseon-Refactoring/

## General refactoring comments and principles
You can find the comments in each file.

 HTML - Refactored Principles (HRP):
    [HRP1] - Container tags are reassigned to reflect their relevance to the structure (e.g. <div> are reassigned to <sections> where the area is more content-oriented)
    [HRP2] - Contents sharing same hierarchy are placed under a list
    [HRP3] - Adding 'alt' attributes to embed descriptive messages for assessibility reasons, created descriptive messages when sections are folded, attempting to increase readability

CSS - refactoring general comment:
    [1] New selectors are used, merging existing selectors with similar format
    [2] The new selectors are orgniased and regrouped in a way that follows the HTML structure
    [3] Unused old selectors are placed after line 185 for revision.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.