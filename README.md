# CSS Specificity Issue

This repository demonstrates a subtle CSS specificity issue that can lead to unexpected behavior. The problem arises when combining ID and class selectors with specific styling rules.

## Description

The `bug.css` file contains a simple example showcasing this issue. The intent is for the `#container.special` selector to override the `#container` selector, but this might not always be the case depending on how the CSS parser handles specificity and the order of the styles.

The `bugSolution.css` file offers solutions to address this problem and ensure the desired outcome.

## How to reproduce

1. Clone this repository.
2. Open `bug.html` (or create a similar HTML file that includes the CSS styles). 
3. Observe the unexpected width of the element. This will depend on your browser and its order of handling.
4. Review `bugSolution.css` to see different ways to solve the problem. 

## Solution

The solutions in `bugSolution.css` highlight methods to resolve the unexpected behavior, enhancing the predictability of the CSS cascade.