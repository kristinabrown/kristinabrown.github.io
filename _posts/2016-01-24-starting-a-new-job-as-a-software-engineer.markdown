---
layout: post
title:  "Starting A New Job As A Software Engineer"
date:   2016-01-24
categories: Software Engineering
---

No matter how much you know about software development, how good you are at writing code, or how many languages you know the first few exposures that you have to a new application can and will be a bit mind boggling. Getting up to speed a new-to-you project is a skill unto itself, and is something that should be valued and practiced and thoughtful. I have a list of places I look to first when getting up
to speed with a new app or project. It is also worth mentioning that "and ask questions" can and should be appended to every single bullet point.

* **Documentation:** Read the Wiki or whatever your team uses for documentation. Your team doesn't have documentation? That is, unfortunately, not totally uncommon, take the lead in getting the documentation started or up to date.

* **Tools:** Take note of what tools are used, and if there is anything new to you take a moment to do a quick look up of what it's all about. You notice that html files are in slim and you're used to erb, look it up.

* **Bugs:** Check out what bugs are being reported. My first week as a software engineer at Blue Bottle Coffee I volunteered to receive and triage bugs reported by our customer service team, it helped me get up to date with some of the more painful points of our main application.

* **Jobs:** This is kind of a weird one, but I find it very useful to just look through the regular running jobs. This can produce some of the most fruitful questions too, for example what's the difference between `OrderFulfillmentJob` and `OrderItemFulfillmentJob`.

* **Tests:** Look through tests to not only see what is being tested but how they are set up. It's really helpful to start to understand that you need instances of a product, a variant, a shipment cycle, and a plan all within a subscription test. And if your new team doesn't have any tests, this is a good time to start to question some recent life decisions.
