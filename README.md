# Uncommon HTML Bug: Incorrect Event Listener Attachment
This repository demonstrates an uncommon bug related to event listener attachment in older browsers using the `attachEvent` method instead of `addEventListener`.  The bug affects older Internet Explorer versions primarily.

## Bug Description
The `attachEvent` method is an older way of attaching event listeners that is not supported by all browsers. Using `attachEvent` leads to the event listener not working as expected in modern browsers.  This is an uncommon bug because most developers now use the standardized `addEventListener` method.

## Solution
The solution is simply to use `addEventListener`. This ensures cross-browser compatibility and avoids the bug. 