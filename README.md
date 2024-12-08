# Uncommon HTML Bug: Duplicate Event Listeners

This repository demonstrates an uncommon bug in HTML related to adding multiple event listeners to the same element using both the `onclick` property and the `addEventListener()` method. This can lead to unexpected behavior, such as duplicate alerts or other unintended consequences.

## Bug Description

The `bug.html` file contains an HTML structure with a `<div>` element.  Event listeners are added to this `<div>` using both the traditional `onclick` property and the more modern `addEventListener()` method.  This redundancy results in the alert being triggered twice upon clicking the div.

## Solution

The `bugSolution.html` file demonstrates the corrected approach. It uses only one method to attach the event listener to avoid the duplicated execution.