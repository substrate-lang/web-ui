# web-ui

A UI library for web programs, built on
[Substrate](https://github.com/substrate-lang/substrate) and its std/web. Views
compile to changes of the document. A component joins a view with its state,
messages and update, and attach puts components and views in elements of the
document. Given a routable type, attach also starts the router, which keeps the
URL as a route in step with the browser's history. The router is experimental.

    substrate test -A        # the tests, twelve of them in Chromium
