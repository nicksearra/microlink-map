# CLAUDE.md - microlink-map

## PROJECT RECORD

The record of record for this project is IN THIS REPOSITORY:

    .record/STATE.md
    .record/LOG.md

Git is the durability and the remote is the off-machine copy. Neither of them
depends on a drive letter.

PART 0, BEFORE ANYTHING ELSE: read both of those files.

PART C, AT THE END OF EVERY SESSION: write both files, stage them by name,
commit them and push them, then read each one back off disk and print its byte
size and LastWriteTime. A write that cannot be read back at its new size did
not happen.

THE DRIVE PATH IS A MIRROR, NOT THE RECORD:

    G:\My Drive\MicroLink\04 Operations\06 Project Record\proj-microlink-map\

Copy the two files there when Test-Path on the record root succeeds. When it
returns False, skip the copy and print one line saying the mirror was skipped
because the mount is down, then carry on. Report a missing mount; never stop
for it. A missing mount is never a reason to stop a session and never blocks
PART C.

THESE ARE DEAD. DO NOT FOLLOW THEM:

    H:\My Drive\...
    %USERPROFILE%\Google Drive\...
    G:\.shortcut-targets-by-id\...
    any "try each drive letter in turn" instruction

Older handoff notes name all four. Every one of them is wrong, and a record
found at one of them is a stale copy, not the record.
