# CSS Bug: Invalid 'content' Property Usage

This repository demonstrates a common yet subtle error in CSS involving the use of the `url()` function within the `content` property of the `::before` pseudo-element.  The incorrect usage prevents the intended image from being displayed.

## Bug Description

The bug lies in attempting to embed an image directly using `url()` within `content`.  This is not the intended behavior of the `content` property.  Instead, images should be added via `background-image`.

## Solution

The solution demonstrates the correct approach, replacing the problematic `content` property with `background-image`. This ensures proper image display.