# Ablation Lab plugins

A Claude Code plugin marketplace that lists every plugin from Ablation Lab. This repo holds only the catalog (`.claude-plugin/marketplace.json`); each plugin is installed from its own repository.

## Install

In Claude Code, add the marketplace once:

```
/plugin marketplace add Ablation-Lab/plugins
```

Then install a plugin by its name, for example:

```
/plugin install tangent-jar@ablation-lab
```

From your shell, the same steps are `claude plugin marketplace add Ablation-Lab/plugins` and `claude plugin install tangent-jar@ablation-lab`.

If you've already installed a plugin from its own repository's marketplace, you don't need to install it again from here.

## Plugins

- [Lore Lookup](https://github.com/Ablation-Lab/claude-lore) (`lore-lookup`): answers questions about Claude, Claude Code and the Claude apps from Anthropic's online docs, help pages and release notes, with links to the pages it used.
- [Cutproof](https://github.com/Ablation-Lab/video-review-tool) (`cutproof`): proofreads a rendered video or Remotion project without watching it. Windows only, needs ffmpeg.
- [Stowdeck](https://github.com/Ablation-Lab/stowdeck) (`stowdeck`): lets Claude list your Claude Code sessions and snapshots, save a snapshot and open the Stowdeck app. Windows only, needs the Stowdeck app.
- [Seaready](https://github.com/Ablation-Lab/seaready) (`seaready`): checks a plugin repo before you submit it to Anthropic's plugin directory, and drafts your answers for the submission form.
- [Tangent Jar](https://github.com/Ablation-Lab/tangent-jar) (`tangent-jar`): parks side questions in a list in your project during a focus session you start, and nudges you back to your main task.
- [Bench Diary](https://github.com/Ablation-Lab/bench-diary) (`bench-diary`): logs the research notes, decisions, anecdotes and experiment ideas you mention into the right doc in your project.
- [Langparity](https://github.com/Ablation-Lab/langparity) (`langparity`): checks a translation against its source and suggests a corrected translation for each problem it confirms.
- [Council Dial](https://github.com/Ablation-Lab/council-dial) (`council-dial`): runs a review council of Claude subagents the way you choose and logs each run, so you can compare council types.

Each plugin's README has its requirements and explains what it runs, reads and sends.

---

Ablation Lab is independent and not affiliated with Anthropic.

Research by George, Ablation Lab.
