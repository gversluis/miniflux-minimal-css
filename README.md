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
Those screenshots are outdated but give a gist.

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

Other solutions and honorable mentions
--------------------------------------
- [Yonta](https://github.com/miradozk/yonta) [Yonta-Fork](https://github.com/JanJastrow/yonta-fork)- Minimal theme
- [Dark midnight theme for Miniflux](https://codeberg.org/zoenglinghou/miniflux-theme) - Very nice theme: Colored categories (first 8 at the moment), proper white space
- [MiniFlux-theme](https://github.com/lacereation/minflux-theme) - Minimal theme with menu items and actions hidden in hamburgers
- [Maya land user styles](https://maya.land/user-styles/miniflux/) - Miniflux custom CSS, changes colors and spacing
- [miniflux-theme-pure](https://github.com/fengkx/miniflux-theme-pure) - Miniflux custom CSS, changes colors and a bit layout
- [Custom CSS](https://gist.github.com/TaylanTatli/c1c725691a69eeb9c5f5889371317ed5) - Miniflux custom CSS, changes colors and spacing
- [reminiflux](https://github.com/reminiflux/reminiflux) - Web client, all feeds visible, looks more like a traditional application
- [ConstaFlux](https://github.com/ConstantinCezarBegu/Microflux) - Android client with offline reading mode, notifications for new feeds
- [Miniflutt](https://github.com/DocMarty84/miniflutt) - Android client, great interface, no offline reading
- [spaRSS](https://github.com/Etuldan/spaRSS) - Best standalone Android RSS reader with offline reading, great user interface, minimal config, but saves articles in cache which is hard to backup without root

Credits
-------
- Author: Gerben Versluis
- [Miniflux](https://github.com/miniflux/) Authors: Frédéric Guillot - [List of contributors](https://github.com/miniflux/v2/graphs/contributors)
- Distributed under Apache 2.0 License
