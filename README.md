# vikqazi.github.io: forwarding pages only

Flightline is now Fowl Atlas, at https://fowlatlas.com/. These pages send old links there, keeping the path
(minus /flightline), the query and the #map view, and bring along the items the old app saved in this browser
(saved spots, hunt log, settings; never a sign-in session or token).

- `index.html`: vikqazi.github.io/ itself.
- `flightline/index.html`: vikqazi.github.io/flightline/ (served once the vikqazi/flightline repo is private;
  until then that repo's own page answers there and does the same thing).
- `404.html`: every other vikqazi.github.io/flightline/<path>. Any other missing path just says "no page here".

Generated: do not edit by hand. They come from the Fowl Atlas build (`tools/mkforwarder.js`, logic in
`nhdata/canon.js`). Never put the app or its data here.
