# Trading-Zentrale Dirty Worktree Review

Generated: 2026-05-09 20:09:51
Path: D:\TZ\TRADING-ZENTRALE

- branch: main
- ahead_behind: 0 0
- github_synced: true
- worktree_clean: false

## status -sb
## main...origin/main
 M .gitignore
 M README.md
 M REPORT.md
 M STATUS/error_sources_and_fix_suggestions.md
 M STATUS/full_system_validation_report.json
 M STATUS/full_system_validation_report.md
 M STATUS/last_replay_session_summary.md
 M STATUS/latest_handoff.md
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
?? .github/
?? AGENTS.md
?? STATUS/ssd_bot_strategy_ready.md
?? docs/AI_WORKSPACE_RULES.md

## remote -v
origin	https://github.com/kjdkd/Trading-Zentrale.git (fetch)
origin	https://github.com/kjdkd/Trading-Zentrale.git (push)

## diff --stat
 .gitignore                                  |   1 +
 README.md                                   |  66 +++++++++---
 REPORT.md                                   |  85 +++++++++++++++
 STATUS/error_sources_and_fix_suggestions.md |  17 ++-
 STATUS/full_system_validation_report.json   |  51 ++++++---
 STATUS/full_system_validation_report.md     |  20 +++-
 STATUS/last_replay_session_summary.md       |  14 +--
 STATUS/latest_handoff.md                    | 106 ++++++++++++++++++
 STATUS/project_migration_report.json        |  10 +-
 STATUS/project_migration_report.md          |   6 +-
 STATUS/project_state.md                     |  14 ++-
 docs/CHATGPT_RULES.md                       | 162 +++++++++++++++-------------
 docs/COPILOT_RULES.md                       |  76 +++++++------
 docs/PROJECT_RULES.md                       |  15 +++
 docs/SETUP_WINDOWS.md                       |  11 +-
 docs/WORKFLOW.md                            |  98 +++++++++--------
 scripts/full_system_validation.py           |  11 +-
 scripts/verify_project_migration.py         |  16 +--
 18 files changed, 574 insertions(+), 205 deletions(-)

## diff --name-status
M	.gitignore
M	README.md
M	REPORT.md
M	STATUS/error_sources_and_fix_suggestions.md
M	STATUS/full_system_validation_report.json
M	STATUS/full_system_validation_report.md
M	STATUS/last_replay_session_summary.md
M	STATUS/latest_handoff.md
M	STATUS/project_migration_report.json
M	STATUS/project_migration_report.md
M	STATUS/project_state.md
M	docs/CHATGPT_RULES.md
M	docs/COPILOT_RULES.md
M	docs/PROJECT_RULES.md
M	docs/SETUP_WINDOWS.md
M	docs/WORKFLOW.md
M	scripts/full_system_validation.py
M	scripts/verify_project_migration.py

## untracked
.github/agents/builder.agent.md
.github/agents/thinker.agent.md
.github/copilot-instructions.md
AGENTS.md
STATUS/ssd_bot_strategy_ready.md
docs/AI_WORKSPACE_RULES.md

## Clustered Changes
| Status | Cluster | File |
|---|---|---|
| M | UNKNOWN_RISK | .gitignore |
| M | DOCS_INFRA | README.md |
| M | UNKNOWN_RISK | REPORT.md |
| M | DOCS_INFRA | STATUS/error_sources_and_fix_suggestions.md |
| M | GENERATED_REPORTS | STATUS/full_system_validation_report.json |
| M | GENERATED_REPORTS | STATUS/full_system_validation_report.md |
| M | DOCS_INFRA | STATUS/last_replay_session_summary.md |
| M | GENERATED_REPORTS | STATUS/latest_handoff.md |
| M | GENERATED_REPORTS | STATUS/project_migration_report.json |
| M | GENERATED_REPORTS | STATUS/project_migration_report.md |
| M | DOCS_INFRA | STATUS/project_state.md |
| M | DOCS_INFRA | docs/CHATGPT_RULES.md |
| M | DOCS_INFRA | docs/COPILOT_RULES.md |
| M | DOCS_INFRA | docs/PROJECT_RULES.md |
| M | DOCS_INFRA | docs/SETUP_WINDOWS.md |
| M | DOCS_INFRA | docs/WORKFLOW.md |
| M | CODE | scripts/full_system_validation.py |
| M | CODE | scripts/verify_project_migration.py |
| ?? | DOCS_INFRA | .github/ |
| ?? | DOCS_INFRA | AGENTS.md |
| ?? | DOCS_INFRA | STATUS/ssd_bot_strategy_ready.md |
| ?? | DOCS_INFRA | docs/AI_WORKSPACE_RULES.md |
