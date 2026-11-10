# web-ui

A UI library for web pages, built on
[Substrate](https://github.com/substrate-lang/substrate) and its std/web. Views
compile to changes of the page. A component joins a view with its state,
messages and update, and attach puts components in elements of the page. It is
experimental.

    substrate test -A        # the tests, two of them in Chromium
