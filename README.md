# atproto-pro

[![skills.sh](https://skills.sh/b/jaredlemler/atproto-pro)](https://skills.sh/jaredlemler/atproto-pro)

An agent skill for the AT Protocol — deep protocol expertise for building on the open social web.

Covers identity (DIDs, handles), repositories, Lexicons, XRPC, OAuth (PKCE + DPoP + PAR), firehose/sync, data model, and all official specs. Provides production-grade guidance for TypeScript (`@atproto/api`, `@atproto/oauth`) and Go (`indigo`) SDKs.

## Install

```bash
# Install to all detected agents
npx skills add jaredlemler/atproto-pro

# Install to a specific agent
npx skills add jaredlemler/atproto-pro -a opencode

# Install globally
npx skills add jaredlemler/atproto-pro -g
```

## What's Included

A single skill: **atproto-pro**

When activated, the agent gains deep knowledge of:

- **Identity**: DID resolution (`did:plc`, `did:web`), handle verification, bidirectional identity checks
- **OAuth**: Full atproto OAuth 2.1 profile with PKCE, DPoP, and PAR — confidential and public client flows
- **Data Model**: Records, collections, CIDs, blobs, DAG-CBOR encoding, `$type` dispatch
- **Lexicons**: Schema authoring, evolution rules, NSID conventions, validation semantics
- **XRPC**: HTTP API patterns, service proxying, inter-service auth, error handling
- **Firehose**: `subscribeRepos` event stream, cursor-based resumption, record-level sync
- **Repositories**: MST structure, CAR import/export, commit signing, at:// URI addressing

## What This Skill Does Not Cover

General-purpose coding, UI development, databases, or infrastructure outside the AT Protocol. When a task is purely about atproto, this agent should be the one responding.

## License

MIT