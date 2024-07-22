# ExpressiveWriter (expressivewriter)

Private journal and article writing, on the web.

This started as a semi-commercial project many years ago. Those requirements morphed over those years and this application both takes the leats-friction route to a writing application and
employs one of the least-friction technologies with-which to get there.

## Application Architecture
This is a Progressive Web Application, for personal use. There are no plans to make this into any Store-based applications for two simple reasons:
1. Being an application for my own use, I see no gain in spening time, money and effort complying with the numerous App Store requirements. Apple has an annual Tax even for ad-hoc distribution, Google requries 20+ co-testers and Microsoft can not help my mobile desires.
2. Further, writing is such an important aspect of my life that I'd not wish to create an envelope in which others sought to write and then, merely due to the vaguaries of life, stop maintaining it.

As for functionality, I have tested that the PWA architecture, using the browser's `IndexedDB` database **does** persist for at least three weeks on iOS 17.6+ and macOS Sonoma; having tested it on my personal devices for applications such as the web version of the commerical [Day One](https://dayoneapp.com/web/). Android/Windows has, of course, long been similarly good. A review of my feature matrix over the years has shown that a very, very high percentage of all desired features can be implemented on that web.

Long-term persistence will be to some form of personal Cloud Drive. I suspect that it will have to be Google Drive (or even Microsoft's OneDrive) as Apple mandate an App Store presence in order to be given a CloudKit container for an App. Data will be *managed* such that the articles themselves are not accessible in the file system. I have tried document-based applications as [Obsidian](https://obsidian.md/) and one of the few shortcommings is that their very-visible file system *gets in the way of the clarity of the writing experience".


