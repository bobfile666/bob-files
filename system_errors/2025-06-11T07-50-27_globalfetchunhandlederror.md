# GlobalFetchUnhandledError - 2025-06-11T07:50:27.267Z

## Error Message
```
Encrypted physical file (hash: 574c1d14326678741ffc9e8555b269e687b99e140b206e64d46b48dc98ef047b) not found at 'testuser/574c1d14326678741ffc9e8555b269e687b99e140b206e64d46b48dc98ef047b'. Index/Storage inconsistency.
```

## Stack Trace
```
Error: Encrypted physical file (hash: 574c1d14326678741ffc9e8555b269e687b99e140b206e64d46b48dc98ef047b) not found at 'testuser/574c1d14326678741ffc9e8555b269e687b99e140b206e64d46b48dc98ef047b'. Index/Storage inconsistency.
    at handleFileDownload (index.js:914:19)
    at async routeRequest (index.js:1671:16)
    at async Object.fetch (index.js:2170:18)
```

## Additional Context
- Trigger/Request: GET https://file.bob6.dpdns.org/v1/files/testuser/2.zip
- Ray ID: 94df847caf952f76

## Environment (Non-Sensitive)
- GITHUB_REPO_OWNER: bobfile666
- TARGET_BRANCH: main
- API_VERSION: v1
---
