# IKE BOM

Bill of Materials centralizing dependency versions for all IKE projects.

## Build Standards

Files in `.claude/standards/` are build artifacts unpacked from `ike-build-standards`. DO NOT edit or commit them. See the workspace root CLAUDE.md for details.

## Key Facts

- GroupId: `dev.ikm.ike`
- Packaging: pom (BOM only, no code)
- Declares version properties for all IKE modules: komet, tinkar-core, rocks-kb
- Declares version properties for all third-party dependencies
- Consumed via `<scope>import</scope>` in other project POMs
