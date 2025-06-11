# Data Maintenance & Consistency Report - 2025-06-11T09:19:20.632Z

Cron: manual_admin_http

## Phase 1 & 2: User Index Link Integrity and Orphaned File Checks
Attempting to check 1 active users...


**Summary for this run:**
- Users Checked: 1
- Users with Issues Detected/Actions Taken: 1
- Broken Index Links Cleaned from index.json: 0
- Orphaned Physical Files Moved to Quarantine: 1

## Detailed Issues and Actions Log (7):
### Type: CorruptedIndexFile
- User: `testuser`
- Index Path: `testuser/index.json`
- Details: User 'testuser': Error processing/parsing index.json at 'testuser/index.json' - Failed to parse index.json: base64ToArrayBuffer is not defined.

### Type: OrphanedFileDetected
- User: `testuser`
- Physical Path: `testuser/2px.cur`
- Details: User 'testuser': ORPHANED physical file found: 'testuser/2px.cur'. Not in (cleaned) index.json. Attempting to move to 'testuser/_orphaned_files/2px.cur'.

### Type: OrphanedFileMoved
- User: `testuser`
- Old Path (Moved From): `testuser/2px.cur`
- New Path (Moved To): `testuser/_orphaned_files/2px.cur`
- Details: Successfully moved to orphaned files directory.

### Type: OrphanedFileDetected
- User: `testuser`
- Physical Path: `testuser/574c1d14326678741ffc9e8555b269e687b99e140b206e64d46b48dc98ef047b`
- Details: User 'testuser': ORPHANED physical file found: 'testuser/574c1d14326678741ffc9e8555b269e687b99e140b206e64d46b48dc98ef047b'. Not in (cleaned) index.json. Attempting to move to 'testuser/_orphaned_files/574c1d14326678741ffc9e8555b269e687b99e140b206e64d46b48dc98ef047b'.

### Type: OrphanedFileMoveFailed
- User: `testuser`
- Physical Path: `testuser/574c1d14326678741ffc9e8555b269e687b99e140b206e64d46b48dc98ef047b`
- Details: Failed to move orphaned file 'testuser/574c1d14326678741ffc9e8555b269e687b99e140b206e64d46b48dc98ef047b' to quarantine.

### Type: OrphanedFileDetected
- User: `testuser`
- Physical Path: `testuser/5d47abd9ee3ad4f430531b4addfb4d09c18155196e9a597d5fa0a7685c2c79f9`
- Details: User 'testuser': ORPHANED physical file found: 'testuser/5d47abd9ee3ad4f430531b4addfb4d09c18155196e9a597d5fa0a7685c2c79f9'. Not in (cleaned) index.json. Attempting to move to 'testuser/_orphaned_files/5d47abd9ee3ad4f430531b4addfb4d09c18155196e9a597d5fa0a7685c2c79f9'.

### Type: OrphanedFileMoveFailed
- User: `testuser`
- Physical Path: `testuser/5d47abd9ee3ad4f430531b4addfb4d09c18155196e9a597d5fa0a7685c2c79f9`
- Details: Failed to move orphaned file 'testuser/5d47abd9ee3ad4f430531b4addfb4d09c18155196e9a597d5fa0a7685c2c79f9' to quarantine.


**Note**: This report provides outcomes of automated consistency checks. Orphaned files are moved to `_orphaned_files/` subdirectory within each user's folder. Broken links are removed from the live `index.json`. Manual review may be needed for complex or recurring issues.
