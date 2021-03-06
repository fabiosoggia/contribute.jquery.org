---
title: jQuery's Style Guides
---

jQuery projects strive to use a common set of styles for code and documentation. This facilitates a team of developers working on the same code base. If each developer were to use their own style, there would be jarring changes in the code as someone read through it. This slows comprehension and can also cause spurious differences in changesets as developers alter style in frivolous ways on the code they touch. 

Our style guides aim to make the code bases appear as if they were written by one precise punctilious programmer, rather than a a cacophony of competing coders. As with many aspects of coding and writing, there can be differences of opinion about the best style. Contentious issues like "spaces versus tabs" or "semicolons or not" distract from the goal of writing code that works. Most project contributors have a slightly different personal coding style, but we all use the jQuery style when contributing to jQuery projects.

Long term, we would like to have all of the formatting automatically done by the build process, so that the resulting code would alway follow the style guide. We haven't reached that nirvana yet, but we have taken a few steps in that direction. For example, our projects contain an [EditorConfig file](http://editorconfig.org) that many programming editors can use to enforce the space and tab rules. Our [JSHint](http://www.jshint.com/about/) configuration checks for common style _faux pas_ such as trailing spaces on a line, or using a variable before it is defined.

### [JavaScript Style Guide](/style-guide/js/)

### [HTML Markup Style Guide](/style-guide/html/)

