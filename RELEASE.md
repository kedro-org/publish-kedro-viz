# Release 3.0.0:

## Major features and improvements

- Added support for [uv](https://docs.astral.sh/uv/) package manager alongside pip

## Migration Guide

- **Existing users**: No action required - continues to work with pip by default
- **uv users**: Add `python_manager: "uv"` to your workflow configuration

**Example for uv users:**

```yaml
- uses: kedro-org/publish-kedro-viz@v3
  with:
    python_manager: "uv"
```

# Release 2.0.0:

## Major features and improvements

- Remove usage of `peaceiris/actions-gh-pages`
- Update README file

# Release 1.1.0:

## Major features and improvements

- Add `include_hooks` input for the action

# Release 1.0.0:

This is an initial release of publish-kedro-viz action

## Major features and improvements

- Add initial setup for the action
- Add `spaceflights-pandas-viz` Kedro starter to test the workflow
- Update README file
