# Blue Begone
Chromium extension to block blue checkmark and/or verified users on Twitter.

Basically used Claude to fix on the existing extension by kheina-com that hasn't been updated in about a year: https://github.com/kheina-com/Blue-Blocker

Although eventually resorted to making from scratch using the extension as an inspiration and reference point for methodolgies for how Claude coded a new version that now works.

Currently tried logged in using the default settings that allows business verified and old accounts with blue checkmarks, both of which are toggleable alongside other settings.

By default it will only hide posts via HTML, not actually block the blue checkmark users encountered to avoid heavy API usage.

If you want a script that actually blocks them, there's this one by adalinesimonian: https://gist.github.com/adalinesimonian/b52a753c9fd6c176598745df01ba12dc

<img width="1086" height="443" alt="Default Settings" src="https://github.com/user-attachments/assets/a4b16e09-5d4f-45f7-803e-079b5f2bbabd" />

## Hide verified only in comments

A new toggleable feature added where it only hides blue verified accounts.

Don't mind blue verified account's postings, but absolutely want to hide potential rage baiters in the comment sections?

This also reflects the verified accounts you enabled/disabled, say you still want to see business verified accounts and vice versa.

<img width="1694" height="991" alt="Hide verified only in comments (Censored)" src="https://github.com/user-attachments/assets/9e32c7d8-03fb-4f93-8a49-f1f103ff3977" />

Yes this is the post I'm giving an example of, no I'm not scrolling any further to find a better example, also not willing to showcase anything super political that are the worst offenders.

## Installation:

Enable developer mode in your Chromium browser of choice and load unpacked, selecting the folder you extracted.

Supports Manifest V2 and V3 so even Google Chrome can use it.

## Other Remarks:

There's bound to be issues as I tried briefly on the surface, although it did succeed when searching a controversial topic as it successfully hidden hundreds of blue checkmark posts as indicated by the mismatching longer scroll bar compared to what's actually been loaded.

Currently after trying for a few weeks of regular usage, had no human verification checks or the likes telling me that I'm hitting an API limit.

> [!WARNING]
> Still take the extension as a potential risk.

https://github.com/user-attachments/assets/9964459a-2c44-4971-a46e-14b702fcf227
