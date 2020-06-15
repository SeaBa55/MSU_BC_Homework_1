# 01 HTML CSS Git: Code Refactor

One of the most common tasks for front-end and junior developers is to take existing code and refactor it to either meet a certain set of standards or implement a new technology. Web accessibility is an increasingly important consideration for businesses, ensuring that people with disabilities or socio-economic restrictions have access to their website, and helping them avoid litigation.

Your task is to refactor an existing webpage to make it accessible. An important rule to follow when working with someone else's code is the Scout Rule:

> Always leave the code you are editing a little cleaner than you found it.

To impress clients, you should always go the extra mile and improve their codebase for long term sustainability. Ensure that all links are functioning correctly and clean up the CSS to make it more efficient, consolidating CSS selectors and properties, organizing them to follow the semantic structure of the HTML elements, and including comments before each element or section of the page.

## User Story

```
AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines
```

## Acceptance Criteria

```
GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title
```

## Review

You are required to submit the following for review:

* The URL of the deployed application.

* The URL of the GitHub repository. Give the repository a unique name and include a README describing the project.

## Revision History

Horiseon - v1.0 - Initial git commit; clone of original index.html and supporting documents.

Horiseon - v1.1 - Made index.html easier to read; changed title form "website" to "Horiseon" (index.html line 7).

Horiseon - v1.2 - Fixed broken nav bar selection; Changed class="search-engine-optimization" to id tag (index.html line 37).

Horiseon - v1.3 - Removed classes "float-left" & "float-right" (index.html lines 38,46,54); Removed float classes (styles.css lines 62-70) and added float/ margin arguments to individual image subclasses (styles.css lines 164-177).

Horiseon - v1.4 - Made styles.css easier to read; Grouped all redundant lines of code into single blocks.

Horiseon - v1.5 - Removed classes "online-reputation-management" & "social-media-marketing" (index.html lines 45,53); Removed redundant image end tag (index.html lines 83). 

Horiseon - v1.6 - Changed all the class '.' selectors for "search-engine-optimization", "online-reputation-management", & "social-media-marketing" to id '#' selectors (styles.css lines 95,104,109,115).

Horiseon - v1.7 - Changed classes "benefit-lead", "benefit-brand", "benefit-cost" to unique identifier (ID) elements (index.html lines 65,73,81);

Horiseon - v1.8 - Changed all the class '.' selectors for "benefit-lead", "benefit-brand", & "benefit-cost" to id '#' selectors (styles.css lines 79,84,89).

Horiseon - v1.9 - Changed class "seo" to unique identifier (ID) element (index.html line 14); Changed class '.' selectors for "seo" to id '#' selectors (styles.css lines line 23).

Horiseon - v2.0 - Removed ".header div ul { list-style-type: none; }" as it contributes no effect (styles.css lines 35-37);

- - -
© 2019 Trilogy Education Services, a 2U, Inc. brand. All Rights Reserved.
