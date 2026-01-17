# Claude Code Expertise Collection

A personal collection of specialized skills for [Claude Code](https://claude.ai/claude-code), providing deep domain expertise for full-stack web development and decentralized protocols.

Created with [taches-cc-resources](https://github.com/glittercowboy/taches-cc-resources).

## Skills

| Skill | Description | Size |
|-------|-------------|------|
| [nextjs-16](./nextjs-16/) | Next.js 16 with Cache Components, Server/Client Components, and modern patterns | 192 KB |
| [nostr](./nostr/) | Nostr protocol for decentralized real-time data exchange | 200 KB |
| [convex-nextjs](./convex-nextjs/) | Convex backend with Next.js frontend integration | 24 KB |
| [evolu-nextjs](./evolu-nextjs/) | Evolu local-first database with offline-first operation | 44 KB |

## Structure

Each skill follows a consistent pattern:

```
skill-name/
├── SKILL.md           # Entry point with principles, routing, and success criteria
├── references/        # Deep technical documentation and API guides
├── workflows/         # Step-by-step task guides with verification
└── templates/         # (optional) Copy-paste starter code
```

### Components

- **SKILL.md** - Main entry point with essential concepts, intake routing, and verification loops
- **references/** - Detailed API docs, code patterns, best practices, and implementation guides
- **workflows/** - Actionable step-by-step guides with code examples and checkpoints
- **templates/** - Production-ready TypeScript implementations (Nostr skill only)

## Skills Overview

### Next.js 16

Build modern Next.js 16 applications with the latest features:

- Cache Components with `'use cache'` directive
- `proxy.ts` replacing middleware (Node.js runtime)
- Server/Client Component boundaries
- Data Access Layer (DAL) for authentication
- Turbopack as default bundler
- Deployment to Vercel/Docker/self-hosted

### Nostr Protocol

Build decentralized applications using Nostr:

- Event-based data model (kinds, relays, subscriptions)
- nostr-tools library for JavaScript/TypeScript
- NIP-44 encryption for secure communication
- Relay pool management and connection handling
- Custom event kind design patterns

### Convex + Next.js

Full-stack type-safe development:

- New function syntax with validators
- Indexes over filters (never use `.filter()`)
- `preloadQuery` + `usePreloadedQuery` for SSR with real-time reactivity
- Convex Auth integration via `proxy.ts`
- Strict typing with `Id<"tableName">`

### Evolu + Next.js

Local-first applications with privacy:

- SQLite-based offline-first operation
- End-to-end encryption with 12-word mnemonic recovery
- Branded types for compile-time safety
- Real-time reactive queries
- Cross-device sync via WebSocket

## Installation

Clone this repository into your Claude Code skills directory:

```bash
git clone https://github.com/YOUR_USERNAME/expertise.git ~/.claude/skills/expertise
```

## Usage

Once installed, Claude Code will automatically load these skills when working on relevant projects. Each skill provides:

1. **Guided workflows** - Step-by-step task completion
2. **Reference documentation** - Deep technical knowledge
3. **Best practices** - Patterns and anti-patterns
4. **Verification loops** - Quality checkpoints

## License

Personal use. Feel free to fork and customize for your own workflows.
