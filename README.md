# eyeBrowser

A web browser for Android TV: a thin shell around an existing engine (GeckoView or the system WebView), not a new engine.

The working name is *eyeBrowser*; *ayeBrowser* is the alternative spelling still under consideration.

## Why

Existing Android TV browsers disappoint in several ways: hard-to-handle cursors, intrusive features, very poor configurability compared with PC browsers, weak video player integration, unintuitive interfaces and missing features.

## Target

- Primary test device: a Philips OLED TV running Android 11.
- The same build is meant to run on other Android TV devices, so every remote key mapping is to be configurable.

## Planned scope of version 0.1

- TV launcher entry and banner
- Engine loading a page
- D-pad cursor with acceleration, and a switch for focus-jumping
- Back key and colour keys wired as shortcuts
- Minimal address bar and start page

## Logo

A tentative logo lives in `docs/assets/` as outlined SVGs (`logo-light.svg` for light backgrounds, `logo-dark.svg` for dark ones). The page in `docs/index.html` renders them and is meant to be served with GitHub Pages from the `/docs` folder. The letterforms are outlined from Fredoka (SIL Open Font License).

## Status

Idea and logo exploration. No code yet.
