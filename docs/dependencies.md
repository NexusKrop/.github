# Dependency Guidelines

## .NET

### Replace or Remove

- Moq: Either `NSubstitute` or [our own Moq build](https://codeberg.org/NexusKrop/moq-build).
- Nugetizer, ThisAssembly, and anything that depends on SponsorLink: No way, unless it is a fork/build which have no SponsorLink.
- SponsorLink itself.
- All of commerical libraries: No way.
