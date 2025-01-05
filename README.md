# CSS Specificity and Inheritance Bug

This repository demonstrates a subtle bug related to CSS specificity and inheritance.  The problem involves unexpected color inheritance when a style is applied to nested elements.

## Bug Description
The CSS code contains rules for `<div>`, `<p>`, and nested `<div><p>` elements. The goal is for the nested `<p>` element to display text in green, overriding styles applied to both the parent `<div>` and the `<p>` element. However, depending on how specificity is handled, the expected result might not occur.

## How to Reproduce
1. Clone the repository.
2. Open `bug.css` to see the problematic code.
3. Create an HTML file (e.g., `index.html`) containing nested `<div>` and `<p>` elements.
4. Link `bug.css` to your HTML file.
5. Observe that the text color of the nested `<p>` element might not be green as intended.

## Solution
Refer to `bugSolution.css` for a solution that correctly handles specificity to achieve the expected behavior.

## Note
This bug highlights the importance of understanding CSS specificity when dealing with nested elements and style inheritance.