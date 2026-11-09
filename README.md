# hello

The plugin that tests [Sleip's registry](https://github.com/sephiroth74/sleip-registry), its pull requests and releases, as Sleip's own `sleip new` makes it.

A plugin of [Lokyr](https://lokyr.dev), made by `sleip new`: its command,
Say Hello, shows a notice at the top of the window.

- `src/init.luau`: the plugin, its callbacks, which `lokyr.d.luau` types.
- `plugin.toml`: its manifest, its name, version, activation, capabilities
  and commands.
- `locales/en/hello.ftl`: its texts in English, which other languages join.
- `tests/hello.luau`: its tests.

`sleip check` checks it, `sleip test` runs its tests, and `sleip dev` links
it into Lokyr, which reloads it at each save.
