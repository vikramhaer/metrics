## Metrics package

A package that reports usage information to [Google Analytics][GA].

If you do not want this information reported, disable this package from the
_Metrics_ section of the Settings view (`cmd-,`).

### Collected Data

* A unique identifier that is generated by computing the [SHA-1][SHA1] of the
  machine's [MAC address][MAC].
* The screen width and height
* The version of Atom being used
* The name of each item opened in a pane such as `EditorView`, `SettingsView`,
  and `MarkdownPreviewView`
* The amount of time the current window was open for
* The amount of time the current window to took to load
* The amount of time the app took to launch

[GA]: http://www.google.com/analytics
[MAC]: http://en.wikipedia.org/wiki/MAC_address
[SHA1]: http://en.wikipedia.org/wiki/SHA-1
