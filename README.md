# webapps

web applications deployed directly on github

- add the WASM/shinylive to a new folder within the `site` directory (e.g. `site/appX`).
- optionally, add a folder with the non-WASM/shinylive equivalent outside of the site directory. When deploying, something like `shinylive::export("appdir", "site/appname")` can be used to compile the non-shinylive version to WASM and store it ready for deployment.
- update `site/readme.md` to include a link to the app (relative to `site`).
