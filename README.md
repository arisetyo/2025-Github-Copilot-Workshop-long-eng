Check the build site here: [https://stghuniverse.z45.web.core.windows.net/#0](https://stghuniverse.z45.web.core.windows.net/#0)

How to build the codelabs from its markdown source:
```
~/go/bin/claat export <name of the markdown file>
```

Example:
```
~/go/bin/claat export workshop.md
```

To serve the resulting codelabs locally, run:
```
~/go/bin/claat serve
```
This starts a local web server (default http://localhost:9090) in the current directory, serving the generated codelab folders. Open the URL in your browser to preview your codelabs.

The value of `id` in the header of the markdown file determines the name of folder for the built HTML file.

On the github workflow, the file that will be built is the `workshop.md` file. So if you need it to be deployed online, make sure the latest one is `workshop.md`.
Push to `upstream` ([https://github.com/eComindo/2025-Github-Copilot-Workshop-long-eng](https://github.com/eComindo/2025-Github-Copilot-Workshop-long-eng)) to build in the build site mentioned above.
```
git push upstream
```