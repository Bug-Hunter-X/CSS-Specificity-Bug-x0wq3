# CSS Specificity Bug

This repository demonstrates a common issue in CSS: unexpected styling behavior due to conflicting selector specificity.

The `bug.css` file contains the buggy CSS, and `bugSolution.css` provides a fix.  The issue arises from the conflict between inline styles and class selectors. The inline style has higher specificity, overriding the class styles. The solution involves understanding and carefully managing CSS specificity.

## Setup

1. Clone this repository.
2. Open `index.html` in your browser.

You'll observe that the intended styling (from the class selector) is not applied.