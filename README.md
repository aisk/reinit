# Ｒｅ：Ｉｎｉｔ ／ 再初期化

<sub>zài chūqīhuà・ㄗㄞˋ ㄔㄨ ㄑㄧ ㄏㄨㄚˋ・zoi³ co¹ kei⁴ faa³・さいしょきか・재초기화・tái khởi tạo</sub>

An agent skill that turns recent coding-agent session history into durable repository guidance. It reviews what the agent repeatedly had to rediscover and what the user explicitly corrected, then writes only the facts that pass a strict retention test into `AGENTS.md` / `CLAUDE.md`.

![](https://repository-images.githubusercontent.com/1299260577/40449da3-5452-439c-8801-8839127831a8)

<sub>*Image by Homutan, source: https://www.pixiv.net/artworks/99426317*</sub>

## Invoke

Invoke it manually: `/reinit` in Claude Code and Crush, `$reinit` in Codex, `/skill:reinit` in pi.

## Install

The quick way, for any supported agent:

```sh
npx skills add aisk/reinit
```

Or clone it into your agent's skills directory:

| Agent | Command |
| --- | --- |
| Claude Code | `git clone https://github.com/aisk/reinit ~/.claude/skills/reinit` |
| Codex CLI | `git clone https://github.com/aisk/reinit ~/.codex/skills/reinit` |
| opencode | `git clone https://github.com/aisk/reinit ~/.config/opencode/skills/reinit` |
| Crush | `git clone https://github.com/aisk/reinit ~/.config/crush/skills/reinit` |
| pi | `git clone https://github.com/aisk/reinit ~/.pi/agent/skills/reinit` |
