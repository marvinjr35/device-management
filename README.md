# Device Management Client Schema

This repository contains Apple's Device Management Client schema data for the MDM (Mobile Device Management) protocol, and the Declarative Device Management feature.

## OS Versions

This release corresponds to the following OS versions

| OS      | Version |
|---------|---------|
| iOS     | 17.0    |
| macOS   | 14.0    |
| tvOS    | 17.0    |
| watchOS | 10.0    |

## What's Available

The following schema items are available:

* MDM commands - `mdm/commands`
* MDM check-in requests - `mdm/checkin`
* MDM profiles - `mdm/profiles`
* MDM errors - `mdm/errors`

* Declarative device management declarations - `declarative/declarations`
* Declarative device management status items - `declarative/status`
* Declarative device management protocol - `declarative/protocol`

* Other device management data formats

## YAML Schema Definition

See [YAML Schema](docs/schema.md).

## Providing Feedback

All feedback on the data in this repository should be made using the `Feedback Assistant` app or website (https://feedbackassistant.apple.com). Select feedback for `Enterprise & Education`, and choose the `Mobile Device Management (MDM)` area.

We will NOT be accepting pull requests on this repository - please use `Feedback Assistant` for all requests.
