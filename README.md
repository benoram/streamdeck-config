# My Stream Deck configuration

I've ordered a StreamDeck XL. While I wait for that, I've been playing with the software version on my phone.

In my mind, stream deck profiles are meant to be shared. And StreamDeck is not just for streamers, and folks putting together video. Its super useful for developers and other non-media related creatives.

My config to start is pretty bare bones, but this repo will be updated as I make changes.

## Images
The ```/Key Images``` folder in the repo contains all the PNG files. It also contains source files for the images, including any laters.  Pixelmator format for source files

## Buttons
- Mic
My mic button is a HotKey switch that swaps between the Mic being on and off. Mic volume is handled with a Keyboard Maestro hotkey to set volume (either 0 or 80%). I've leveraged an animated icon when the Mic is on so it is super obvious.

- New Macro, Play Macro
This leverages functionality in Keyboard Maestro to record keyboard based macros. Super useful for bulk-editing text. Another animated icon when macros are being recorded, so the recording mode is obvious.

- CPU
Leverages one of the built-in plugins with a custom image.

- Safari left
Moves the Safari window to my left screen and set a prescribed window size. This is attached to an AppleScript in Keyboard Maestro

- Slack, Outlook web mail, Outlook web calendar.
Obvious

- Terminal, GitHub Desktop and Soulver

- Lock computer
Also attached to a Keyboard Maestro hotkey