# National Fabrications — continuation notes

This project is the existing React/Vite site, refined without rebuilding it from scratch.

## Improvements in this version
- Premium cinematic hero fallback using the existing architectural image assets.
- Scroll-driven hero progress indicator.
- Hero automatically uses `public/videos/hero-scroll.mp4` if that file is added.
- Refined hero hierarchy, overlays, grid and responsive behavior.
- Refined Projects section with stronger editorial layout and hover treatment.
- Featured project loads eagerly; secondary images remain lazy.
- Navigation CTA changed to “Start a Project”.
- Contact project brief now prepares a real email draft to `nationalfabrications@gmail.com` instead of pretending the form was sent.
- Added focus/selection accessibility polish and mobile spacing refinements.

## Hero video
The uploaded project did not contain `public/videos/hero-scroll.mp4`.

To activate the final scroll-controlled cinematic video, copy your final MP4 into:

`public/videos/hero-scroll.mp4`

No code change is required.

## Run
From the project root:

`npm install`

then:

`npm run dev`

Open the local Vite URL shown in the terminal.

V11: Increased global architectural film visibility by reducing global tone/veil and making chapter surfaces substantially more translucent while preserving local text contrast.
