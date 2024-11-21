Chrome Version : <Copy from: 'about:version'>
URLs (if applicable) :
## Other browsers tested

Add OK or FAIL, along with the version, after other browsers where you
have tested this issue:
Safari:
Firefox: Returns false
Edge:

Let's say you have a hierarchy on node as follow:

element1 > element2 > element3

## What steps will reproduce the problem
(1)
Add an event listener on document.body to catch any click passing through the page.
log whether the event.target contains element1.
(2)
Click on element1
(3)
Chrome returns true

## What is the expected result

returns false

## What happens instead

returns true

Please provide any additional information below. Attach a screenshot if
possible.
