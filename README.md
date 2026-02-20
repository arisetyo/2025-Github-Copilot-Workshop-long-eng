Check the build site here: [https://stghuniverse.z45.web.core.windows.net/#0](https://stghuniverse.z45.web.core.windows.net/#0)

How to build:
```
~/go/bin/claat export <name of the markdown file>
```

Example:
```
~/go/bin/claat export workshop.md
```

The value of `id` in the header of the markdown file determines the name of folder for the built HTML file.

On the github workflow, the file that will be built is the `workshop.md` file. So if you need it to be deployed online, make sure the latest one is `workshop.md`.