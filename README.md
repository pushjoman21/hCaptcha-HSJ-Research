<div align="center">

# hCaptcha HSJ Research Notes

Technical documentation of hCaptcha's HSJ fingerprint events and the `vmdata` serialization format.

![Status](https://img.shields.io/badge/status-archived-lightgrey?style=flat-square)
![Purpose](https://img.shields.io/badge/purpose-educational-blue?style=flat-square)
![Type](https://img.shields.io/badge/type-documentation-informational?style=flat-square)

</div>

> [!IMPORTANT]
> **Archived research · Educational use only**
> This repository documents past research and is no longer maintained. The analyzed system has changed since publication, so the findings are **outdated** and may not reflect current versions.
> The material is provided solely for educational and defensive security purposes. It must not be used to circumvent protections, automate access without authorization, or violate any platform's terms of service.

---

## Overview

A set of research notes describing which browser signals hCaptcha's HSJ script collects, how they are classified, and how per-frame interaction data is serialized. The notes are meant as a reference for studying browser fingerprinting and VM-based client-side protection.

## Contents

| File | Description |
|------|-------------|
| [`fingerprint_docs.md`](fingerprint_docs.md) | Fingerprint envelope, event IDs and value classes (static, hashed, dynamic) |
| [`REVERSE_VMDATA.md`](REVERSE_VMDATA.md) | Structure of the `vmdata` frames, event streams and render signatures |
| `image.png` | Debugger capture from the analysis of the HSJ encryption routine |

## Research Topics

- Browser fingerprinting signals and their classification
- VM-based serialization of interaction data
- Structure of encrypted telemetry payloads

---

## Legal Notice

hCaptcha is a trademark of Intuition Machines, Inc. This project is independent and is not affiliated with, sponsored or endorsed by hCaptcha.

The material is provided "as is", without warranty of any kind. The author accepts no liability for any misuse.

## Contact & Takedown Requests

Vendors with concerns about this repository can reach out at **jomandiscord@gmail.com**. Content will be reviewed and adjusted or removed promptly where appropriate.
