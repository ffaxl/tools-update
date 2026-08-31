# Changelog

All notable changes to this project will be documented in this file.

This project adheres to [Keep a Changelog](https://keepachangelog.com/en/1.0.0/)
and follows [Semantic Versioning](https://semver.org/).

## [0.1.0] - 2026-08-31

### Added ✨

- Add update-tools script for installing CLI tools
- Allow updating a subset of tools by name
- Add download progress bar and --quiet flag
- Track installed versions, prune removed tools, handle failures gracefully
- Migrate mc to its community fork, add gh and glab
- Add sops
- Add age
- Add argocd
- Add chezmoi

### Changed 🔧

- Consolidate progress UI into a ProgressUI class
- Unify cfssl/age bundle installers into add_bundle

### Fixed 🐛

- Use GitLab's latest-release endpoint, fix GitHub headers, dedup resolvers

### Miscellaneous 🧹

- Add repository skeleton config
