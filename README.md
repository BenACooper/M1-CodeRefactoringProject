# M1-CodeRefactoringProject
A project to practice refacoring existing HTML & CSS. Original versions are saved in the OldAssets folder for reference.

## Goals HTML:
- HTML elements are semantic.
- HTML elements are structured logically, independent of style and positioning.
- Icon & image elements have accessible ALT attributes.
- Heading attributes fall in sequentia order.
- Title element is concise and descriptive.
- All links function properly.
- Selectors & properties are organized semantically and consolidated.
- CSS file is properly commented.

## Refactoring Record
### Title, Semantic HTML & Corresponding CSS Selectors
- HTML line 7: Renamed title from "website" to "Horison - Online Reputation Management & Social Media Marketing"
- HTML lines 11/21 & CSS lines 11/18/23/27/35/39: Renamed element from "div" to "header." Removed redundant class attribute. Renamed corresponding selectors from ".header to "header."
- HTML line 27 & CSS line 52: Renamed class "hero" to "herobanner." Renamed corresponding selector ".hero" to ".herobanner"  
- HTML lines 29/35 36/42 43/69: Renamed 3 elements from "div" to "section"  
- Push changes to GitGub before attempting to restructure the navbar into the header.


## QUESTIONS:
- When "git add -A" command line responded "warning: in the working copy of 'assets/style.css', CRLF will be replaced by LF the next time Git touches it" 0- What does this mean?
