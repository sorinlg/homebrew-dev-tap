# Homebrew Dev Tap for tf-manage2

This is a development tap for tf-manage2 that contains prerelease versions (alpha, beta, rc) for testing purposes.

## Usage

```bash
# Add the dev tap
brew tap sorinlg/dev-tap

# Install the development version
brew install tf-manage2-dev

# Or install directly
brew install sorinlg/dev-tap/tf-manage2-dev
```

## Purpose

This tap is used for:
- Testing prerelease versions before stable release
- Validating new features like shell completions
- Getting early access to upcoming features

For stable releases, use the main tap:
```bash
brew install sorinlg/tap/tf-manage2
```

## Automatic Updates

This tap is automatically updated by GoReleaser when prerelease tags (alpha, beta, rc) are pushed to the main repository.
