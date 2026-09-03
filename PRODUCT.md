# Chhath Puja Festival — Product Specification

## Overview
A simple Android app for Chhath Puja festival information, countdown, devotional-song playback, wishes, greeting posters, gallery, and पूजा विधि.

## Target User
People who want a convenient mobile companion for Chhath Puja.

## MVP
1. Home dashboard
2. Chhath Puja dates and schedule
3. Festival countdown
4. Chhath songs with demo/sample audio player
5. Wishes generator
6. Greeting poster generator
7. Festival gallery
8. पूजा विधि and festival information

## Primary Workflow
Open app → view festival status/countdown → choose a feature → consume information or play a song → return to Home.

## Screens
- Home
- Chhath Schedule
- Songs & Player
- Wishes
- Poster Generator
- Gallery
- Puja Guide

## Song Player
The MVP uses bundled or locally available demo/sample audio only. Player supports play/pause, seek, next/previous, playlist, title, cover image, and volume where supported.

## Explicitly Deferred
- User accounts
- Social feed/comments
- Cloud sync
- Online payments
- Full song catalog of copyrighted commercial recordings
- Admin dashboard

## Delivery
Android application. The first implementation should use a maintainable Android architecture and produce an installable debug APK for testing.

## Success Criteria
A tester can install the app, navigate all MVP screens, see the Chhath schedule/countdown, play demo audio, generate a wish/poster, browse the gallery, and read the puja guide without crashes.