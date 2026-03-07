You are working from a web-UI local clone/snapshot of my GitHub repository, but the authoritative source of truth is the live remote repo: `parsabp01/vista-ranch-swmmV2`. For this audit, you must first inspect and reconcile against the current state of my actual GitHub repository contents/history, and not rely solely on the stale local cloned worktree if there is any discrepancy.

# Repo Cleanup Audit

## Remote reconciliation status
- Unable to verify live GitHub remote contents in this environment (git ls-remote to github.com failed with HTTP 403), so findings are from local snapshot + git history.

## Current authoritative outputs
- `outputs/v2_branchlogic_basins_1_to_5/build_summary.json`
- `outputs/v2_branchlogic_basins_1_to_5/pipeline_state.json`
- `outputs/v2_branchlogic_basins_1_to_5/blocker_summary_clean.md`
- `outputs/v2_branchlogic_basins_1_to_5/residual_blockers_after_overrides.csv`
- `outputs/v2_branchlogic_basins_1_to_5/residual_blockers_traceability.csv`
- `outputs/v2_branchlogic_basins_1_to_5/branch_logic_graph_qaqc.md`
- `outputs/v2_branchlogic_basins_1_to_5/source_lookup_overrides_applied.csv`
- `outputs/v2_branchlogic_basins_1_to_5/manual_ac_overrides_applied.csv`

## Stale / duplicated / superseded / inconsistent outputs found
- `outputs/v2_branchlogic_basins_1_to_5/basin_layout_summary.md` contains repeated lines (likely appended in prior runs).
- `outputs/v2_branchlogic_basins_1_to_5/branch_logic_true_absence_review.csv` appears superseded by post-override artifacts; retain for provenance only.
- `outputs/v2_branchlogic_basins_1_to_5/lookup_bug_resolution_report.md` appears superseded by post-override artifacts; retain for provenance only.
- `outputs/v2_branchlogic_basins_1_to_5/missing_ac_manual_input_template.csv` appears superseded by post-override artifacts; retain for provenance only.
- `outputs/v2_branchlogic_basins_1_to_5/missing_ac_exception_list.csv` appears superseded by post-override artifacts; retain for provenance only.

## Requested checks
- `outputs/v2_branchlogic_basins_1_to_5/blocker_summary_clean.md`: duplicated stale sections present now: **no** (rewritten cleanly).
- `outputs/v2_branchlogic_basins_1_to_5/build_summary.json`: single-state valid JSON: **yes**.
- `outputs/v2_branchlogic_basins_1_to_5/pipeline_state.json`: single-state valid JSON: **yes**.

## Recommended actions
- Keep authoritative files above as live status outputs.
- Treat superseded/stale files as historical context; do not use them for live counts.
- If remote access is restored, rerun this audit after fetching `origin/main` and refreshing ANSWERS files.
