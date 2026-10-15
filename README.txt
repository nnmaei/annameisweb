ANNA MEI BOT ARCHIVE — AVATAR SETUP

1) Website favicon/avatar
--------------------------------
Put your website avatar image at:
assets/site-avatar.png

This is the small icon shown in the browser tab. Square 256x256 or 512x512 PNG works best.

2) Bot avatars
--------------------------------
Put each bot image in assets/bots/ using the filenames already referenced in index.html:
- ethan-lucas.jpg
- kenshin.jpg
- daiki.jpg
- haruki.jpg
- darian.jpg
- kaien.jpg

Or change the `avatar:` value in BOT_DATA to any filename/path you prefer.

Example:
avatar: "assets/bots/ren.jpg"

3) Facebook links
--------------------------------
Change each `facebookPost:` value in BOT_DATA to the exact Facebook post URL.

4) Add a new bot
--------------------------------
Copy one object inside BOT_DATA and set:
name, type, hook, tags, coverLabel, avatar, quote, facebookPost

Then re-upload the whole folder to Cloudflare Pages.
