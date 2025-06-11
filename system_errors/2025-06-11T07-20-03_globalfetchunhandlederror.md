# GlobalFetchUnhandledError - 2025-06-11T07:20:03.839Z

## Error Message
```
Encrypted physical file (hash: 574c1d14326678741ffc9e8555b269e687b99e140b206e64d46b48dc98ef047b) not found at 'testuser/574c1d14326678741ffc9e8555b269e687b99e140b206e64d46b48dc98ef047b'. Index/Storage inconsistency.
```

## Stack Trace
```
Error: Encrypted physical file (hash: 574c1d14326678741ffc9e8555b269e687b99e140b206e64d46b48dc98ef047b) not found at 'testuser/574c1d14326678741ffc9e8555b269e687b99e140b206e64d46b48dc98ef047b'. Index/Storage inconsistency.
    at handleFileDownload (index.js:887:19)
    at async routeRequest (index.js:1644:16)
    at async Object.fetch (index.js:2032:18)
```

## Additional Context
- Trigger/Request: GET https://file.bob6.dpdns.org/v1/files/testuser/2.zip
- Ray ID: 94df57f61a132ae1

## Environment (Non-Sensitive)
- GITHUB_REPO_OWNER: bobfile666
- TARGET_BRANCH: main
- API_VERSION: v1
---
