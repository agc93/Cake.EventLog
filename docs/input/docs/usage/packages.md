---
Order: 30
Title: Packages
---

# Packages

You can include the addin in your script with:

```
#addin nuget:?package=Cake.EventLog

//or to use the latest development release
#addin nuget:?package=Cake.EventLog&prerelease
```

The NuGet prerelease packages are automatically built and published from the `develop` branch so they can be considered bleeding-edge while the non-prerelease packages will be much more stable.

Versioning is predominantly SemVer-compliant so you can set your version constraints if you're worried about changes.