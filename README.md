# verify-device-card

A single, self-contained sign-in screen: the "Sign in again to verify your
device" card with a looping CSS scan animation over a laptop drawing. Nothing
else on the page.

**Live:** <https://ogabek-karimov.github.io/verify-device-card/>

- One file — `index.html`. No build, no dependencies, no images, no JavaScript
  for the animation itself (a few lines only wire up the theme toggle).
- Follows the visitor's light / dark system setting, with a small toggle in the
  corner to override it.
- Respects `prefers-reduced-motion`.

Open `index.html` directly, or serve the folder with `npx serve .`.

The animation component on its own (CSS + markup + web component) lives in
[signin-scan-animation](https://github.com/ogabek-karimov/signin-scan-animation).

## License

MIT — see [LICENSE](LICENSE).
