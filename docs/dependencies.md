# Dependency Guidelines

This documentation serves as the rules of which dependencies may or may not be used in NexusKrop projects.

## .NET

### Explicit Prohibition

- `nugetizer`, `Moq`, `This Assembly` and all other NuGet packages made by the same authors as of the packages above
- Any commerical stuff requiring purchase
- SponsorLink or anything with the same objective (or anything that depends on such).

### Rules

- No `SponsorLink`. If any slowdowns were caused by SponsorLink-ed projects, such dependencies must be forked or replaced with another dependency. We do not accept SponsorLink, and we urge you not to sponsor any projects using SponsorLink. *Any contributions adding SponsorLink or dependencies which depends on it or have dependencies depend on it, etc. will be refused.*
