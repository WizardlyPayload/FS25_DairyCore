# Changelog

All notable changes to FS25_DairyCore will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

Changelog tracking for this mod begins **2026-08-22** under the suite-wide ruling
(see the ecosystem ledger, entry for Arissani and Wizard). Prior history lives in
the repo's git history and README.

---

## [Unreleased]

### Added
- Changelog file established (suite ruling 2026-08-22).
- Feed-field designation surface (DC-11): a deep dialog opened from the Dairy Esc
  glance ("Feed Fields") lists your owned fields with live soil state and lets you
  toggle each as feed for a barn. This is what makes the feed bonuses and the
  mycotoxin penalty actually fire.

### Fixed
- Barn discovery now distinguishes live milk barns from saved records. Startup
  retries preserve unresolved dairy state, rebind late-loading barns and notify
  the existing barn and breed surfaces when visibility or ownership changes.
  Diagnostics report live barns and stored records separately. Test package
  version 1.0.5.24 distinguishes this correction from the earlier retry diagnostics.
- Feed-field bonuses and penalties plus the mycotoxin penalty now apply in both
  Standard and RealisticLivestock (Ritter) modes. They previously ran only in the
  Standard score path, so a Ritter-mode farm was silently exempt (DC-11 placement).
- Un-designating a feed field now syncs to co-op partners immediately, matching
  the designation path (F106).

## [1.0.5.4] - 2026-08-22

- First entry under changelog tracking.
