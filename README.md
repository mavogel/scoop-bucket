<p align="center">
  <img src="assets/logo.svg" alt="scoop-bucket logo" width="140">
</p>

<h1 align="center">scoop-bucket</h1>

<p align="center">
  Personal <a href="https://scoop.sh">Scoop</a> bucket by <a href="https://github.com/mavogel">@mavogel</a>.
</p>

## Usage

```powershell
scoop bucket add mavogel https://github.com/mavogel/scoop-bucket
scoop install <app>
```

Or install directly without adding the bucket first:

```powershell
scoop install https://raw.githubusercontent.com/mavogel/scoop-bucket/main/bucket/<app>.json
```

## About

This repository hosts Scoop manifests for my own tools, so they can be installed and updated with `scoop` like any other package. macOS and Linux users can find the same tools in [mavogel/homebrew-tap](https://github.com/mavogel/homebrew-tap).
