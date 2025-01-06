# Tailwind CSS Classes Not Applied Bug

This repository demonstrates a common issue where Tailwind CSS classes fail to apply styles to HTML elements.  The problem stems from incorrect configuration or improper integration of Tailwind into the project. The solution shows how to correctly set up Tailwind for your project to ensure the classes are recognized and applied properly.

## Bug Description

The `bug.html` file contains a div element with Tailwind classes (`bg-red-500` and `p-4`).  Despite the classes, the element remains unstyled because Tailwind is not processing the directives.  This could be due to various reasons such as missing or incorrect Tailwind configuration files, build process issues, or incorrect import statements.

## Solution

The `bugSolution.html` file showcases the corrected version.  It includes the necessary steps to correctly install and configure Tailwind in your project, ensuring the classes are processed and render styles correctly.