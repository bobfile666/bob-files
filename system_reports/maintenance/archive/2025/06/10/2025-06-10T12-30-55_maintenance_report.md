# Data Maintenance & Consistency Report - 2025-06-11T12:21:10.838Z

Cron: manual_admin_http

## Phase 1 & 2: User Index Link Integrity and Orphaned File Checks
Attempting to check 1 active users...


**Summary for this run:**
- Users Checked: 1
- Users with Issues/Actions: 1
- Broken Index Links Cleaned: 0
- Orphaned Physical Files Moved: 1

## Detailed Issues and Actions Log (7):
### Type: CorruptedIndexFile
- User: `testuser`
- Index Path: `testuser/index.json`
- Details: User 'testuser': Error processing/parsing index.json at 'testuser/index.json' - undefined.

### Type: OrphanedFileDetected
- User: `testuser`
- Physical Path: `testuser/52694e2f042f59479e99080b050d2d6a08ea1e093e4c73cc22f01d5a7e3baace`
- Details: User 'testuser': ORPHANED physical file found: 'testuser/52694e2f042f59479e99080b050d2d6a08ea1e093e4c73cc22f01d5a7e3baace'. Not in original index.json. Attempting to move.

### Type: OrphanedFileMoved
- User: `testuser`
- Old Path (Moved From): `testuser/52694e2f042f59479e99080b050d2d6a08ea1e093e4c73cc22f01d5a7e3baace`
- New Path (Moved To): `testuser/_orphaned_files/52694e2f042f59479e99080b050d2d6a08ea1e093e4c73cc22f01d5a7e3baace`
- Details: Successfully moved to orphaned files directory.

### Type: OrphanedFileDetected
- User: `testuser`
- Physical Path: `testuser/574c1d14326678741ffc9e8555b269e687b99e140b206e64d46b48dc98ef047b`
- Details: User 'testuser': ORPHANED physical file found: 'testuser/574c1d14326678741ffc9e8555b269e687b99e140b206e64d46b48dc98ef047b'. Not in original index.json. Attempting to move.

### Type: OrphanedFileMoveFailed
- User: `testuser`
- Physical Path: `testuser/574c1d14326678741ffc9e8555b269e687b99e140b206e64d46b48dc98ef047b`
- Details: Failed to move orphaned file 'testuser/574c1d14326678741ffc9e8555b269e687b99e140b206e64d46b48dc98ef047b' to quarantine.

### Type: OrphanedFileDetected
- User: `testuser`
- Physical Path: `testuser/5d47abd9ee3ad4f430531b4addfb4d09c18155196e9a597d5fa0a7685c2c79f9`
- Details: User 'testuser': ORPHANED physical file found: 'testuser/5d47abd9ee3ad4f430531b4addfb4d09c18155196e9a597d5fa0a7685c2c79f9'. Not in original index.json. Attempting to move.

### Type: OrphanedFileMoveFailed
- User: `testuser`
- Physical Path: `testuser/5d47abd9ee3ad4f430531b4addfb4d09c18155196e9a597d5fa0a7685c2c79f9`
- Details: Failed to move orphaned file 'testuser/5d47abd9ee3ad4f430531b4addfb4d09c18155196e9a597d5fa0a7685c2c79f9' to quarantine.


**Note**: This report provides outcomes of automated consistency checks. Orphaned files are moved to `_orphaned_files/` subdirectory. Broken links are removed from the live `index.json`. Manual review may be needed for complex or recurring issues.
