# Changelog

## v5 (2025-12-14)
- Renamed `stable/` worktree to `kernel/` across all skills
- Renamed `inbox-workflow.xml` to `mail-workflow.xml` (v3)
- Mail now uses `META/mail/{inbox,read,trash}/` structure

## v4 (2025-12-14)
- **Breaking**: `name` is now an attribute on root tag, not a child element
  - Old: `<skill v="1"><name>foo</name>...`
  - New: `<skill name="foo" v="1">...`
- Added `<portability>` section to self.xml — no hardcoded paths
- Added `inbox-workflow` skill (now mail-workflow)
- Removed `objective-cycle` skill (superseded by ticket-workflow)
- Removed `http-api-usage` skill (belongs in http_api library)
- Simplified `ll.xml` manifest format
- All skills bumped to v2

## v3 (2025-12-13)
- First formal release with release workflow
- Added `harness.xml` app template (forkable context assembler)
- Added `vnd` script with env var support (`LLXML_RUST_LIBS`, `LLXML_WEB_LIBS`)
- Made all paths portable (no hardcoded `/home/...` paths)
- Moved `harness.xml` to `spec/` directory

## v2 (2025-12-13)
- Skipped (internal iteration)

## v1 (2025-12-11)
- Initial release
- `self.xml` spec (was LLXML.md, then llxml.xml)
- Core skills: llxml-writing, llxml-auditing
- Project structure with worktrees, META/, ctx/
