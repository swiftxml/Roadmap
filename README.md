# Roadmap

A roadmap of things that should or could come for the SwiftXML project.

## Known issues

Known issues should be resolved as soon as possible.

- Pipeline: A first compilation (or after `swift package clean`) gives warnings about missing dependencies (but then compiles just fine).

## Additions

Additional features may be implemented, provided the necessary resources are available.

- A streaming interface for the parser.
- A validation package (presumingly for W3C schemas).
- A Windows GUI for a “typical” application that uses the Pipeline framework.
- GUIs for other platforms.

## Breaking changes

The implementation of breaking changes requires a new major version. To prevent too many major versions to happen, breaking changes should first be collected here, allowing to implement them at once.

### Breaking changes: Renaming

- EventProcessorForLogger: Argument `excutionInfoFormat` → `infoFormat`