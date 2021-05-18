---
title: "Providing Great Support"
date: 2021-05-18T19:18:30+01:00
draft: false
---


# Github apps
When adding apps to Github Orgs we might be exposing information and code to the app developer creating a security risk to our intellectual property and even exposing tools, websites, or applications of getting malicious code injected into them.  
My recommendations would be the following to handle this situation:
  - Initial audit to the application by checking the permissions it requests.
  - Apply the principle of least privilege by only adding it to the needed repositories containing the risk to the whole Github Org.
  - Perform a background check to ensure the organization or developer behind an application is legitimate and credible enough.
  - Validate how robust is the application’s security posture. In case they suffer a breach, you might also be a victim of the attack
I would also try to engage with the user to make him understand why we need to do this but also make him feel involved and a vital part of a strong security culture in our company.

"Dear user,  
We know that this app might be critical to your work but let's first evaluate the permissions that the application request so we can evaluate the risks and plan ahead mitigations if we have any issue.  
Let's also apply the principle of least privilege and add it only to the repo where it is needed, so if you can provide a list of them that would be very helpful in keeping all Protocol Labs more secure without blocking any of your work.  
If you don't mind we would also like to monitor the activity of this application in the first 30 days so we can understand it even better."

# Website fire
I would start by visiting the website myself, to check if the website displays fine and be sure this is not an issue local to the user computer, connection, or site.  
Next, I would ask the user to ping the website and do a dig command to put connectivity and DNS solving out of the equation.  
After these steps, I would query the user if the outage is related to any type of change to the website so I could move to troubleshoot all the components involved in a website, like CDN, web server, database but with a high priority on the place where the change happened.
