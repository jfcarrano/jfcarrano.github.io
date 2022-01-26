---
title: "Learning to walk again: starting a digital media survey"
date: 2022-01-25T20:45:52-05:00
slug: mit-digital-media-survey-01
tags: ["archives", "digital media", "survey"]
draft: false
---

In Ricky Erway's foundational instructional guide, ["You've Got to Walk Before You Can Run: First Steps for Managing Born-Digital Content Received on Physical Media"](https://www.oclc.org/research/publications/2012/oclcresearch-managing-born-digital-physical-media.html), we learn that "walk" in this context means to know about the physical media that you have in your collection, the where, the how much, and the what type. This is also related to the archival principles of [physical](https://dictionary.archivists.org/entry/physical-control.html) and [intellectual control](https://dictionary.archivists.org/entry/intellectual-control.html) of collections. This report inspired many archival institutions to begin surveying their collections for born-digital media as a basic starting point to approaching born-digital processing. The trend included multiple rounds of [SAA's "Jump-in" initiative](https://www2.archivists.org/groups/manuscript-repositories-section/jump-in-initiative-0) which encouraged repositories to do surveys and share their results. 

Where I work, the MIT Libraries, for various reasons, did not do a survey or partake in the Jump-in initiatives. There were efforts to survey some collections but there wasn't anything comprehensive. At the same time, there was some transfer of material off of digital media found in collections. So we weren't walking or jumping but we would do random sprints and then collapse into a crawl, gasping for breath while working on other projects that came along.

In recent years, I've worked to formalize our [procedures for transferring content](https://wikis.mit.edu/confluence/x/8xmuC) off of born-digital physical media and I feel like we're in a good place to do that work for common media types. In 2019, I began the start of work for a media survey but was delayed due to the pandemic (surprise!). When I regained the ability to access the collections again in fall 2021, I began the survey work in earnest.

## Goals

In starting this work I have a few goals for what we hope to get out of it. As you might expect, I want to figure out what media we have and where it is! Beyond this simple knowledge, doing this work will give us a more holistic understanding of the media in our collection that can inform our future processing efforts, appraisal, staffing, and what equipment we may need. While all of this media is at some level of risk remaining stored in these formats, knowing the collections that contain the media can help us take an EDISJ approach in prioritizing the transfer of content by and about white women and people of color of all genders.

## Looking for leads

We started the survey process by developing a list of terms related to digital media, which we could then search for in our ArchivesSpace repository and create a report from the API with: Floppy, Floppies, Disc, Discs, Disk, Disks, Diskette, Diskettes, CD, CDs, CD-rom, CD-roms, DVD, DVDs, USB, Hard drive, Flash drive, Digital, Zip, Data tape, Data tapes, Thumb drive, Backup, Backups, Cartridge, Cartridges.

Using this list we ended up with a pretty long CSV of possible elements within finding aids and accessions to investigate. To make this list a little more manageable, I separated out the terms that were the result of just searching "digital" to possibly work on at a later stage of the process, as these would most like contain the most false positives.

I started going through the remaining list for any false positives or duplicate entries. We ended up with 545 entries, which isn't that solid of a number as in many cases I can't tell whether description is in aggregate or an item level. I used formulas to total up the frequency per search term and the number of results per archival collection which I can use as a starting point to figure out which collections to call first. I then took the paired down list and bulk imported them into an Aeon "activity" for eventually requesting their boxes from storage.

## How to record survey results

In planning for this survey we needed a method to record our results once the boxes are called from storage and we get that sweet plastic, magnetic, and optical substrate into our hands. That's where the media log will come in!

Archivists at other institutions developed multiple media logs ([NYU](https://github.com/NYULibraries/medialog) and [Rockefeller Archive Center](https://github.com/RockefellerArchiveCenter/dm_log), for instance) for similar situations as us, recording the presence of digital media in collections, it's type, and whether the content has been migrated to a more accessible medium. These other instances caught the eye of staff members here years ago and we had [a version that was spun up for us](https://github.com/MITLibraries/adml) (but rewritten in Java, not sure why...). The app sat largely unused since that time, when the pandemic started it was fully taken offline due to a need of a infrastructure migration and the realization that it wouldn't be used for some time.

As part of the survey prep we decided to get the app running again because it seemed like it would fit our needs. This took a little while with some support from staff in digital library services but we're back up and running. We made some minor additions for things that might be useful like label info and categories of media that weren't present but the app largely remains similar.

## Next steps

With all this geared up, we were hoping to get started with actually *doing* the survey at the start of this new year but with the pandemic raging I've been fully working from home this past month. Delayed again! But what can you do? Before going remote again, I already had done some calculations based on the number of boxes I'm allowed to call to campus (we use offsite storage), the number of days I work on campus during a week, and the time to do the survey against the time remaining and it would be impossible to finish by the end of the fiscal year (when I wanted to complete the survey).

So even with the month delay, things were already a bit behind. I'm ready to push ahead with the actual survey regardless of the time it takes and hope to share some more updates along the way!
