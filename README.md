# Unblockers

Disclaimer: I am not responsible for any damage done to your Chromebook, nor will I do anything about it. If you need help, open an issue. None of these will bypass network blocks.

## I need more please fork this

# extension corrupter/abc hack
Discovered by ?
Works on any extension
## Works on 119. (not tested on 120+)
### Requirements
###   Bookmarklets unblocked
###   Bookmarks shown
1. Find your extension ID. This can be done by going to `chrome://extensions/`, clicking on "Details" on the extension you want to block, and copying what comes after `id` in the search bar (e.g. haldlgldplgnggkjaafhelgiaglafanh for GoGuardian)
2. Go to ```chrome-extention://`YOUR-ID-HERE`/manifest.json```, making sure to replace `YOUR-ID-HERE` with the actual ID of your extension.
3. Drag [this](chrome://hang/) and [this other thing](chrome://kill) into your bookmarks bar.
4. On manifest.json, click on the first bookmark (hang)
5. Quickly reload
6. Click the other bookmark rapidly
This absolutely disables any extension. Works until sign out.

# GetGone for GoGuardian
Discovered by ?
GoGuardian
## Works on 120
### Requirements 
###   GoGuardian

1. Turn off internet
2. Sign out
3. sign back in with any account
4. Open a new tab, do not go to any link yet.
5. Click rapidly on the GoGuardian extension (not license) for about 45 seconds. It should be pinned.
6. If it turns a dark grey, it worked, else, go back to step 2.
This absolutely disables GoGuardian, it will not function. This lasts until sign out.
