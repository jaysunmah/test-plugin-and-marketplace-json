# test-plugin-and-marketplace-json

Public test repo containing one Claude Code plugin and marketplace metadata.

## Layout

```text
.
├── .claude-plugin/
│   ├── marketplace.json
│   └── plugin.json
└── plugins/
    └── example-plugin/
        ├── .claude-plugin/
        │   └── plugin.json
        ├── README.md
        └── skills/
            └── github-demo/
                └── SKILL.md
```

The root marketplace manifest lists `example-plugin` with `source` set to `./plugins/example-plugin`. The root plugin manifest is included so this repo can also exercise direct plugin metadata discovery.
