# The Emperor of the United States

A grounded, warm, gently comic text adventure in contemporary San Francisco, played turn by turn in conversation with Claude.

You're the many-times-great-niece or -nephew of Joshua Abraham Norton (Norton I, Emperor of the United States and Protector of Mexico). A letter on heavy paper brings you to an estate attorney's third-floor walkup, where a trunk is waiting: a plumed beaver hat, a dress saber, a uniform mended more than once, and a portfolio of decrees, seven of them still marked open. You have one week, January 2 through 8, to decide what, if anything, that inheritance means.

The Empire was never real, but the city's agreement to treat it as real was, and it made San Francisco kinder. Authority in this game exists only as a gift other people choose to give, scene by scene.

## How to play

Once the plugin is installed, ask Claude:

> Let's play The Emperor of the United States.

The game only starts when you ask for it by name (or as "the Emperor Norton game"), so it won't take over conversations about the historical Emperor Norton or San Francisco.

Each turn, Claude narrates a few sentences and offers three choices (A, B, and C), plus D) Something else, where you can type anything you'd like to try. Along the way you'll:

- Spend your mornings, afternoons, and evenings carefully, because there are always more open decrees than days
- Keep an eye on your **Funds** and your **Regard**, the city's freely given warmth
- Decide what to wear from the trunk each day, from full regalia to no Empire at all
- Settle 150-year-old debts, visit the Emperor's rotation of congregations, and find out who in the city will play along
- Arrive at the graveside observance in Colma on the anniversary of Norton's death, with whoever you've earned beside you

The game is a single sitting, though a longer one. If you need to stop partway, ask for a save-state block at any time and paste it into a new chat to pick up where you left off.

## Install in Claude Code

Add this repository as a marketplace, then install the plugin:

```bash
claude plugin marketplace add srosebattles/emperor-of-the-united-states-game
claude plugin install emperor-of-the-united-states@emperor-of-the-united-states-game
```

Or do both from inside a Claude Code session:

```text
/plugin install emperor-of-the-united-states --marketplace srosebattles/emperor-of-the-united-states-game
```

## What's inside

This plugin contains a single skill, `emperor-of-the-united-states`, which is plain Markdown instructions for Claude. It has no scripts, hooks, MCP servers, or other executable code. It doesn't fetch anything, collect any data, or send anything anywhere. During play, the skill asks Claude not to use other tools, so the game stays in plain text.

```text
.claude-plugin/
  plugin.json        Plugin manifest
  marketplace.json   Lets Claude Code install the plugin from this repository
skills/
  emperor-of-the-united-states/
    SKILL.md         The game master instructions
LICENSE              CC BY 4.0
```

The assets folder holds the plugin's icon (the Emperor's plumed hat) and its editable SVG source.

## License

The Emperor of the United States by Sarah Rose Battles is licensed under the [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/) (CC BY 4.0). The full text is in [LICENSE](LICENSE).

You're free to share and adapt it, including commercially, as long as you give credit and say if you made changes. If you publish a remix, please include a link back to [llmtextgames.xyz](https://llmtextgames.xyz) in your credit. For example:

> Based on *The Emperor of the United States* by Sarah Rose Battles ([llmtextgames.xyz](https://llmtextgames.xyz)), licensed under CC BY 4.0.
