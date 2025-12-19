# grease-generic-dark
Attempts to autodetect non-dark sites and applies a generic dark mode on them.

The method `isDark()` applies different methods to asses the current site, and if none of them indicate an existing dark mode then a generic dark mode is applied.
  - `prefersDarkAndSiteSupportsIt()`
  - `siteDeclaresDarkMode()`
  - `hasDarkBackground()`
  - `hasDarkThemeClass()`

The method `applyGenericDarkMode()` is based on [Dark mode](https://greasyfork.org/en/scripts/472251-dark-mode/post-install) from Greasy Fork.
