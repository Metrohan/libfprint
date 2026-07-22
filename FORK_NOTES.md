# Fork Notes

This repository is a fork of [Void755/libfprint](https://github.com/Void755/libfprint), which is itself a SIGFM-based fork of the upstream [FPrint libfprint](https://gitlab.freedesktop.org/libfprint/libfprint) project.

## Purpose

This fork exists to support Linux enablement for the Goodix GXFP5130 fingerprint sensor found in Huawei MateBook laptops.

## Local changes

- Added Goodix GXFP5130 (`gxfp`) driver support
- Updated the default PSK path used by PAM integration
- Added a Nix package definition (`gxfp-tools`)
- Tracked and updated the `gxfpmoc` subproject and related sources

## Related project

The primary project, packaging, and documentation for this work live at:

- [gxfp5130-linux](https://github.com/Metrohan/gxfp5130-linux)

## Upstream

Original authorship and licensing (LGPL-2.1) belong to the upstream project(s):

- [Void755/libfprint](https://github.com/Void755/libfprint) — SIGFM fork this repository is based on
- [FPrint libfprint](https://gitlab.freedesktop.org/libfprint/libfprint) — original upstream project
