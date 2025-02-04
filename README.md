# MX Keys Mini Media Control Workaround (MacOS)

So, you got yourself an Logitech MX Keys Mini and just realized it doesn’t have previous/next media keys? Yep, that sucks. But don’t worry—I’ve got the fix.

You’ll need a free software called [Karabiner-Elements](https://karabiner-elements.pqrs.org/). It’s MacOS-exclusive, but if you’re on Windows, you can replicate the logic using [AutoHotkey](https://www.autohotkey.com/).

### Steps to Fix This Mess:
1. Download Karabiner.
2. Install it.
3. Open it.
4. In the side menu, click **"Complex Modifications"**.
5. Click **"Add your own rule"**.
6. Copy the content of `script.json` from this repository.
7. Paste it into Karabiner.
8. Click **"Save"**.
9. Enjoy your now-functional media keys.

### But Why Left Control Instead of Fn?
Good question. The short answer: **because life isn’t fair.**

Karabiner doesn’t recognize the Fn key on this keyboard specifically. I’ve tried—believe me, I really tried—but no luck. So, we’re stuck using the left Control key instead. Not ideal, but hey, it works.
