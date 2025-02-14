# Uncommon HTML Error: Non-String in innerHTML

This repository demonstrates an uncommon error in HTML related to using a non-string value when setting the `innerHTML` property of an element.  The error does not throw a Javascript error, but it can lead to unexpected behaviour.

## The Problem
The `innerHTML` property expects a string value.  When a non-string (such as a number or object) is passed, it won't cause a Javascript error.  Instead, it will either result in no changes being made or potentially unexpected results depending on the browser's handling of the situation.