# Pull request evidence for upstream issue 342

The screenshots were captured from `https://rsi.grivn.dev/` with commit
`0f3cd060536b72644a244c28f60379a534ce07ca` linked into the live DSH web
profile. The authenticated same-origin compatibility bridge returned HTTP 200,
the Web UI Plugins and Community Plugins settings controls were available, and
the namespace exposure warnings were absent.

The `before-*` screenshots use the same build with `trustedProxyHosts` empty;
the `after-*` screenshots use the documented authenticated-proxy config. The
browser audit also covered Skin Center and Pet: all four first-level family
settings sections had zero namespace-exposure warnings after the change.

This branch contains evidence only and is not part of the pull request diff.
