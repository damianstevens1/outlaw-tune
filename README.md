# Outlaw Tune

Outlaw Tune is a static, mobile-first guitar tuner prototype. It uses browser microphone input, Web Audio pitch detection, six-string auto-detection, and an outlaw-country character progression that reacts as the note moves from flat to perfect to sharp.

## Files

- `index.html`
- `style.css`
- `script.js`
- `assets/`
- `netlify.toml`

## Local Preview

Open `index.html` directly, or serve the folder with any static server.

The app will try to request microphone access automatically. If the browser blocks the prompt, the no-mic preview animation and demo cents slider still work.

## Netlify

Drag the contents of this folder, or the packaged ZIP, into Netlify. No build command is required.

## iOS Wrapper Notes

For an Xcode wrapper, use `WKWebView` and bundle the static files locally. Add `NSMicrophoneUsageDescription` to `Info.plist` so the tuner can use microphone pitch detection.
