# AGENTS.md

## Implementation Rules
- Read PRODUCT.md, ARCHITECTURE.md, and ACCEPTANCE.md before changing code.
- Keep the MVP offline-first.
- Use Kotlin and Jetpack Compose unless the existing project requires otherwise.
- Keep UI simple, festive, readable, and responsive.
- Keep content/data separate from UI where practical.
- Use Media3 for audio playback.
- Do not bundle copyrighted commercial songs without explicit permission.
- Use placeholder/demo audio when licensed/original audio is unavailable.
- Do not add login, payments, cloud sync, or social features unless explicitly requested.

## Commands
Use the project's Gradle wrapper for build and test commands.

## Definition of Done
- Build succeeds.
- No new compiler errors.
- MVP acceptance cases are testable.
- No feature outside the approved MVP is required.
- The app can produce an installable debug APK.

## Stop Conditions
Stop and ask before:
- adding paid services,
- using real secrets,
- introducing public authentication or user data storage,
- bundling copyrighted commercial recordings,
- changing the Android delivery target,
- deleting or overwriting existing user/project data.