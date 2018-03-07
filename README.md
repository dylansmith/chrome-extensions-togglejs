Toggle JavaScript Chrome extension
==================================

This is the source code for the "Toggle JavaScript" extension for Google Chrome
or Chromium browsers.

The official extension can be downloaded from the Chrome Web Store.

If you find any of this source code useful, awesome! Tell your friends about the
extension and help me out by giving it a positive review at the Chrome Web
Store.

Description
-----------

> Enable or disable JavaScript without the hassle.

Toggle JavaScript provides a simple, easy-to-access browser button to enable or
disable JavaScript globally. It was built with web developers in mind, but is
equally useful for anyone who wants to quickly enable/disable JavaScript without
having to dig deep into Chrome's Settings panel.

### Features:

- global JavaScript master switch
- reloads when toggling to ensure accurate rendering (optional since v1.3)

### More Info:

There are similar extensions that enable or disable JavaScript per-domain, but I
find this over-complicated so I decided to build a JavaScript "master switch".

Also, similar extensions can cause pages to be rendered inaccurately after
disabling JavaScript. This extension uses an auto-reload technique to ensure
that pages are always rendered correctly after switching JavaScript on or off.

I hope you enjoy using it - if you do, please tell your friends about it and
help me out by giving it a positive review. Thanks!

Changelog
---------

v1.3 (7 March 2018)
- Auto-reload can now be disabled (default: enabled)
- Uses improved chrome.tabs.reload() instead of .duplicate()

v1.2 (11 November 2013)
- Renamed to "Toggle JavaScript"
- Updated readme
- Improved browser action icons

v1.1 (9 November 2013)
- Updated icons

v1.0 (9 November 2013)
- Released initial version
