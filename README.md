# CSS Specificity Bug

This repository demonstrates a subtle bug related to CSS specificity and inheritance.  The issue involves unexpected behavior when combining nested selectors and the `:first-child` pseudo-class.

## Problem
The `bug.css` file contains CSS code intended to style list items. However, due to a specificity issue, only the first list item is styled correctly.  The other list items are styled unexpectedly.

## Solution
The `bugSolution.css` file provides a corrected version of the CSS, addressing the specificity problem and ensuring all list items are styled as intended.

## How to Reproduce
1. Clone this repository.
2. Open `bug.html` (you'll need to create a simple HTML file with a list to test). 
3. Observe the unexpected styling of the list items.
4. Replace `bug.css` with `bugSolution.css` and observe the corrected styling.