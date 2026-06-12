# orbit Recovery Records

## project_init / project_name_candidates

- time: `2026-06-08T18:18:57.495060+00:00`
- run_id: `<NEXUS_RUN_ID>`
- signature: `project_init/project_name_candidates/project_name_model_failed/recommended_not_in_real_five_letter_project_word_list`
- reason: project_name_model_failed
- summary: Recover project-name initialization failures by registering a debug handoff, verifying the model output and explicit-name branch, patching only the original run checkpoint when safe, recording diagnosis/edit/test worklog, and re-binding the same run.
## github / github_public

- time: `2026-06-08T18:19:04.401763+00:00`
- run_id: `<NEXUS_RUN_ID>`
- signature: `github/github_public/gh_auth_required/invalid_token_then_github_api_eof`
- reason: gh_auth_required
- summary: Recover GitHub public sync from invalid gh token and GitHub API EOF by diagnosing auth state, using official gh web/device login, resuming stored EOF continuation when present, and retrying the original public sync under Nexus public staging and secret-scan controls.
