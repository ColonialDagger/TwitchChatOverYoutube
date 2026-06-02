# Twitch Chat over YouTube

This script replaces the YouTube live stream chat frame with their corresponding Twitch channel chat frame. Works with emote extensions, but the extension menu can only be accessed via twitch.tv.

This extension cannot and will not claim channel points, but all other features are still accessible.

If you want to add channel maps to the JSON, make a pull request or open an issue.

# Supported Extensions

| Extension    | Firefox                                                                  | Chrome                                                                                                       |
|--------------|--------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------|
| Violetmonkey | [Firefox](https://addons.mozilla.org/en-US/firefox/addon/violentmonkey/) | [Chrome](https://chromewebstore.google.com/detail/jinjaccalgkegednnccohejagnlnfdag?utm_source=item-share-cb) |
| Tampermonkey | [Firefox](https://addons.mozilla.org/en-US/firefox/addon/tampermonkey/)  | [Chrome](https://chromewebstore.google.com/detail/dhdgffkkebhmkfjojejmpbldmpobfkfo?utm_source=item-share-cb) |

# Installation

Add the script to VioletMonkey/Tampermonkey via the following URL:

```
https://raw.githubusercontent.com/ColonialDagger/TwitchChatOverYoutube/refs/heads/main/script.json
```

<img width="842" height="309" alt="image" src="https://github.com/user-attachments/assets/6ead14c0-ec54-4fc3-a02d-210fd52e5898" />


Alternatively, copy the entire contents of the `script.json` file into a new script.

# Usage

The script will automatically replace YouTube chat with the Twitch chat window when a mapping is present in `channel_map.json`.

Once Twitch chat is loaded, you can switch between Twitch chat and YouTube chat with a set hotkey. The default hotkey is `F8`.

# AI Disclaimer

This is vibe-coded.
