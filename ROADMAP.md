# Norwegian 4×4 — Roadmap

## Shipped
- Setup screen: age → max HR via Fox, Tanaka, Gulati formulas + manual entry
- Formula descriptions (appear on selection)
- Zone preview (85–95% target) updates live
- Warm-up phase: 0 / 15s / 30s / 1–15 min stepper, skippable, skip-to-10s button during workout
- 4 × 4 min work / 3 min recovery protocol
- Large timer + HR display with zone coloring (blue / green / red)
- Zone bar + zone feedback text
- Progress dots for N intervals
- Audio beep patterns (warmup / work / recovery / countdown / done)
- Haptic vibration mirroring audio patterns
- Landscape layout (timer left, HR right) — matched card borders on both panels
- BLE connection to CooSpo H808S chest strap
- BLE auto-reconnect on drop + manual reconnect button mid-workout
- Brave browser detection + confirmed fix instructions (enable Web Bluetooth API + new permissions backend in brave://flags)
- BLE pre-check via getAvailability(), 15s timeout with feedback if picker is suppressed
- Wake Lock API (screen stays on during workout)
- Add to Home Screen install banner + PWA manifest + service worker
- Summary screen (duration, avg HR, time in zone, per-interval breakdown)
- Finish time display on workout screen ("Done at X:XX PM", updates every tick)
- Settings & Tips screen (three-dot menu, birthday → auto-age via localStorage, 6 protocol tip cards sourced to Helgerud et al. 2007 / NTNU CERG, disclaimer)
- Tabata mode (configurable work/rest/rounds, shares HR monitor + warmup)
- Standalone HR Monitor screen (live BPM, zone coloring, session max/avg/min, landscape layout)

## Considering
- Cooldown phase after last interval (adjustable duration, like warm-up)
- Custom interval builder — define any number of phases with arbitrary durations and labels
- Workout history saved to localStorage with a log screen
- HR line graph with coloured zone bands (displayed in HR monitor and post-workout summary)
- Monitor battery level display (read from GATT Battery Service, shown in HR monitor screen)
