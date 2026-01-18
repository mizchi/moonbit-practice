# MoonBit Practice Plugin

A Claude Code plugin providing best practices for MoonBit code generation.

## Installation

```bash
claude plugin marketplace add mizchi/moonbit-practice
claude plugin install moonbit-practice@moonbit-plugins
```

## Usage

```bash
/moonbit-practice
```

## Included References

- **ide.md**: Code navigation with `moon ide`
- **ffi.md**: MoonBit FFI reference
- **refactor.md**: Refactoring patterns
- **configuration.md**: moon.mod.json / moon.pkg configuration
- **agents.md**: Project layout and development workflow

## Directory Structure

```
moonbit-practice/
├── .claude-plugin/
│   └── marketplace.json
├── skills/
│   └── moonbit-practice/
│       ├── SKILL.md
│       ├── reference/
│       │   ├── agents.md
│       │   ├── configuration.md
│       │   ├── ffi.md
│       │   ├── ide.md
│       │   └── refactor.md
│       └── assets/
│           └── ci.yaml
└── README.md
```

## License

MIT
