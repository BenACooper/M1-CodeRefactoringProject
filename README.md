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
- HTML line 7: Renamed title from "website" to "Horiseon - Online Reputation Management & Social Media Marketing"
- HTML lines 11/21 & CSS lines 11/18/23/27/35/39: Renamed element from "div" to "header." Removed redundant class attribute. Renamed corresponding selectors from ".header to "header."
- HTML line 27 & CSS line 52: Renamed class "hero" to "herobanner." Renamed corresponding selector ".hero" to ".herobanner"  
- HTML line 28 & CSS line 72: Renamed element from "div" to "main" and removed redundant class attribute. Renamed CSS line 72 from ".content" to "main".
- HTML lines 29/35 36/42 43/69 & CSS lines 137/146/155/164/168/172/176/181/186: Renamed 3 elements from "div" to "section." Changed all elements to only have a single attribute of type ID. *Fixed link on line 16.
- HTML lines 51/73 & CSS line 78: Renamed element from "div" to "aside" and removed redundant class attribute. Renamed corresponding selector ".benefits" to "aside".
- HTML lines 52/58 59/65 66/72: Renamed elements from "div" to "section".
- HTML line 74 & CSS lines 191/198: Renamed element "div" to "footer" and removed redundant class attribute. Renamed corresponding selector from ".footer" to "footer".

### HTML Elements Restructuring
- HTML line 75; changed h2 element to h4 so headings fall in sequential order


## QUESTIONS:
- When "git add -A" command line responded "warning: in the working copy of 'assets/style.css', CRLF will be replaced by LF the next time Git touches it" 0- What does this mean?
