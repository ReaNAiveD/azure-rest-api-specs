# communicationservices

> see https://aka.ms/autorest

This is the AutoRest configuration file for communicationservices.

## Getting Started

To build the SDKs for My API, simply install AutoRest via `npm` (`npm install -g autorest`) and then run:

> `autorest readme.md`

To see additional help and options, run:

> `autorest --help`

For other options on installation see [Installing AutoRest](https://aka.ms/autorest/install) on the AutoRest github page.

---

## Configuration

### Basic Information

These are the global settings for the communicationservices.

```yaml
openapi-type: data-plane
tag: package-sms-2025-05-29-preview
```

### Supression
``` yaml
suppressions:
 - code: LroExtension
   from: communicationservicessms.json
   reason: Lro attribute was not part of any previous version. Trying to add it signals breaking changes and requires adding operation-location, etc.
 - code: XmsEnumValidation
   from: communicationservicessms.json
   reason: In the stable version repeatabilityResult has enum with accepted/rejected. Also SDK generation of SmsSendResponseItemRepeatabilityResult will fail without it.
```

### Tag: package-2020-07-20-preview1

These settings apply only when `--tag=package-2020-07-20-preview1` is specified on the command line.

```yaml $(tag) == 'package-2020-07-20-preview1'
input-file:
  - preview/2020-07-20-preview1/communicationservicessms.json
title:
  Azure Communication Services
```

### Tag: package-sms-2021-03-07

These settings apply only when `--tag=package-sms-2021-03-07` is specified on the command line.

```yaml $(tag) == 'package-sms-2021-03-07'
input-file:
  - stable/2021-03-07/communicationservicessms.json
title:
  Azure Communication Services
```

### Tag: package-2024-01-14-preview

These settings apply only when `--tag=package-2024-01-14-preview` is specified on the command line.

```yaml $(tag) == 'package-2024-01-14-preview'
input-file:
  - preview/2024-01-14-preview/communicationservicessms.json
title:
  Azure Communication Services
```

### Tag: package-sms-2024-02-05-preview

These settings apply only when `--tag=package-sms-2024-02-05-preview` is specified on the command line.

```yaml $(tag) == 'package-sms-2024-02-05-preview'
input-file:
  - preview/2024-02-05-preview/communicationservicessms.json
title:
  Azure Communication Services
```

### Tag: package-sms-2024-12-10-preview

These settings apply only when `--tag=package-sms-2024-12-10-preview` is specified on the command line.

```yaml $(tag) == 'package-sms-2024-12-10-preview'
input-file:
  - preview/2024-12-10-preview/communicationservicessms.json
title:
  Azure Communication Services
```

---

### Tag: package-sms-2025-05-29-preview

These settings apply only when `--tag=package-sms-2025-05-29-preview` is specified on the command line.

```yaml $(tag) == 'package-sms-2025-05-29-preview'
input-file:
  - preview/2025-05-29-preview/communicationservicessms.json
title:
  Azure Communication Services
```
---

# Code Generation

## Swagger to SDK

This section describes what SDK should be generated by the automatic system.
This is not used by Autorest itself.

## Python

See configuration in [readme.python.md](./readme.python.md)

## Ruby

See configuration in [readme.ruby.md](./readme.ruby.md)

## TypeScript

See configuration in [readme.typescript.md](./readme.typescript.md)

## CSharp

See configuration in [readme.csharp.md](./readme.csharp.md)
