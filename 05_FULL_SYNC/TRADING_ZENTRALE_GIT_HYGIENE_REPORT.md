# TRADING_ZENTRALE Git Hygiene Report

Generated: 2026-05-09 21:00:44
Path: D:\TZ\TRADING-ZENTRALE

## Core State
- branch: main
- ahead_behind: 0 0
- TRADING_ZENTRALE_FETCH_OK=False
- TRADING_ZENTRALE_FSCK_OK=True

## status -sb
## main...origin/main
 M .gitignore
 M README.md
 M REPORT.md
 M STATUS/error_sources_and_fix_suggestions.md
 M STATUS/full_system_validation_report.json
 M STATUS/full_system_validation_report.md
 M STATUS/last_replay_session_summary.md
 M STATUS/project_migration_report.json
 M STATUS/project_migration_report.md
 M STATUS/project_state.md
 M docs/CHATGPT_RULES.md
 M docs/COPILOT_RULES.md
 M docs/PROJECT_RULES.md
 M docs/SETUP_WINDOWS.md
 M docs/WORKFLOW.md
 M scripts/full_system_validation.py
 M scripts/verify_project_migration.py

## remote -v
origin	https://github.com/kjdkd/Trading-Zentrale.git (fetch)
origin	https://github.com/kjdkd/Trading-Zentrale.git (push)

## fetch --prune output
fatal: renaming pack to '.git/objects/pack/pack-d941b2589625f9a3e1bda68f66fa0732dac6aefb.pack' failed: File exists
error: failed to perform geometric repack
error: task 'geometric-repack' failed

## fsck --full output
dangling commit 6363a45b90a697ffffa33881b29da6f837777068
dangling commit a00c2dfd12519c112a1936379a264eca49943c79
dangling tree 9acfc255b60f92703f5cc7a9e50b8bc1b30dda57

## Pack Directory Inventory
| Name | Length | LastWriteTime |
|---|---:|---|
| multi-pack-index | 9336 | 2026-05-06 16:31:14 |
| pack-ccf9524633cdf37fc4114e33310127a77c5db5e7.idx | 2164 | 2026-05-06 16:31:12 |
| pack-ccf9524633cdf37fc4114e33310127a77c5db5e7.pack | 26591476 | 2026-05-06 16:31:12 |
| pack-ccf9524633cdf37fc4114e33310127a77c5db5e7.rev | 208 | 2026-05-06 16:31:12 |
| pack-ec3ac09a8893744e691e3d188315c8cd43811af8.idx | 8100 | 2026-05-06 15:11:06 |
| pack-ec3ac09a8893744e691e3d188315c8cd43811af8.pack | 228705 | 2026-05-06 15:23:02 |
| pack-ec3ac09a8893744e691e3d188315c8cd43811af8.rev | 1056 | 2026-05-06 15:11:06 |
| pack-dcadc1d2cb55733cb3d54f64fcc23a35a9f0d356.pack | 527951 | 2026-05-08 22:05:18 |
| pack-dcadc1d2cb55733cb3d54f64fcc23a35a9f0d356.rev | 1708 | 2026-05-08 22:05:18 |
| pack-dcadc1d2cb55733cb3d54f64fcc23a35a9f0d356.idx | 12664 | 2026-05-08 22:05:18 |
| pack-6fa82659f7e2b9c1f6a659a89eb21617dcb43dd8.rev | 2828 | 2026-05-08 22:05:44 |
| pack-6fa82659f7e2b9c1f6a659a89eb21617dcb43dd8.idx | 20504 | 2026-05-08 22:05:44 |
| pack-d941b2589625f9a3e1bda68f66fa0732dac6aefb.rev | 104 | 2026-05-08 22:05:44 |
| pack-d941b2589625f9a3e1bda68f66fa0732dac6aefb.idx | 1436 | 2026-05-08 22:05:44 |
| pack-6fa82659f7e2b9c1f6a659a89eb21617dcb43dd8.pack | 27292853 | 2026-05-08 22:05:44 |
| pack-d941b2589625f9a3e1bda68f66fa0732dac6aefb.pack | 8478 | 2026-05-08 22:05:44 |
| pack-d941b2589625f9a3e1bda68f66fa0732dac6aefb.mtimes | 104 | 2026-05-08 22:05:44 |
| pack-a0e309d8704ece07892e858fee918b31f03470fb.pack | 27295589 | 2026-05-08 23:02:40 |
| pack-a0e309d8704ece07892e858fee918b31f03470fb.rev | 2860 | 2026-05-08 23:02:40 |
| pack-a0e309d8704ece07892e858fee918b31f03470fb.idx | 20728 | 2026-05-08 23:02:40 |
| pack-51c21803c9bec291abcfc067bcea0d228fe3e7d1.pack | 27302714 | 2026-05-08 23:19:38 |
| pack-51c21803c9bec291abcfc067bcea0d228fe3e7d1.rev | 2924 | 2026-05-08 23:19:38 |
| pack-51c21803c9bec291abcfc067bcea0d228fe3e7d1.idx | 21176 | 2026-05-08 23:19:38 |
| pack-5307d767a757c48308fe75d8082c07cf72a1607a.pack | 27312597 | 2026-05-09 00:16:06 |
| pack-5307d767a757c48308fe75d8082c07cf72a1607a.rev | 2992 | 2026-05-09 00:16:06 |
| pack-5307d767a757c48308fe75d8082c07cf72a1607a.idx | 21652 | 2026-05-09 00:16:06 |
| pack-ae63c07bf5b80f021be708ae2298aeecf2ae170d.pack | 27326185 | 2026-05-09 00:45:48 |
| pack-ae63c07bf5b80f021be708ae2298aeecf2ae170d.rev | 3036 | 2026-05-09 00:45:48 |
| pack-ae63c07bf5b80f021be708ae2298aeecf2ae170d.idx | 21960 | 2026-05-09 00:45:48 |
| pack-66c0cc0eb64b3d916c88c944ac9ec15f650b5d2a.rev | 3060 | 2026-05-09 17:49:44 |
| pack-66c0cc0eb64b3d916c88c944ac9ec15f650b5d2a.idx | 22128 | 2026-05-09 17:49:44 |
| pack-66c0cc0eb64b3d916c88c944ac9ec15f650b5d2a.pack | 27332819 | 2026-05-09 17:49:44 |
