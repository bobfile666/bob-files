# Data Maintenance & Consistency Report - 2025-06-11T12:29:55.328Z

Cron: manual_admin_http

## Phase 1 & 2: User Index Link Integrity and Orphaned File Checks
Attempting to check 1 active users...


**Summary for this run:**
- Users Checked: 1
- Users with Issues/Actions: 1
- Broken Index Links Cleaned: 0
- Orphaned Physical Files Moved: 1

## Detailed Issues and Actions Log (5):
### Type: CorruptedIndexFile
- User: `testuser`
- Index Path: `testuser/index.json`
- Details: User 'testuser': Error processing/parsing index.json at 'testuser/index.json' - undefined.

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
- Physical Path: `testuser/815704716c4710b5b06133a3fffa59867a56cc7862d18a4acb6b1ebbdc7e0e73`
- Details: User 'testuser': ORPHANED physical file found: 'testuser/815704716c4710b5b06133a3fffa59867a56cc7862d18a4acb6b1ebbdc7e0e73'. Not in original index.json. Attempting to move.

### Type: OrphanedFileMoved
- User: `testuser`
- Old Path (Moved From): `testuser/815704716c4710b5b06133a3fffa59867a56cc7862d18a4acb6b1ebbdc7e0e73`
- New Path (Moved To): `testuser/_orphaned_files/815704716c4710b5b06133a3fffa59867a56cc7862d18a4acb6b1ebbdc7e0e73`
- Details: Successfully moved to orphaned files directory.


**Note**: This report provides outcomes of automated consistency checks. Orphaned files are moved to `_orphaned_files/` subdirectory. Broken links are removed from the live `index.json`. Manual review may be needed for complex or recurring issues.
