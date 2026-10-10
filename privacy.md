# Hey, about your privacy

I made this app because I'm lazy. 🪥 I watch Shorts while brushing my teeth and I hate scrolling with a wet, foamy hand. If that sounds like you, you'll probably like this. It's free for life. Use it as much as you want.

Now the serious bit, said simply: I don't want your watch history, account, or identity. There is no sign-in, no ads, no analytics SDK, and no tracker baked into the APK. Nothing about which Short you watched is sent anywhere.

I'm also not watching the Short with you. I never see the video frame as content. I don't grab the title, the channel, the description, or your search history. Locally on your phone, the accessibility service:

- reads the player's progress control when it is available
- when that control is idle or frozen, looks only at how full the thin progress line is on screen (white or red) so it can still advance when a clip ends or when progress jumps backward (a Short that peaks then restarts)
- looks for on-screen labels for live broadcasts and still image posts (LIVE / watching / like this post and similar) so it can skip those and keep clips playing
- does **not** use screenshots for titles, channels, faces, or anything else
- does **not** read captions to decide what to do

The overlay buttons show when a Short is fullscreen on screen. They hide when it isn't (including floating / tiny windows). Pause turns auto-scroll off; the up control skips once.

**Network:** the only thing the app fetches from the internet is a tiny public `version.json` (and, if you choose Update, the APK) from this releases repo, so you can get newer builds. That check is not tied to which Short you are watching.

Pause auto-scroll, switch the accessibility service off, or uninstall. After that, nothing of mine is running. Promise. 🫶

Not affiliated with any brand or apps.
