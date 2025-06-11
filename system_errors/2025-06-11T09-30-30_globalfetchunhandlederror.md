# GlobalFetchUnhandledError - 2025-06-11T09:30:30.117Z

## Error Message
```
Encrypted physical file (hash: d44785c55b7b15f282c8ba34b85ac9f79ef3772a6af92fe9149f4407597b38b9) not found at 'testuser/d44785c55b7b15f282c8ba34b85ac9f79ef3772a6af92fe9149f4407597b38b9'. Index/Storage inconsistency. This issue has been logged for review.
```

## Stack Trace
```
Error: Encrypted physical file (hash: d44785c55b7b15f282c8ba34b85ac9f79ef3772a6af92fe9149f4407597b38b9) not found at 'testuser/d44785c55b7b15f282c8ba34b85ac9f79ef3772a6af92fe9149f4407597b38b9'. Index/Storage inconsistency. This issue has been logged for review.
    at handleFileDownload (index.js:1011:19)
    at async routeRequest (index.js:1777:16)
    at async Object.fetch (index.js:2386:18)
```

## Additional Context
- Trigger/Request: GET https://file.bob6.dpdns.org/v1/files/testuser/aaa.jpg
- Ray ID: 94e01705cdd208fa

## Environment (Non-Sensitive)
- GITHUB_REPO_OWNER: bobfile666
- TARGET_BRANCH: main
- API_VERSION: v1
---
