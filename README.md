# musterctl skill

The generated Agent Skill that teaches coding agents when and how to discover
the installed `musterctl` control plane. The live CLI remains authoritative.

```bash
npx -y skills@1.5.23 add jdegregorio/musterctl-skill --skill musterctl
```

`skills/musterctl/SKILL.md` is generated from `musterctl` v0.1.1 metadata. Run
`./scripts/check` to verify it has not drifted.
