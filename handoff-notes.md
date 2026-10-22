# Developer handoff notes

## What I delivered
Built a static customer support page for Northstar Services with contact information, support hours in CST, and a reminder to include an order number. In the response to the product manager's request, I added a FAQ section explaining how to check order status. Also, added support-checklist.md to document the manual checks. 

## How I verified the page
I opened index.html in my browser and confirmed that the styling loaded and the title displayed. I then went through each item in the support-checklist.md. I resized the browser window to verify that the page adjusted to the resizing. 

## Remote change I received
A team member added a "Support escalation" section to README.md saying unresolved billing request go to the billing team after one business day. I received it by running git pull --ff-only origin main, and the new section then appeared in my local README and the commit appeared in my git log. 

## Git workflow explanation
git commit only saves a snapshot to my local repository history. GitHub is a separate remote copy, so it did not change until I ran git push origin main to upload my local commits. Likewise, my local files did not update when the README changed on GitHub until I ran git pull. 