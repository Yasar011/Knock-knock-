# WHO'S THERE?

A fictional interactive horror website used as a prop in a short film.
Single static page (`index.html`), no backend, no tracking, no third-party requests.
It never touches the camera, microphone, location, contacts or files.

## Runtime
The whole experience is paced to finish **under 60 seconds** from the START click
(about 3.5 s of intro before it). Each answer has a short, silent timer; if a viewer
is slow, the site picks for them and speeds up the remaining beats so the run still ends in time.

## Production panel (hidden)
- Open / close: `` ` `` (backquote) or `Ctrl+Alt+P` — `Esc` closes
- Phone: tap the top-left corner 5 times
- URL options: `?film` (clean preview mode), `?panel`, `?speed=2`, `?mode=early|scripted|standard`

Panel: reset, restart website, skip to any question, trigger the creepy section / "Wait." moment /
final question / final reveal, change the question sequence, sound on/off, glitch on/off,
film preview mode, playback speed, 60-second limit on/off.

## Deploy
Static site — any static host works. `vercel.json` adds privacy headers (camera/mic/geolocation denied).
