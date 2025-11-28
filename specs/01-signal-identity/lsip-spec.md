# LSIP — Law-N Signal Identity Protocol (Draft)

**Status:** Draft  
**Version:** 0.1.0  
**Author:** Peace Thabiwa  
**Last Updated:** 2025-11-25

---

## 1. Summary

LSIP defines how Law-N assigns, encodes, and verifies **signal identities**.

A signal identity is a cryptographically verifiable description of:
- the device
- the frequency band
- the G-layer
- the tower/satellite context
- the time window

LSIP is to signals what IP + MAC + TLS certs are to CLFI, but unified.

---

## 2. Motivation

- CLFI identifies endpoints via **IP addresses** and occasionally MAC.
- It does not:
  - bind identity to frequency
  - encode radio constraints
  - expose tower/satellite context

LSIP fixes this by making “who is speaking” a **signal-native** concept.

---

## 3. Identity Structure (high-level)

At a high level:

```text
SignalID = hash(
  device_fingerprint,
  frequency_band,
  g_layer,
  tower_context,
  time_window
)
