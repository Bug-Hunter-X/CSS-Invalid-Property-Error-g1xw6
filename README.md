# CSS Invalid Property Error

This repository demonstrates a common yet often overlooked CSS error: using invalid or unsupported properties.  This can lead to unexpected rendering issues across different browsers, especially those that are older or not fully up-to-date.

The `bug.css` file contains the buggy code, while `bugSolution.css` provides a corrected version.

## Problem
The problem lies in using unsupported CSS properties. Some properties might be specific to older browsers, require vendor prefixes, or simply be nonexistent in the CSS specifications.

## Solution
Always refer to up-to-date CSS specifications and browser compatibility charts.  Use vendor prefixes for properties that require them, and ensure properties are valid according to the CSS specification.  Utilize a browser developer tool to debug CSS issues and identify invalid properties.