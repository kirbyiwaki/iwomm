---
title: Create custom pinned icons for additional Vivaldi profiles
tags: browser, vivaldi, taskbar, shortcut, icon
---

Vivaldi allows you to create multiple profiles, but it's difficult to pin each of them to the taskbar with custom icons. Here's how to do it:

1. Create a desktop shortcut for each profile.
   - If you're making the profile, select "Create Desktop Shortcut" while making it.
   - If the profile already exists, right click on desktop > New > Shortcut, then enter `C:\Users\YourUsername\AppData\Local\Vivaldi\Application\vivaldi.exe --profile-directory="Profile 1"` into the location field. Replace "YourUsername" with your actual username and "Profile 1" with the actual profile directory name (e.g. "Profile 2", "Profile 3", etc.).
2. Open vivaldi from the shortcut, it should open with your target profile.
3. Right click on the Vivaldi icon in the taskbar and select "Pin to taskbar".
4. Right click on the Vivaldi icon in the taskbar again, right click on the profile name and select properties.
5. Make sure the location field is the same as in step 1 (`C:\Users\YourUsername\AppData\Local\Vivaldi\Application\vivaldi.exe --profile-directory="Profile 1"`), edit it again if it reverted.
6. Change the icon to your custom icon (you may need to restart Explorer.exe for it to update).
7. Repeat for all profiles.

---
*UNTESTED*

This may solve the same problem for other Chromium-based browsers, just use the path to the browser's executable and the profile directory.
For example:
- Chrome: `C:\Program Files\Google\Chrome\Application\chrome.exe --profile-directory="Profile 1"`
- Edge: `C:\Program Files (x86)\Microsoft\Edge\Application\msedge.exe --profile-directory="Profile 1"`
- Opera: `C:\Users\YourUsername\AppData\Local\Programs\Opera\launcher.exe --profile-directory="Profile 1"`
- Brave: `C:\Program Files\BraveSoftware\Brave-Browser\Application\brave.exe --profile-directory="Profile 1"`