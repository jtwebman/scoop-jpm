# scoop-jpm

The [Scoop](https://scoop.sh) bucket for [jpm](https://github.com/jtwebman/jpm), a fast, small,
secure-by-default package manager for JavaScript. Windows x64 and arm64.

```powershell
scoop bucket add jpm https://github.com/jtwebman/scoop-jpm
scoop install jpm
```

`scoop update jpm` takes each new release. The manifest installs jpm's release binary, the one
`irm https://getjpm.sh/install.ps1 | iex` installs, after checking its SHA-256, with `jpx` beside
it. A scheduled workflow picks up each new release on its own.

More about jpm: [getjpm.sh](https://getjpm.sh).
