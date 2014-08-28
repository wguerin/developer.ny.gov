---
layout: post
title: Browser Support Guidelines
---

- Focus and Scope
    - The guidelines apply to all sites and web apps, both public-facing and internal
- Define “support”
    - Market share threshold: cover ~95% of users
        - For now, look at the top 95% of desktop and the top 95% of mobile separately. Mobile is small now but will grow once we have more mobile-friendly sites so we want to make sure those don't get lost when looking at overall (desktop + mobile) stats.
        - 95% is not a hard and fast rule — find a good cut off point that doesn't leave a significant number of users right on the cusp of support/non-support
    - Support features, not browsers
        - It's not necessary to fully support all features
    - What experience should "other" features and browsers present to the user
- Guidelines and principles
    - Always serve functional HTML
    - Progressive enhancement for JavaScript and advanced CSS
        - Not too detailed — testing group will cover best practices
    - Don't create Java/Flash applets — write in HTML/CSS/JS
- Outlier support
    - What agencies with exceptional/unusual needs should do
    - Data to support any exceptions
- Legacy support
    - What should be done for old browsers that require more maintenance but can't be ignored (e.g. IE7)
- List of supported browsers
    - "All of them"
        - "Future friendly" http://futurefriendlyweb.com
    - Define both a goal to aim for (the newest, most capable browsers) as well as a minimum requirement
    - Take into account what we need to provide vendors with a more formal list
