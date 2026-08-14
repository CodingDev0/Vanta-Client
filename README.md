# Vanta Client 2.0

Monochrome Android companion/client shell for Minecraft Bedrock.

## No Android Studio required

Push this repository to GitHub. The included GitHub Actions workflow builds the Android APK in the cloud.

See **[GITHUB_BUILD.md](GITHUB_BUILD.md)**.

## Features

- Smart Performance, PvP, Balanced, Battery and Custom profiles
- Bedrock launcher
- Refresh-rate and device telemetry
- Android Game Mode detection
- Performance-mode helper
- PvP/performance HUD architecture
- HUD scaling, opacity and grid settings
- `.mcpack` / `.mcaddon` import foundation
- Pack library
- JSON profile export/import
- Safe Mode
- Black/gray/white Vanta theme
- Bedrock resource-pack foundation

## FPS

Vanta is deliberately honest about FPS. It can request supported Android/OEM performance behavior and optimize profile settings, but a normal Android app cannot directly rewrite Minecraft Bedrock's private renderer or guarantee an unsupported FPS cap.

## Repository layout

```text
app/                    Android application
bedrock/                Bedrock resource-pack foundation
docs/                   Documentation
tools/                  Android/Bedrock helper scripts
.github/workflows/      Cloud APK build
```

## License

MIT
