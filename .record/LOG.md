# microlink-map - project record: LOG

Append only. Newest entry at the top.
Entry shape: ## YYYY-MM-DD [tag] short title, with an evidence line under it.

## 2026-09-10 [record] Session close, commit and push result

evidence: the record commit in this repository is e727038, message
"record: add in-repo project record and CLAUDE.md rule". Push succeeded to https://github.com/MicroLink-Data-Centers/microlink-map.git.
This entry exists because a commit cannot contain its own hash, so the hash and
the push result of the commit above are stamped here in a second commit.

evidence: session totals, read by command. 93 directories under
C:\Users\Dell\Code, 63 of them git repositories. 63 records created, 63 LOG.md
created, 60 CLAUDE.md created and 3 record blocks replaced. Pushes: 54
succeeded, 6 skipped for no remote, 3 failed. The three failures are
microlink-hq-v3 (HTTP 403, no write access), microlinkdc-mcs (HTTP 403, no
write access) and microlink-loom (non-fast-forward, 1 ahead and 5 behind
origin/main). In all three the record is committed locally and is not yet
off-machine.

evidence: Drive mirror SKIPPED because the mount is down. Test-Path on
"G:\My Drive\MicroLink\04 Operations\06 Project Record" returned False and
Get-PSDrive listed only C and Temp. The skip did not stop the session and did
not block this write.

evidence: Desktop handoff files corrected in place. Line numbers as they stand
after the edit: "Come code with us.. ;).md" lines 123, 125 and 289-296; "Give me
a G drive for coding.md" lines 184-196; "My daily streatch.md" lines 29-37;
"Daily Run Instructions.md" lines 207-211. The drive-letter ladder is gone from
all four.

evidence: NOT corrected, outside the named scope of this session, and each still
declares the Drive path the only record and instructs a session to STOP when it
is missing: C:\Users\Dell\Code\CLAUDE.md, the tail block of each of those four
Desktop files, and C:\Users\Dell\.claude\CLAUDE.md. Until those are changed they
contradict the rule written into this repository's CLAUDE.md.

## 2026-09-10 [record] In-repo project record created

evidence: .record/STATE.md and .record/LOG.md created in this repository on
2026-09-10. Repository facts read by command at creation: remote https://github.com/MicroLink-Data-Centers/microlink-map.git,
branch main, HEAD 7893d8a, tree clean. CLAUDE.md created, carrying the
rule that the record of record is .record/STATE.md and .record/LOG.md in this
repository and that the Drive path is a mirror only. Staged by named path only
(.record/STATE.md, .record/LOG.md, CLAUDE.md), never a bare git add; committed
with message "record: add in-repo project record and CLAUDE.md rule"; push
target https://github.com/MicroLink-Data-Centers/microlink-map.git.

evidence: Drive mirror SKIPPED. Test-Path on
"G:\My Drive\MicroLink\04 Operations\06 Project Record" returned False and
Get-PSDrive listed only C and Temp, so the mount is down. The skip did not stop
the session and did not block this write, which is the whole point of the
change made on 2026-09-10.

evidence: session-wide, read by command. C:\Users\Dell\Code holds 93
directories, 63 of them git repositories, 57 with a remote and 6 without, 6
with a dirty tree. Before this session 3 repositories carried CLAUDE.md
(microlink-funding-crm, microlink-hq, microlink-loom, each holding an
uncommitted Drive-only record block appended at 08:23 on 2026-09-10) and 0
carried .record/. .record is excluded by a ".*" rule in .gitignore line 2 in
microlink-investor-v3 and microlink-investor-v3-5; in those two repositories
the record was staged with git add -f, which tracks the files from then on.

evidence: four Desktop handoff files were corrected in place in the same
session, replacing the older try-each-drive-letter fallback list with the new
rule: "Come code with us.. ;).md" lines 123 and 289-294, "Give me a G drive for
coding.md" lines 184-195, "My daily streatch.md" lines 29-36, and "Daily Run
Instructions.md" lines 207-211.
