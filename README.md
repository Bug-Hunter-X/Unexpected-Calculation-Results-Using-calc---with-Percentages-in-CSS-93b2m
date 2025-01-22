# Unexpected Calculation Results Using calc() with Percentages in CSS

This repository demonstrates a subtle bug involving the CSS `calc()` function when combining percentages and other units. The expected calculation does not match the rendered result.

## Bug Description
The `calc()` function in CSS is designed to perform calculations directly within the stylesheet. However, there can be unexpected behavior when combining percentages with other units like pixels or ems.  This can lead to layout inconsistencies or unexpected rendering.

## Steps to Reproduce
1. Clone this repository.
2. Open `bug.css` and observe the incorrect calculation in the `.element` style.
3. Open `bugSolution.css` to see one approach towards solving the issue.

## Solution
One common approach to resolve issues related to percentage calculations in `calc()` is to ensure that you're applying units consistently and that the context of the percentages is clearly defined. Sometimes the calculation order and the units involved can affect results.