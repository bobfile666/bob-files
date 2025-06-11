# Data Maintenance & Consistency Report - 2025-06-11T07:48:38.197Z

Cron: manual_admin_http

## Phase 1 & 2: User Index Link Integrity and Orphaned File Checks
Attempting to check 1 active users...

Checked 1 users. Found issues for 1 users. Moved 4 orphaned files.

## Detailed Issues and Actions (13):
### Type: CorruptedIndexFile
- User: testuser
- Index Path: `testuser/index.json`
- Details: User 'testuser': Error processing/parsing index.json at 'testuser/index.json' - Failed to parse index.json: base64ToArrayBuffer is not defined.

### Type: OrphanedFile
- User: testuser
- Physical Path: `testuser/51494369717bc9e6027b969f895e578ce601b7c88be3c1741718eb4d307e00d5`
- Details: User 'testuser': ORPHANED physical file found: 'testuser/51494369717bc9e6027b969f895e578ce601b7c88be3c1741718eb4d307e00d5'. Not in index.json. Attempting to move to 'testuser/_orphaned_files/51494369717bc9e6027b969f895e578ce601b7c88be3c1741718eb4d307e00d5'.

### Type: OrphanedFileMoved
- User: testuser
- Old Path: `testuser/51494369717bc9e6027b969f895e578ce601b7c88be3c1741718eb4d307e00d5`
- New Path (Moved To): `testuser/_orphaned_files/51494369717bc9e6027b969f895e578ce601b7c88be3c1741718eb4d307e00d5`
- Details: Successfully moved to orphaned files directory.

### Type: OrphanedFile
- User: testuser
- Physical Path: `testuser/574c1d14326678741ffc9e8555b269e687b99e140b206e64d46b48dc98ef047b`
- Details: User 'testuser': ORPHANED physical file found: 'testuser/574c1d14326678741ffc9e8555b269e687b99e140b206e64d46b48dc98ef047b'. Not in index.json. Attempting to move to 'testuser/_orphaned_files/574c1d14326678741ffc9e8555b269e687b99e140b206e64d46b48dc98ef047b'.

### Type: OrphanedFileMoveFailed
- User: testuser
- Physical Path: `testuser/574c1d14326678741ffc9e8555b269e687b99e140b206e64d46b48dc98ef047b`
- Details: Failed to move orphaned file 'testuser/574c1d14326678741ffc9e8555b269e687b99e140b206e64d46b48dc98ef047b' to quarantine.

### Type: OrphanedFile
- User: testuser
- Physical Path: `testuser/5d47abd9ee3ad4f430531b4addfb4d09c18155196e9a597d5fa0a7685c2c79f9`
- Details: User 'testuser': ORPHANED physical file found: 'testuser/5d47abd9ee3ad4f430531b4addfb4d09c18155196e9a597d5fa0a7685c2c79f9'. Not in index.json. Attempting to move to 'testuser/_orphaned_files/5d47abd9ee3ad4f430531b4addfb4d09c18155196e9a597d5fa0a7685c2c79f9'.

### Type: OrphanedFileMoveFailed
- User: testuser
- Physical Path: `testuser/5d47abd9ee3ad4f430531b4addfb4d09c18155196e9a597d5fa0a7685c2c79f9`
- Details: Failed to move orphaned file 'testuser/5d47abd9ee3ad4f430531b4addfb4d09c18155196e9a597d5fa0a7685c2c79f9' to quarantine.

### Type: OrphanedFile
- User: testuser
- Physical Path: `testuser/815704716c4710b5b06133a3fffa59867a56cc7862d18a4acb6b1ebbdc7e0e73`
- Details: User 'testuser': ORPHANED physical file found: 'testuser/815704716c4710b5b06133a3fffa59867a56cc7862d18a4acb6b1ebbdc7e0e73'. Not in index.json. Attempting to move to 'testuser/_orphaned_files/815704716c4710b5b06133a3fffa59867a56cc7862d18a4acb6b1ebbdc7e0e73'.

### Type: OrphanedFileMoved
- User: testuser
- Old Path: `testuser/815704716c4710b5b06133a3fffa59867a56cc7862d18a4acb6b1ebbdc7e0e73`
- New Path (Moved To): `testuser/_orphaned_files/815704716c4710b5b06133a3fffa59867a56cc7862d18a4acb6b1ebbdc7e0e73`
- Details: Successfully moved to orphaned files directory.

### Type: OrphanedFile
- User: testuser
- Physical Path: `testuser/8703d7ef897fe08f6fb5b3f94678c51fcfbabd5c4512e49db18f967d57b0ccd1`
- Details: User 'testuser': ORPHANED physical file found: 'testuser/8703d7ef897fe08f6fb5b3f94678c51fcfbabd5c4512e49db18f967d57b0ccd1'. Not in index.json. Attempting to move to 'testuser/_orphaned_files/8703d7ef897fe08f6fb5b3f94678c51fcfbabd5c4512e49db18f967d57b0ccd1'.

### Type: OrphanedFileMoved
- User: testuser
- Old Path: `testuser/8703d7ef897fe08f6fb5b3f94678c51fcfbabd5c4512e49db18f967d57b0ccd1`
- New Path (Moved To): `testuser/_orphaned_files/8703d7ef897fe08f6fb5b3f94678c51fcfbabd5c4512e49db18f967d57b0ccd1`
- Details: Successfully moved to orphaned files directory.

### Type: OrphanedFile
- User: testuser
- Physical Path: `testuser/d2aca41bce7c99cf8579baad04a10d4352aefa75610dd0fa170eb403e46332bf`
- Details: User 'testuser': ORPHANED physical file found: 'testuser/d2aca41bce7c99cf8579baad04a10d4352aefa75610dd0fa170eb403e46332bf'. Not in index.json. Attempting to move to 'testuser/_orphaned_files/d2aca41bce7c99cf8579baad04a10d4352aefa75610dd0fa170eb403e46332bf'.

### Type: OrphanedFileMoved
- User: testuser
- Old Path: `testuser/d2aca41bce7c99cf8579baad04a10d4352aefa75610dd0fa170eb403e46332bf`
- New Path (Moved To): `testuser/_orphaned_files/d2aca41bce7c99cf8579baad04a10d4352aefa75610dd0fa170eb403e46332bf`
- Details: Successfully moved to orphaned files directory.

**Note**: This report provides basic consistency checks. Orphaned files are moved to `_orphaned_files/` subdirectory within each user's folder. Manual review may be needed.
