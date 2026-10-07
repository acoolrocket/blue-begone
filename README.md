# blue-begone
Chromium extension to block blue checkmark and/or verified users on Twitter.

Basically used Claude to fix on the existing extension by kheina-com that hasn't been updated in about a year: https://github.com/kheina-com/Blue-Blocker

Although eventually resorted to making from scratch using the extension as an inspiration and reference point for methodolgies for how Claude coded a new version that now works.

Currently tried logged in using the default settings that allows business verified and old accounts with blue checkmarks, both of which are toggleable alongside other settings.

By default it will only hide posts via HTML, not actually block the blue checkmark users encountered to avoid heavy API callouts.

If you want a script that actually blocks them, there's this one by adalinesimonian: https://gist.github.com/adalinesimonian/b52a753c9fd6c176598745df01ba12dc

<img width="352" height="478" alt="Settings" src="https://github.com/user-attachments/assets/2fd223ef-2baa-4921-a75d-24a2e96a7049" />

## Installation:

Enable developer mode in your Chromium browser of choice and load unpacked, selecting the folder you extracted.

## Other Remarks:

There's bound to be issues as I tried briefly on the surface, although it did succeed when searching a controversial topic as it successfully hidden hundreds of blue checkmark posts as indicated by the mismatching longer scroll bar compared to what's actually been loaded.

Supports Manifest V2 and V3 so even Google Chrome can use it.

Do note to take this extension as a risk as its uncertain how many API calls it does in normal usage that might at worst be bannable.
