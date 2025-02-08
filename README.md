# Missing Closing Quote in img src Attribute

This repository demonstrates a common, yet easily overlooked, error in HTML: a missing closing quote in the `src` attribute of an `<img>` tag. While many browsers try their best to interpret the code, this can cause unexpected issues, such as incorrect image loading, errors, or inconsistent rendering across different browsers.

## The Problem

A missing closing quote in the `src` attribute will usually not result in an immediate error message. Instead, the browser will often try to guess at the intended filename.  This guess might be completely wrong, leading to a broken image or unexpected consequences.

## The Solution

Ensuring that the `src` attribute is correctly enclosed within double quotes is crucial for reliable image loading. The `solution.html` file shows the corrected code.

## How to Reproduce

1. Open `bug.html` in your browser.
2. Observe the broken image.
3. Open `solution.html` in your browser.
4. Observe the correctly displayed image.