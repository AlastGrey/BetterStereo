# Third-party assemblies

## Reactor.dll

- Version: 2.5.1
- Source: https://github.com/NuclearPowered/Reactor/releases/tag/2.5.1
- SHA-256: `403F6C506E7AD0872B3B6833731066272553F20EB037D7DB8962A406A5271E5E`
- License: LGPL-3.0

Among Us 19.0 crashes during startup with Reactor 2.3.1, the newest version published to NuGet. The
Mitochondria 0.14.0 packages still pull 2.3.1 transitively, so `Stereo.csproj` excludes that package's
assets and compiles against this 2.5.1 assembly instead.
