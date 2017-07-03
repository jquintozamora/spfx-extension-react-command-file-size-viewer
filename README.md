## react-command-file-size-viewer

This is where you include your WebPart documentation.

### Debuggin the code

```bash
gulp serve --nobrowser
```

Url:

```
https://jquinto.sharepoint.com/sites/dev/Shared%20Documents/Forms/AllItems.aspx?loadSPFX=true&debugManifestsFile=https://localhost:4321/temp/manifests.js&customActions={"5f509a36-9998-4a5f-a5f4-b7d02d4f90b4":{"location":"ClientSideExtension.ListViewCommandSet"}}
```

This package produces the following:

* lib/* - intermediate-stage commonjs build artifacts
* dist/* - the bundled script, along with other resources
* deploy/* - all resources which should be uploaded to a CDN.

### Build options

gulp clean - TODO
gulp test - TODO
gulp serve - TODO
gulp bundle - TODO
gulp package-solution - TODO
