# Joe's Corner Skills

Agent skills for [Joe's Corner](https://joescorner.ai), a news and content aggregator built for the AI age. These skills let AI agents query live feeds and posts from the Joe's Corner public API.

Built on the [Agent Skills](https://agentskills.io) open standard.


## Available Skills

- [joescorner](skills/joescorner/SKILL.md) - Query feeds, fetch posts, and discover content. No authentication required.


## Prerequisites

- [uv](https://docs.astral.sh/uv/getting-started/installation/) for running the bundled scripts


## Installation

### Claude Code

In any Claude Code session, run:

```
/plugin marketplace add joescorner/joescorner-skills
/plugin install joescorner-skills@joescorner-skills
```

### OpenClaw

Available on [ClawHub](https://clawhub.ai/joescorner/joescorner). Install with:

```
openclaw skills install joescorner
```

### Other agents

Copy the `skills/joescorner/` directory into your agent's skills directory:

```bash
git clone https://github.com/joescorner/joescorner-skills.git
cp -r joescorner-skills/skills/joescorner ~/.agents/skills/
```


## Links

- [Joe's Corner](https://joescorner.ai)
- [Python SDK](https://github.com/joescorner/joescorner-python)
- [OpenAPI Spec](https://github.com/joescorner/joescorner-openapi)

## License

MIT
