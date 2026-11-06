# webapps

web applications deployed directly on github

- add the WASM/shinylive to a new folder within the `docs` directory (e.g. `docs/appX`).
- optionally, add a folder with the non-WASM/shinylive equivalent outside of the site directory. When deploying, something like `shinylive::export("appdir", "docs/appname")` can be used to compile the non-shinylive version to WASM and store it ready for deployment.
- update `docs/readme.md` to include a link to the app (relative to `docs`; the directory name is generally enough).
