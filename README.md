
<p align="center">
  <a href="https://github.com/snow-actions/eclint"><img alt="GitHub Actions status" src="https://github.com/snow-actions/eclint/workflows/ECLint-action/badge.svg"></a>
</p>

# ECLint action

Execute [ECLint](https://github.com/jedmao/eclint) on GitHub Actions.  
ECLint validates or fixes code based on [EditorConfig](https://editorconfig.org/).

## Usage

See [action.yml](action.yml)

### Validate

```yml
- uses: snow-actions/eclint@v1.0.0
  with:
    args: 'check'
```

### Fix

Execute `eclint fix *.yml`. Make commit yourself.

```yml
- uses: snow-actions/eclint@v1.0.0
  with:
    args: 'fix *.yml'
```

## Example

See [actions tab](https://github.com/snow-actions/javascript-action/actions)

## Privacy

This Action contacts Chainguard's licensing server to verify authorization. Connection metadata (IP address, GitHub repository identifier, timestamp, and any metadata encoded in the auth token) is transmitted to Chainguard, Inc. even if authorization is denied in accordance with our [Privacy Notice](https://www.chainguard.dev/legal/privacy-notice)
