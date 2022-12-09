# unarchiving-download-artifact

Downloads an artifact and unarchives it.

Meant to be used as drop-in replacement for [download-artifact](https://github.com/marketplace/actions/download-a-build-artifact) when using [archiving-upload-artifact](https://github.com/marketplace/actions/archive-and-upload-build-artifacts) instead of [upload-artifact](https://github.com/marketplace/actions/upload-a-build-artifact).

## Example
```yaml
- name: Archive and upload Build Artifacts
  uses: RockLobster/unarchiving-download-artifact@v0.2
  with:
    name: android-test-results
    path: android/libs
```