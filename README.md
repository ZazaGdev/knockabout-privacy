# Knockabout, privacy policy and support

  Public hosting for the privacy policy and support page of **Knockabout**, the party game
  (bundle `com.knockabout.app`).

  **Live pages:** https://zazagdev.github.io/knockabout-privacy/ and
  https://zazagdev.github.io/knockabout-privacy/support.html

  English only. Unlike Martva, this app is not aimed at the Georgian market and its content ships
  in English, so there is no second language here.

  The source of truth is the app repository, at `docs/legal/privacy-policy.md` and
  `docs/legal/support.md`. These HTML files are a static rendering produced by
  `node scripts/build-legal.mjs`.

  **To update:** edit the markdown in the app repository, rerun that script, and copy
  `docs/legal/site/` over this repository. Do not hand-edit the HTML here; the next build
  overwrites it.
  