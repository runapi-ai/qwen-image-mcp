# Changelog

## [v0.2.0](https://github.com/runapi-ai/qwen-image-mcp/releases/tag/v0.2.0) - 2026-09-30

### Changed
- Send tool arguments to the service without local model, enum, range, required-field, or cross-field validation. Tool descriptions still list declared types and known values.
  Migration: Invalid arguments now return the service's error, including its message, instead of a local tool-input rejection.


## [v0.1.1](https://github.com/runapi-ai/qwen-image-mcp/releases/tag/v0.1.1) - 2026-07-31

### Changed
- Resolve MCP prices from the RunAPI Price Schedule API instead of embedded package data.


## [v0.1.0](https://github.com/runapi-ai/qwen-image-mcp/releases/tag/v0.1.0) - 2026-07-22

### Added
- Add focused Qwen Image generation, remix, edit, task polling, and pricing tools.
