# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.24.0](https://github.com/agentidentitytrustprotocol/aitp-rs/compare/aitp-experimental-v0.23.0...aitp-experimental-v0.24.0) - 2026-10-27

### Added

- *(handshake)* [**breaking**] SPIFFE moves to aitp-experimental behind an IdentityVerifier hook (RS-RC4 P3) ([#437](https://github.com/agentidentitytrustprotocol/aitp-rs/pull/437))
- *(renewal)* [**breaking**] move TCT renewal to aitp-experimental (RS-RC4 P2) ([#436](https://github.com/agentidentitytrustprotocol/aitp-rs/pull/436))
- *(delegation)* [**breaking**] move multi-hop delegation to aitp-experimental (RS-RC4 P1) ([#435](https://github.com/agentidentitytrustprotocol/aitp-rs/pull/435))

### Other

- [**breaking**] every stable struct and enum is non_exhaustive, private or classified exhaustive (RS-RC3) ([#413](https://github.com/agentidentitytrustprotocol/aitp-rs/pull/413))
- [**breaking**] collapse the workspace into aitp, aitp-experimental and aitp-cli (RS-RC2) ([#411](https://github.com/agentidentitytrustprotocol/aitp-rs/pull/411))
