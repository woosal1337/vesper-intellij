# Vesper for JetBrains

Peppermint and orange flavored dark theme for JetBrains IDEs. One to one port of the [Vesper VSCode theme](https://github.com/raunofreiberg/vesper) by Rauno Freiberg.

Works in IntelliJ IDEA, PyCharm, WebStorm, PhpStorm, RubyMine, GoLand, CLion, Rider, DataGrip, RustRover, and any other IntelliJ Platform IDE on build 231 and newer.

## Install

From the IDE, `Settings` → `Plugins` → `Marketplace` → search `Vesper`. Or grab the latest build from [Releases](https://github.com/woosal1337/vesper-intellij/releases) and install from disk.

After install, switch to it under `Settings` → `Appearance & Behavior` → `Appearance` → `Theme`. The bundled editor color scheme is applied automatically.

## Build from source

```
./gradlew buildPlugin
```

The distributable zip lands in `build/distributions/`.

To try it out in a sandbox IDE,

```
./gradlew runIde
```

## Credits

Original VSCode theme, [Rauno Freiberg](https://github.com/raunofreiberg/vesper). JetBrains port, [Ege Çelebi](https://github.com/woosal1337).

## License

MIT. See `LICENSE.md`.
