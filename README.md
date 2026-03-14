# Skill CLI Protocol — Documentation

The official docs for [SCP (Skill CLI Protocol)](https://skillcliprotocol.io).

SCP is an open convention for giving AI agents capabilities using plain files and standard CLI tools. No SDKs, no servers, no protocol negotiation.

## Structure

```
docs/
  index.mdx              # Landing page
  quickstart.mdx          # 2-minute quickstart
  learn/
    what-is-a-skill.mdx   # Core concept
    how-skills-work.mdx    # Agent loop, discovery, execution
    why-not-mcp.mdx        # SCP vs MCP comparison
  develop/
    create-a-skill.mdx     # Build guide
    skill-manifest.mdx     # skill.json reference
    testing.mdx             # Testing skills
  registry/
    overview.mdx           # Finding and installing skills
    publishing.mdx         # Publishing to the registry
```

## Local development

```bash
npm i -g mintlify
mintlify dev
```

## Contributing

See [CONTRIBUTING.md](./CONTRIBUTING.md).
