# CSS Specificity Bug with !important

This repository demonstrates a subtle bug in CSS related to specificity and the `!important` declaration.  The `bug.css` file contains the erroneous code, while `bugSolution.css` provides a corrected version.

The issue arises when trying to override a style rule containing `!important` with a more specific selector.  The `!important` flag overrides the specificity, producing unexpected results.  The solution showcases alternative approaches to resolve this without relying on `!important`.