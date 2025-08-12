# Swiftly Swift - Github Action

A Github Action to install [Swiftly](https://www.swift.org/swiftly/documentation/swiftlydocs/) and a swift toolchain. Works with MacOS and Linux runners.

```yaml
  - uses: beeauvin/swiftly-swift@v1
    with:
      swift-version: 6.1
```

`swift-version` is the Swift Toolchain version that Swiftly will install and defaults to `latest`. Any version string supported by Swiftly (including snapshots) should work.

### Windows

Unfortunately [Swiftly doesn't currently support windows](https://github.com/swiftlang/swiftly/issues/151) so this action doesn't either. Open to contributions to get it working with currently available install methods until Swiftly has support for it.

## License

Swiftly Swift is available under the [Mozilla Public License 2.0](https://mozilla.org/MPL/2.0/).

A copy of the MPLv2 is included [license.md](/license.md) file for convenience.
