# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Added
- Add maintainers list: Added `MAINTAINERS.md` file with the list of maintainers for the project.
- Support body with no model: Added support for body with no model.
- Update interceptor_to_embeddings_handler: Updated interceptor_to_embeddings_handler.

### Changed
- Pin poetry to 1.8.5: Pinned poetry version to 1.8.5.
- Bump epam/ai-dial-ci from 1.10.0 to 1.10.2: Updated epam/ai-dial-ci version.
- Bump jinja2 from 3.1.4 to 3.1.5: Updated jinja2 version.
- Bump starlette from 0.36.3 to 0.40.0; fastapi from 0.109.2 to 0.115.2: Updated starlette and fastapi versions.
- Migrated aiohttp from 3.9.5 to 3.10.2: Updated aiohttp version.
- Bump epam/ai-dial-ci from 1.9.1 to 1.9.2: Updated epam/ai-dial-ci version.
- Bump epam/ai-dial-ci from 1.9.2 to 1.9.4: Updated epam/ai-dial-ci version.
- Bump epam/ai-dial-ci from 1.9.4 to 1.10.0: Updated epam/ai-dial-ci version.
- Bump epam/ai-dial-ci from 1.10.0 to 1.10.2: Updated epam/ai-dial-ci version.
- Bump aiohttp from 3.10.2 to 3.10.11: Updated aiohttp version.
- Bump protobuf from 5.29.0 to 5.29.1: Updated protobuf version.

### Fixed
- Fixed propagation of exceptions from upstream endpoints.
- Fixed Makefile.
- Fixed package_root_dir helper.

### Removed
- Removed en-core-web-sm as an explicit dependency.
- Removed assets from the package.

