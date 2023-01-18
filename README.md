# miniflux-minimal-css

Introduction
------------
I wrote a black Miniflux custom CSS for a more minimal interface.

It basically:
- Adds a fixed menu bar at the top because I wanted feeds available within a single click
- Removes text where there are icons available because I wanted a more compact design
- Added some colors for the icons to make them visually distinctable
- Moved common item actions to the right where they are close to my fingers on mobile
- Hides less common actions which are available one click away (keyboard navigation may still work)
- Black background so it produces less light and uses less battery


This CSS was written for [Miniflux v2](https://github.com/miniflux/v2) version 2.0.41 and may work on different versions.

I wrote this CSS for my own use so it is not tested except for my current Mull on Android and Firefox on Windows. Chromium on Windows seems to work as well but I only gave it a sneak peek.

Screenshots
-----------

Mobile screenshots

<img src="/screenshots/Screenshot_20230118-140542.png" height="600" alt="Mobile Unread screenshot" /> <img src="/screenshots/Screenshot_20230118-140721.png" height="600" alt="Mobile Feeds screenshot" /> <img src="/screenshots/Screenshot_20230118-140759.png" height="600" alt="Mobile Feed screenshot" /> <img src="/screenshots/Screenshot_20230118-140648.png" height="600" alt="Mobile Item screenshot" />

Desktop screenshots

<img src="/screenshots/Screenshot 2023-01-18 at 14-11-32 Unread (124) - Miniflux.png" width="640" alt="Desktop Unread screenshot" /> <img src="/screenshots/Screenshot 2023-01-18 at 14-12-42 Feeds (21) - Miniflux.png" width="640" alt="Desktop Feeds screenshot" /> <img src="/screenshots/Screenshot 2023-01-18 at 14-12-05 Wumo Kind of Normal (29) - Miniflux.png" width="640" alt="Desktop Feed screenshot" /> <img src="/screenshots/Screenshot 2023-01-18 at 14-15-37 Wumo 18. Jan 2023 - Miniflux.png" width="640" alt="Desktop Item screenshot" />

Installation
------------
1. Download and install [Miniflux v2](https://github.com/miniflux/v2)
2. Go to `Settings`
3. Choose Theme `Dark - Sans Serif`
4. Manually copy all CSS from [miniflux.css](/miniflux.css) to `Custom CSS`
5. Click `Update` & enjoy!

Credits
-------
- Author: Gerben Versluis
- MiniFlux Authors: Frédéric Guillot - [List of contributors](https://github.com/miniflux/v2/graphs/contributors)
- Distributed under Apache 2.0 License
