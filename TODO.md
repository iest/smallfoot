TODO
====

Basics
------

- [ ] Find all footnotes on page, pull in content, remove original footnote
- [ ] Create button where superscript was, add original footnote content to `data-smallfoot-note`
- [ ] On click, append footnote to page, adding content to the data-attribute


Advanced
--------

- [ ] Position the footnote horizontally correctly
- [ ] Position the footnote vertically correctly
- [ ] Position the pointy triangle to be in the correct orientation and horizontal position
- [ ] Reposition on window resize

Vertical position mechanics:

- Get vertical position of button
- If space below button > footnote max-height (precalculated), render below
- else render above

Horizontal position mechanics

- Footnote basic style is 100% width
- umm...
