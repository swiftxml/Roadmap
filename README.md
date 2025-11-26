# Roadmap

A roadmap of things that should or could come for the SwiftXML project.

## Known problems

- Pipeline: A first compilation (or after `swift package clean`) gives warnings about missing dependencies (but then compiles just fine).

## Additions

- A validation package (presumingly for W3C schemas).

## Breaking changes

The implementation of breaking requires a new major version. To prevent too many major versions to happen, breaking changes should first be collected here, allowing to implement them at once.

### Renaming

- EventProcessorForLogger: Argument `excutionInfoFormat` → `infoFormat`