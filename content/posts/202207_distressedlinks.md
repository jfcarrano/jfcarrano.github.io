---
title: "Distressed Links"
date: 2022-07-13T08:50:02-04:00
slug: distressed-links
tags: ["web archives", "link rot"]
draft: false
---

At work I've been crawling some form of the [MIT COVID-19 response webpage](https://now.mit.edu/) daily since early March 2020. In that time there have been a couple of domain name switches but it's been pretty boring considering the scope and tragedy of the ongoing pandemic.

In June, I was reviewing some of our crawl reports for this seed and I noticed an unusual url in the host report: archive.org, i.e. the big brother of Archive-It, THE (with no respect to Ohio State) Internet Archive. Obviously, this shouldn't happen unless the site was actually linking out to IA.

After some investigation, I found that there were a few links to IA! *It's web archives all the way down.* The strange thing was that the links were on the MIT Travel policy page, pointing to information from [the Department of State](https://travel.state.gov/content/travel/en/traveladvisories/traveladvisories.html/) and [the CDC](https://www.cdc.gov/coronavirus/2019-ncov/travelers/map-and-travel-notices.html) (under "Additional Resources") that is still actively maintained and people would need the most up-to-date information about. Instead, they were getting pandemic related travel info from late March!

Checking out the [Archive-it Wayback captures for the MIT travel page](https://wayback.archive-it.org/7963/*/https://now.mit.edu/policies/mit-travel-policy/), I saw that this change happened around May 11. You can see the proper links on [May 9](https://wayback.archive-it.org/7963/20220509093052/https://now.mit.edu/policies/mit-travel-policy/) but then those links are removed on [May 11](https://wayback.archive-it.org/7963/20220511014346/https://now.mit.edu/policies/mit-travel-policy/) and then added back in [later in the day](https://wayback.archive-it.org/7963/20220511205440/https://now.mit.edu/policies/mit-travel-policy/), but replaced with IA Wayback links. Weird! For their part, I was able to find the maintainers of the website and they fixed the links pretty quickly.

They didn't tell me how this might of occurred but we can speculate a couple scenarios:

1. Somebody accidently deleted those links when updating the website and had to go into IA out of ease or necessity to find what was there before. They then did a simple copy+paste instead of editing out the Wayback url prefix. In any event, maintain backups!
2. Or some link checking plug-in went awry and inserted a Wayback link in place of the original links, due to an error saying the page was no longer available (temporary 404, etc.).

Either way, the result was that the content was made to look outdated or old, kind of like how you can distress a piece of furniture to make it look vintage. I'm not about to yuck anyone's yum but neither of those things are for me. While there was no ill intent here, you can see how easy it is to spread misinformation this way, especially if people aren't looking closely. The pandemic isn't over and people need up-to-date information to inform their decisions. 

Link rot is a real problem and web archives have a place to play in mitigating that in information resources. However, current information shouldn't be replaced by a snapshot of something in time.  If we're going to insert archived links into web pages either manually or via automation, the solutions to display them are already out there such as [robust links](https://robustlinks.mementoweb.org/), where you can display both a current link and a web archived version very easily. You've then got the up-to-date info and a web archived link just in case.  Make your links robust, not distressed!
