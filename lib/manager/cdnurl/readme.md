**Important**: This manager isn't aware of subresource integrity (SRI) hashes. It will search/replace any matching url it finds, without consideration for things such as script integrity hashes.

To enable this manager, add the matching files to `cdnurl.fileMatch`. For example:

```json
{
  "cdnurl": {
    "fileMatch": ["\\.html?$"]
  }
}
```
