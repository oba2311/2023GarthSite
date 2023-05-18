---
layout: post
title: "We increased conversion rates by over 20% doing this"
date: 2022-06-29
categories: [product, Growth, Consumer]
---

#### KEY TIPS AND TRICKS TO GROWTH-HACK SAAS ONBOARDING

Everything you need to know to drastically improve your SaaS onboarding completion rates.

(Published on Medium/Bootcamp - https://medium.com/p/f596d8a23f79)


<img src="{{ site.baseurl }}/assets/images/onboardingGloat1.png" alt="onboardingGloat1" class="right" width="60%" height="60%">

#### Increase completion rates focusing on the following aspects

It is the end of 2021 and I’m leading the Growth Team for a B2B2E company (E=employees) in HRTech SaaS. We are deciding to tackle a well-known growth challenge — improving the product’s onboarding.

Any growth PM runs into this challenge at some point or another so here’s what worked for us. This is how we were able to increase E2E completion rates by over 19% and at the same time improve data contribution significantly.

TL;DR — here’s the formula:

1. Test and improve copy.
2. Use autosuggestions for form fields where you can.
3. Make it configurable.
4. Reduce clutter and unnecessary inputs.
5. Think about measurements and critical data from the get-go.
6. Optimization and testing.

---


The underlying assumptions we worked with were:

- Our holy grail is activation, which is “apply” for an opportunity (we are a talent marketplace :) ). More on that in a future post. This article is a great source to learn about activation.
- As a B2B2E, every feature in our product has two kinds of stakeholders — the end-users, and our clients. This is also true for the onboarding:
    - We want our users to be activated, and our clients want to get to know their employees better. These two goals aren’t the same, there is a clear tradeoff to manage.
- Our design is constrained by our business’s strong selling points, and what sales had sold in the demo. This is not uncommon for B2B / B2B2E / B2B2C companies.

#### Iterate to find the perfect copy, make it configurable, and implement autosuggestions

Here’s what worked for us:

- Start with the end goal in mind:
    - What are you optimizing for? Completion rates? Data contribution? Be specific. “We want to get as much data about users as we can” is not specific.

- Say you are working on an Insure-tech product, a good version would be more like:
    - “Our model uses street address as one of the most important parameters and therefore it is key to get this data point during onboarding when users have high intent”.

- When it comes to completion rates — when we researched (and huge kudos to our designers Maayan Yudovitch and Omri Dvir for extensive research), we noticed a pattern — there is probably a pretty low correlation between the total number of screens/modals and completion rates.
    - Remember this rule of thumb: it is not about the number of screens / steps, but about the friction in every one of those.

- Takeaway: reverse engineer the current onboarding to key data points.

- We took the existing onboarding experience and went through each one of the data fields and asked ourselves — does this info would lead to higher activation rates? How so?

- Result: We ended up cutting more than 30% of the original data inputs we’d had.


#### Copy and Localization

You’d be surprised how far copy will go. Since the onboarding is the first handshake a user would have with the product, it is all the more important to check whether your copy is in-line with best practices:

- What’s in it for the user: Users aren’t looking for features, they are looking for value. When finalizing copy ask yourselves — what’s in it for them? Why would they care?

- Make sure that a language-picker, if you have one, comes first. If you go as far as letting users use their language — let them use it from the get-go.

- Action: We hired a UX writer and redid the copy throughout. We asked ourselves Qs like: what is the average age of our users? How can we use the page’s title to create a hook? How can we cut # of words in half?

- Results: higher comprehension, higher completion rates.

To learn more: [https://www.omerbenami.com/](https://www.omerbenami.com/)

#### Configurability and Optimization

When we wanted to A/B-test the old version for the onboarding we couldn’t since many things were hard-coded. This time we planned to build everything configurable such that we can test pretty much whatever we want going forward. This is a great piece about testing challenges you might want to check.

- Action: we’ve done 2 things to prepare the ground for testing:
    - Dynamic infra — we built the infra to play with screen order. Simple JSON file and we can play with it.
    - We listed our most desired tests and built with those in mind.

- Pro-tip for PMs: Try to think in advance which tests you would want to run so you can inform your team and build accordingly.

- Results: We can run any experiment we might want.

Consult this outstanding article for cases where testing is not possible.

#### Friction Minimization with autosuggestions

A handy rule of thumb: The more demanding a data field is to fill in, the easier the fill-in pattern should be. We noticed that autocomplete works like magic. And it works for others as well.

- Users much prefer to click one time rather than type a couple of words — that’s not surprising, and nevertheless, if you read this article there’s a high chance that the product you are working on doesn’t leverage autosuggestions. This is probably the critical factor that led to more and higher-quality data.

- Takeaway: We collected within the first 72 hours more data than the entire year before.

Declutter UI, design around predefined KPIs, and always be testing!

#### Data and measurement

This might sound obvious, but bear with me and you’d be surprised.

- The older version was built a while back, a couple of years ago, and the metrics didn’t change since then (we use internal KPIs, not rocket science at all, but the details are beside the point).

- It is super useful to think in advance about top metrics and key KPIs you’d want to measure so you can plan your events accordingly. This will allow you to have a war-room / launch room shortly after the launch (more on that in a future post ;) ).

- Actions: sit with your BI / Data Engineering and map events accordingly. That is often a step missed and it is too important to fall between the cracks.

- Results: We measured key KPIs from day1, with full flexibility to measure granular data points anywhere in the user flow.

If this kind of content interests you, read more here, and follow me on Medium. For product leadership content listen on [https://www.productfm.com/](https://www.productfm.com/)

To learn more: [https://www.omerbenami.com/](https://www.omerbenami.com/)

---
#### Good resources on onboarding and activation:

- Improve activation with those tips: [https://userpilot.com/blog/improve-user-activation/](https://userpilot.com/blog/improve-user-activation/)
- Onboarding best practices: [https://userpilot.com/blog/user-onboarding-best-practices/](https://userpilot.com/blog/user-onboarding-best-practices/)
- Improve your copy in 1 minute: [https://medium.com/@ayat/5-brilliant-e-commerce-copy-testing-ideas-to-try-right-now-a46a5de1859b](https://medium.com/@ayat/5-brilliant-e-commerce-copy-testing-ideas-to-try-right-now-a46a5de1859b)
- What you can and should test: [https://analucianovak.medium.com/17-things-you-need-to-test-regularly-c011b7db5d72](https://analucianovak.medium.com/17-things-you-need-to-test-regularly-c011b7db5d72)
- Great AB testing intro: [https://medium.com/swlh/what-every-product-manager-should-know-about-ab-testing-7e7619fe4533](https://medium.com/swlh/what-every-product-manager-should-know-about-ab-testing-7e7619fe4533)

Tags: UX Design, Product Management, Conversion Optimization, SaaS, Growth Hacking

