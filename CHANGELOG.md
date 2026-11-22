# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.1.0](https://github.com/so1ve/firn/releases/tag/v0.1.0) - 2026-11-22

### Added

- *(action)* allow branch, commit, or flake ref in version input
- *(cli)* default config path to /etc/firn/config.toml with --config flag
- *(action)* add GitHub Action for automatic cache pull and push
- *(server)* expose public-keys endpoint and simplify visibility
- initial firn implementation

### Fixed

- *(nix)* add sqlite and zstd buildInputs

### Other

- *(release)* enable git_only release-plz for unpublished firn crate
- *(deps)* update Rust crates, GitHub Actions, and Nix locks
- streamline README
- add release-plz workflow with static release binaries
- serve unified root cache without owner prefix
- simplify README config and add firn.example.toml
