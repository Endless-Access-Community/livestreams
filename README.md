# livestreams

Planning and resources for community livestreams

## Suggest a topic

If there's a specific topic you think would be interesting to the Endless Access community, players, educators, or learners:

1. Review the [existing ideas and planned streams](https://github.com/Endless-Access-Community/livestreams/issues?q=is%3Aissue%20state%3Aopen%20label%3AIdea%20OR%20label%3AStream)

    - If your idea already exists, add a :+1: reaction
    - Comment if there is additional helpful context/information you can provide

1. If your idea doesn't exist, select **New issue** then detail your suggestion
    
    - A member of the team will review it and may follow-up for additional information.

## Run a stream

If you're streaming to the official Endless Access channel, here are some tips for consistency/a smooth experience:

1. **Use [OBS Studio](https://obsproject.com/).** While you can stream to YouTube directly from the browser, you get much more control using streaming software. Start by importing the preconfigured scenes from this repo, then reconfigure any cameras and screen shares for your specific setup.

1. **For remote guests, use [VDO.ninja](https://vdo.ninja/).** This is how the OBS scenes are configured with Browser sources; you can pipe a remote camera feed, screen share, etc. straight into OBS and then treat them as any other video source. Note that you have to choose between sharing your desktop audio (simplest) _or_ sharing the audio from each Browser source; if you do the latter, note that your guest will not be audible on the stream if their video is not visible!

1. **Use a smart screen resolution.** Set the resolution of any screen that will be shared to 1920×1080 if possible; this ensures it will be as crisp as possible on a 1080p stream. If you have a HiDPI (Retina, 2× scaled, etc.) or otherwise high resolution display, using a lower resolution at 1× scaling can also significantly help with performance while streaming, whether screen sharing or not.

1. **Use the brand assets.** Set the wallpaper of any screen that will be shared to the `background-16x9.png` image; this makes it match the background of each scene which is shown behind cropped video feeds or if a source doesn't load. For full-screen graphics (e.g. calls to action or other text), use the `background-alt-16x9.png` image. For text, use [Figtree](https://fonts.google.com/specimen/Figtree), extra bold. For thumbnails, use the `thumbnail.svg` file as a starting point (ensuring you have the Figtree font installed!), editing the text e.g. in Inkscape.

1. **Don't overlay the logo.** Since the backgrounds already feature the Endless Access logo, there's generally no need to duplicate it by overlaying it. The YouTube player may also overlay a channel logo in the bottom-right corner, which could cause duplication.

1. **Schedule the stream, but start it early.** Use YouTube Studio to schedule the stream well in advance so viewers can see it ahead of time and be notified when it goes live; at the same time, aim to start the stream up to five minutes early e.g. with a “starting soon” graphic and music to ensure your stream is stable, audio is working, etc.

1. **Schedule a pre-stream prep session**. Get set up 20–30 minutes before the scheduled stream to ensure guests can join the VDO.ninja room, OBS scenes are configured correctly, audio is working well, etc. Use this time to record a test in OBS Studio, switching between different scenes that will be used and paying extra attention to audio sources and quality. Review the stream agenda with all participants so you're on the same page!
