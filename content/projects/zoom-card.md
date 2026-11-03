+++
title = '9aclass.net + Zoom card'
date = 2020-07-21T21:11:28+07:00
description = "a 'phonebook' for online classes during the pandemic. Pure HTML+CSS+JS"
draft = false
+++

Remember online classes?

9aclass.net was built on Google Site, to serve as a 'phonebook' with the meeting code, password, and link for each classroom listed.

The search directory was built to be really simple. If one needed to look up, the meeting link for, say, math class, one simply needed to type:
9aclass.net/math

But typically, students wouldn't need to manually search the meeting details thanks to the Zoom card. But it is good to have the search function especially when the Zoom card fails to serve the right information (see later).

The Zoom card is exactly what it sounds like: a tiny rectangle that will automatically generate the meeting code, password, link according to the schedule. See the demo below:

{{< mainframe >}}

\+ a notification feature (if enabled) on the browser to remind students 5 minutes before class starts.

---

Looking back, I wished the card wasn't incredibly hard-coded. If a Math class would be swapped with History class tomorrow, one would have to dig through the messy JS code to update the information and revert them back to the regular, weekly schedule (inside convoluted arrays) when the class has finished.

