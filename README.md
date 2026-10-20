A simple test page for exploring `env(safe-area-inset-*)` behaviour in mobile
browsers. Try it here:

https://tangobravo.github.io/safe-area-insets-demo/

Blue squares are fixed to each corner of the viewport and offset by the
safe-area insets, and the current `safe-area-inset-*` and
`safe-area-max-inset-*` values are shown in px alongside the visual viewport
size.

The page has options to:

- Change the `viewport-fit` value in the viewport meta tag
- Toggle fullscreen, with a choice of `navigationUI` value
- Enter an `immersive-ar` WebXR session with the document as the `dom-overlay`
  root, optionally with `camera-access` as a required feature

The body has a 2000px min-height so scrolling can trigger the browser toolbar
hiding behaviour.

The WebXR setup is based on the ar-barebones sample from the
[Immersive Web WebXR Samples](https://github.com/immersive-web/webxr-samples).
