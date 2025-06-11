# GlobalFetchUnhandledError - 2025-06-11T09:22:36.352Z

## Error Message
```
Failed to retrieve content for existing physical file (hash: 574c1d14326678741ffc9e8555b269e687b99e140b206e64d46b48dc98ef047b).
```

## Stack Trace
```
Error: Failed to retrieve content for existing physical file (hash: 574c1d14326678741ffc9e8555b269e687b99e140b206e64d46b48dc98ef047b).
    at handleFileDownload (index.js:1023:19)
    at async routeRequest (index.js:1777:16)
    at async Object.fetch (index.js:2332:18)
```

## Additional Context
- Trigger/Request: GET https://file.bob6.dpdns.org/v1/files/testuser/2.zip
- Ray ID: 94e00b750c4d100b

## Environment (Non-Sensitive)
- GITHUB_REPO_OWNER: bobfile666
- TARGET_BRANCH: main
- API_VERSION: v1
---
