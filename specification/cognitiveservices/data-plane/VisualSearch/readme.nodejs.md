## Node.js

These settings apply only when `--nodejs` is specified on the command line.
Please also specify `--node-sdks-folder=<path to root folder of your azure-sdk-for-node clone>`.

``` yaml $(nodejs)
nodejs:
  package-name: azure-cognitiveservices-visualsearch
  package-version: 1.0.0-preview
  output-folder: $(node-sdks-folder)/lib/services/visualSearch
  override-client-name: VisualSearchAPIClient
  azure-arm: false
  generate-license-txt: true
  generate-package-json: true
  generate-readme-md: false
```
