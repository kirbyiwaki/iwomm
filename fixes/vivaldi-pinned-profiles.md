---
title: Create custom pinned icons for additional Vivaldi profiles
tags: browser, vivaldi, taskbar, shortcut, icon
---

Vivaldi allows you to create multiple profiles, but it's difficult to pin each of them to the taskbar. Here's how to do it:

1. Create a desktop shortcut for each profile.
   - If you're making the profile, select "Create Desktop Shortcut" while making it.
   - If the profile already exists, right click on desktop > New > Shortcut, then enter `C:\Users\YourUsername\AppData\Local\Vivaldi\Application\vivaldi.exe --profile-directory="Profile 1"` into the location field. Replace "YourUsername" with your actual username and "Profile 1" with the actual profile directory name (e.g. "Profile 2", "Profile 3", etc.).
2. Right click on the desktop shortcut and change the icon to the desired custom icon.
3. Right click on the desktop shortcut and select "Pin to taskbar".

---
*UNTESTED*

This may solve the same problem for other Chromium-based browsers, just use the path to the browser's executable and the profile directory.
For example:
- Chrome: `C:\Program Files\Google\Chrome\Application\chrome.exe --profile-directory="Profile 1"`
- Edge: `C:\Program Files (x86)\Microsoft\Edge\Application\msedge.exe --profile-directory="Profile 1"`
- Opera: `C:\Users\YourUsername\AppData\Local\Programs\Opera\launcher.exe --profile-directory="Profile 1"`
- Brave: `C:\Program Files\BraveSoftware\Brave-Browser\Application\brave.exe --profile-directory="Profile 1"`