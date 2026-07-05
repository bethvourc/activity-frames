# Acknowledgments

The default capture engine provisioned by `aframes record` is a pinned
build of screenpipe v0.3.324 (Mediar AI), released under the MIT
license. It is downloaded on demand from the public npm registry and is
not bundled with this package. The compiler itself is engine-agnostic:
any capture system writing a compatible SQLite schema works via
`$AFRAMES_DB`.
