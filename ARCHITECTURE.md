# Chhath Puja Festival — Architecture

## Platform
Android app.

## Suggested Stack
- Kotlin
- Jetpack Compose
- Navigation Compose
- AndroidX ViewModel
- Media3/ExoPlayer for audio playback
- Local bundled assets for MVP content
- No backend required for the first version

## Modules
| Product Feature | Technical Module |
|---|---|
| Home | HomeScreen |
| Schedule | ScheduleScreen + FestivalData |
| Countdown | Countdown component |
| Songs | SongsScreen + PlayerViewModel + Media3 |
| Wishes | WishesScreen + local templates |
| Posters | PosterScreen + Android image/canvas APIs |
| Gallery | GalleryScreen + bundled image assets |
| Puja Guide | GuideScreen + local content |

## Data
Festival dates, song metadata, wish templates, guide text, and gallery metadata are local MVP assets/data.

## Audio
Use only demo/sample audio that is legally permitted for bundling. Store audio in app resources/assets. Media3 handles playback state, seeking, playlist navigation, and lifecycle integration.

## Navigation
Use a single navigation graph with Home as the entry point. Each feature has its own screen and can return to Home.

## Offline Behavior
Core MVP content and demo audio should work without an internet connection.

## Error Handling
- Missing media: show a friendly unavailable message.
- Invalid navigation state: return to Home.
- Poster generation failure: show retry action rather than crashing.

## Future Extension
A later version may add a remote catalog/API for licensed songs, but that is outside MVP.