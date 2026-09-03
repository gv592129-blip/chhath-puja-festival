# Chhath Puja Festival — Acceptance Criteria

## Home
- App opens to Home without crashing.
- Home provides access to every MVP feature.
- Festival countdown is visible.

## Schedule
- User can see the Chhath Puja schedule.
- Dates and event names are clearly readable.
- Schedule works offline.

## Countdown
- Countdown updates automatically.
- It does not display negative or obviously invalid values after the target event.
- Date/time handling uses the device's local timezone.

## Songs
- User can open the song list.
- A demo song can start and pause.
- Seek control changes playback position.
- Next/previous changes tracks when available.
- Playlist state remains usable while navigating within the app.
- Missing audio produces an error message, not a crash.
- Only legally permitted demo/sample audio is bundled.

## Wishes
- User can select or generate a Chhath Puja wish.
- Wish text is readable and can be copied/shared through Android's standard share mechanism if implemented.

## Poster Generator
- User can select a template and enter a name/text.
- A poster is generated without distortion.
- Generated image can be previewed.

## Gallery
- Gallery loads bundled images.
- Tapping an image opens a larger view.
- Missing image assets do not crash the app.

## Puja Guide
- User can read the main पूजा विधि/information sections.
- Text is scrollable and readable.

## Packaging
- Project builds successfully as an Android debug APK.
- APK installs on a supported Android device/emulator.
- App can be launched and all MVP screens can be reached.

## Definition of Done
All criteria above pass on a clean build and a fresh app installation.