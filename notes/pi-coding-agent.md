# Pi coding agent

Pi is a minimal, opinionated terminal coding harness for AI-assisted development. It emphasizes predictable behavior, exact control over context, and a small surface area over feature bloat.

Key design ideas include a unified multi-provider LLM layer, an agent core that handles tool execution and event streaming, a lightweight TUI, and the CLI layer that adds session management, custom tools, themes, and project context files. The project also supports alternative UIs on top of the same core.

The author describes the philosophy as favoring explicitness and post-processable session data, with the broader Pi stack split into pi-ai, pi-agent-core, pi-tui, and pi-coding-agent. Related context files are loaded from the current project, parent directories, and a global Pi location. See [[raw/2026-04-18T14-14-06.510Z--c5885adb-2c1c-4780-97f8-a7aee9e755ba.txt]] for the captured page, plus the earlier Pi captures at [[raw/2026-04-18T13-56-43.773Z--402bfb4f-a729-4b94-ae7e-7ebe58e68774.txt]] and [[raw/2026-04-18T13-56-03.873Z--19f7abe1-74e1-4ff5-9c72-4bfda74bceb0.txt]].

## References
- [[raw/2026-04-18T14-14-06.510Z--c5885adb-2c1c-4780-97f8-a7aee9e755ba.txt]]
- [[raw/2026-04-18T13-56-43.773Z--402bfb4f-a729-4b94-ae7e-7ebe58e68774.txt]]
- [[raw/2026-04-18T13-56-03.873Z--19f7abe1-74e1-4ff5-9c72-4bfda74bceb0.txt]]