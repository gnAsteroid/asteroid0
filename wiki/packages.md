## packages

**Packages**, whether in [go](go.md) or [GNO](GNO.md), are a way to organize and encapsulate related code. Packages allow developers to group   functions, types, and variables together, making it     easier to manage and reuse code. Each package is defined in its own directory.

If you inspect a source, each line such as `import "p/path/to/something"` imports a package.

GNO distinguishes 2 kinds of packages:

1. [realms](realm.md) - they start by `/r`,
2. [pure packages](pure.md) - they start by `/p`.
