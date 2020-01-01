---
title: MacBook Pro Touch ID stopped working
description: This is a post on mnclife about fixing issues related to MacBook Pro Touch ID.
date: Last Modified
tags:
  - Mac
layout: layouts/post.njk
---

As a developer, you often end up in the issues related to the development environment. I use the **MacBook Pro (15-inch, 2019)** model for my development activities and configured Touch ID for unlocking my Mac. Everything was well until I changed my Mac password. From then on, I had to manually type my password every time to unlock Mac as the Touch ID stopped working.

## Solution

The solution that worked for me was to reset Mac SMC (System Management Controller).

What is SMC?

The SMC is responsible for hardware and other low-level functions on Intel-based Mac computers

How to reset SMC on Mac?

The procedure is different based on the Mac model.

For MacBook Pro (15-inch, 2019), press **Shift + Control + Option** on the left side of the built-in keyboard, then press the power button at the same time. Hold these keys and the power button for 10-20 seconds.

For other models see the [Links](#links)

---

After resetting SMC, I had to set up my Touch ID again.

Finally, I'm able to use my Touch ID  &#128515;

### Links

<https://support.apple.com/en-us/HT201295>
