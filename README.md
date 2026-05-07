# test-plugin-and-marketplace-json

Public test repo containing multiple Claude Code plugins and marketplace metadata.

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
    └── second-plugin/
        ├── .claude-plugin/
        │   └── plugin.json
        ├── README.md
        └── skills/
            └── second-demo/
                └── SKILL.md
```

The root marketplace manifest lists each plugin with `source` set to its directory under `./plugins`. The root plugin manifest is included so this repo can also exercise direct plugin metadata discovery.
