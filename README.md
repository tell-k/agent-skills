# agent-skills

A Claude Code plugin marketplace by tell-k.

```
/plugin marketplace add tell-k/agent-skills
/plugin install digesta@tell-k
```

The marketplace name is `tell-k` (`agent-skills` is a reserved name in Claude Code and cannot be used).

The skills are standard Agent Skills, so they can also be installed into other agents (Codex, Cursor, …) with the [skills CLI](https://github.com/vercel-labs/skills):

```
npx skills add tell-k/digesta
```

| Plugin | Description |
|---|---|
| [digesta](https://github.com/tell-k/digesta) | Turns a meeting or study-session recording and its transcript into minutes, a graphic recording, and a digest video (built for Japanese meetings) |
