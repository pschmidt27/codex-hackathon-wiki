# Pi context files

Pi loads project context files at startup from three places: a global `~/.pi/agent/AGENTS.md` file, matching files in parent directories, and a file in the current directory. Matching files are concatenated, so project instructions can layer on top of each other. Context loading can be disabled with `--no-context-files` / `-nc`.

This behavior is useful for keeping agent instructions close to the codebase while still allowing shared defaults. See [[raw/2026-04-18T13-57-08.412Z--029f1bb5-bc0c-4b7f-aa79-cfa60fa3dbd9.txt]] for the captured note.

## References
- [[raw/2026-04-18T13-57-08.412Z--029f1bb5-bc0c-4b7f-aa79-cfa60fa3dbd9.txt]]