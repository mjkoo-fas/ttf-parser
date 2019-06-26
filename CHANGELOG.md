# Change Log
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/)
and this project adheres to [Semantic Versioning](http://semver.org/).

## [Unreleased]
### Added
- Vertical metrics querying from the `vmtx` table.
- OpenType fonts are allowed now.
- High Byte Mapping Through Table (2) `cmap` subtable support.
- Unicode Variation Sequences (14) `cmap` subtable support.
- `no_std` compatibility.

### Changed
- A major rewrite. TrueType tables are no longer public.
- Use `GlyphId` instead of `u16`.

### Fixed
- `GDEF` table parsing.

[Unreleased]: https://github.com/RazrFalcon/ttf-parser/compare/v0.1.0...HEAD