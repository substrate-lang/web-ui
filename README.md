# web-ui

A UI library for web programs, built on
[Substrate](https://github.com/substrate-lang/substrate) and its std/web. Views
compile to changes of the document, and can hold SVG as well as HTML. A
component joins a view with its state, messages and update. app gathers
components and views into an app, which attach puts in elements of the
document, and which a server can write into a page's HTML with app-render. When
the app's component takes routes, attach also starts the router, which keeps the
URL as a route in step with the browser's history.

    substrate test -A        # the tests, fourteen of them in Chromium
