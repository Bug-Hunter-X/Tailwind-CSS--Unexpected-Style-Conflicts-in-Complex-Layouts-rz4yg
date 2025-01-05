# Tailwind CSS: Unexpected Style Conflicts in Complex Layouts

This repository demonstrates a common bug encountered when using Tailwind CSS in complex layouts, specifically where nested components or conditional rendering lead to unintended style conflicts. The bug manifests as unexpected visual glitches or layout deviations from the intended design. This is often due to the utility-first approach and difficulties in managing style specificity.

The `bug.html` file showcases the problematic layout. The `bugSolution.html` file provides a solution using techniques to mitigate style conflicts and improve specificity.

## Bug Reproduction

1. Clone this repository.
2. Open `bug.html` in your browser.
3. Observe the unexpected layout issues.

## Solution

The `bugSolution.html` file demonstrates how to resolve the bug by applying the following strategies:

*   **Improved class naming:** Using more specific and descriptive class names to avoid naming collisions and ensure better style specificity.
*   **Scoped Styles:** Encapsulating styles within specific components to prevent unintended global style application.
*   **`@layer` directives:** Using `@layer` to override styles and ensure precedence.
*   **Parent-Child Specificity:** Carefully planning class names to control specificity between parent and child components.

This example highlights the importance of careful planning, clean class naming, and understanding Tailwind's specificity rules when building complex layouts.  The solution showcases how using these practices can solve common issues.
