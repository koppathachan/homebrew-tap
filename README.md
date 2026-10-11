# koppathachan/homebrew-tap

Homebrew packages for [kyu](https://github.com/koppathachan/kyu), a message
queue that runs on storage it does not implement.

```sh
brew install --cask koppathachan/tap/kyu
```

That installs both binaries: `kyu`, the queue engine, and `kyu-memstore`, the
reference storage server, which keeps everything in memory and is for trying
kyu out. Run `kyu -version` to see which release you have.

The casks in `Casks/` are written by kyu's release workflow on every tagged
release. Do not edit them by hand: the next release overwrites them. Report
problems on [kyu's issue tracker](https://github.com/koppathachan/kyu/issues).
