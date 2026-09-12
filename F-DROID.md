# F-Droid packaging notes

This project is intended for inclusion in the official F-Droid repository.

## Requirements

- Build from source with Gradle.
- No Firebase, Google Play Services, analytics, advertising, or API keys are required.
- The project includes a MIT license.
- Version 1.0 uses versionCode 1.
- Upstream releases should be tagged (for example `v1.0`) and the F-Droid metadata should use the full commit hash for the corresponding release.

## F-Droid metadata

For the official F-Droid repository, create a metadata file in `fdroiddata/metadata/` named after the Android application ID:

`com.aistudio.adhan.qibla.yml`

The exact `Builds` block should be generated/tested with fdroidserver against the tagged release commit before submitting a merge request.

See the official F-Droid submission guide for the current metadata requirements.
