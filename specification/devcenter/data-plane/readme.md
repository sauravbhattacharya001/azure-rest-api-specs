# devcenter

> see https://aka.ms/autorest

This is the AutoRest configuration file for devcenter.

## Getting Started

To build the SDKs for My API, simply install AutoRest via `npm` (`npm install -g autorest`) and then run:

> `autorest readme.md`

To see additional help and options, run:

> `autorest --help`

For other options on installation see [Installing AutoRest](https://aka.ms/autorest/install) on the AutoRest github page.

---

## Configuration

### Basic Information

These are the global settings for the devcenter.

```yaml
openapi-type: data-plane
azure-arm: false
tag: package-2022-03-01-preview
```

### Tag: package-2022-03-01-preview

These settings apply only when `--tag=package-2022-03-01-preview` is specified on the command line.

```yaml $(tag) == 'package-2022-03-01-preview'
input-file:
  - Microsoft.DevCenter/preview/2022-03-01-preview/devcenter.json
  - Microsoft.DevCenter/preview/2022-03-01-preview/devbox.json
  - Microsoft.DevCenter/preview/2022-03-01-preview/environments.json
```
