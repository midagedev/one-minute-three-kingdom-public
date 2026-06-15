# Public Visual Language

This public showcase uses a terminal-forward visual style: dark surfaces, quiet borders, and small color accents that behave like TUI tokens.

## Color Tokens

| Token | Use | Example |
| --- | --- | --- |
| `[gold]...[/gold]` | rare reward, title object, important state | `[gold]인장[/gold]` |
| `[danger]...[/danger]` | threat, rumor, failure pressure | `[danger]소문[/danger]` |
| `[command]...[/command]` | typed commands and command labels | `[command]report[/command]` |
| `[success]...[/success]` | resolved action or stable recovery | `[success]합의[/success]` |
| `[muted]...[/muted]` | secondary metadata, timestamps, low-priority labels | `[muted]지난 회귀[/muted]` |

## Emphasis Rule

Color only the meaningful token: a label, command, named object, short status, or one important word.

Do not color a whole sentence just because the sentence is important. If everything is highlighted, the TUI loses scanability and the player cannot tell what changed.

## Examples

Good:

```text
관아 보고서: [danger]소문[/danger]이 서문 창고까지 번졌다.
다음 명령: [command]orders[/command]
장부에 [gold]인장[/gold] 후보가 남았다.
```

Avoid:

```text
[danger]관아 보고서: 소문이 서문 창고까지 번졌다.[/danger]
[command]다음 명령을 입력하고 오늘의 선택을 확정한다.[/command]
```

## SVG Asset Notes

- SVG assets must be self-contained for GitHub README rendering.
- Do not depend on external fonts, external images, scripts, or private URLs.
- Public images must not include real private beta network hosts, IP addresses, operator accounts, internal paths, or private repository URLs.
- Use system font stacks and plain SVG text. Keep labels short enough to remain readable at README width.
