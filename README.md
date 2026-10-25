# test_app

A Flutter sandbox for checking that the SDK, emulators and tooling work on a
new setup. It's the standard counter app, kept as a known-good baseline.

## Run it

```bash
flutter pub get
flutter run          # pick any device: Android, iOS, web, macOS, Linux, Windows
flutter test         # runs the counter widget test
```

## Why it exists

- Quick smoke test after upgrading Flutter (managed with FVM in `~/fvm`)
- Somewhere to try packages or widgets before using them in a real project
- Checks every platform folder (android, ios, web, macos, linux, windows) builds
