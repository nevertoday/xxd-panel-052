<p align="center"><img src="./assets/banner.svg" alt="XXD Panel 052 project banner" width="1200"></p>

<div align="center">

# 🦁 XXD Panel 052

### Let a handcrafted miniature world float along one landscape line

[![Codex Skill](https://img.shields.io/badge/Codex-Skill-000000?style=flat-square)](./SKILL.md)
[![Modes](https://img.shields.io/badge/Modes-4-EF805E?style=flat-square)](#)
[![Output](https://img.shields.io/badge/Output-PNG-4AA1AE?style=flat-square)](#)

<a href="README.md">简体中文</a> PAPER-CRAFT MINIATURE · HORIZONTAL FLOATING STRIP · HANDMADE MATERIAL · AIRY COOL BLUE · GENEROUS SPACE

Rebuild the most recognisable source subject and limited supported environment as paper, cardstock, soft-clay, and thin-wood miniatures on one long floating landscape strip. Authentic craft detail, intimate macro light, and pale open space create a premium art-installation presence.

## Why this Skill exists

The style is source-dependent, not a decorative preset. Its operative transformation is:

```text
lock identity, silhouette, pose, direction, and relation → preserve three cues → select one primary subject and limited supported elements → rebuild paper, cardstock, soft-clay, and thin-wood miniatures → place them on one long horizontal floating strip → establish scale depth, overlap, and calm balance → reveal authentic craft through macro light → retain airy cool blue and generous space → add one signature-like short title
```

If an unrelated photograph could replace the source without materially changing recognition, model construction, support, strip silhouette, material, balance, colour, whitespace, and copy, the result does not belong to this Panel.

## The visual contract

- Preserve at least three source-specific cues across silhouette, proportion, pose, direction, action, structure, colour, material, or relation.
- Build one dominant primary miniature and limited source-supported models, all seated on one long, narrow, lightweight horizontal floating strip.
- Create depth through scale variation, layered overlap, and quieter foreground/background pieces; stay broadly centred without mechanical symmetry or a second focal point.
- Show paper fibres, folds, cut marks, layered thickness, rough rims, and tiny handmade imperfections; reject slick plastic CGI.
- Organise airy cool blues, ivory, pale beige, muted grey-green, and tiny muted-blush accents with soft macro light and generous pale negative space.

Complete aesthetic constraints and rejection rules live in the Skill and production prompts. They preserve the original brief without turning its historical 3:4 canvas into a hidden default. [SKILL.md](SKILL.md) · [production prompt](references/xxd-panel-052-prompt.en.md)

## Samples · From X

> [Xiaoxiaodong (@xiaoxiaodong01)](https://x.com/xiaoxiaodong01/status/2091500926721020375) · 23 August 2026<br>
> GPT2 × paper cut × quiet elegance × aesthetic prompt × VOL.052

<table>
  <tr>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2091500926721020375"><img src="./assets/examples/sample-01.jpg" alt="XXD Panel 052 sample 1"></a></td>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2091500926721020375"><img src="./assets/examples/sample-02.jpg" alt="XXD Panel 052 sample 2"></a></td>
  </tr>
  <tr>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2091500926721020375"><img src="./assets/examples/sample-03.jpg" alt="XXD Panel 052 sample 3"></a></td>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2091500926721020375"><img src="./assets/examples/sample-04.jpg" alt="XXD Panel 052 sample 4"></a></td>
  </tr>
</table>

<p align="center"><a href="https://x.com/xiaoxiaodong01/status/2091500926721020375">View the original post and full prompt →</a></p>

These samples demonstrate the 052 aesthetic motive. Their subjects, composition, palette, copy, and earlier canvas ratio never become generation references or current defaults.

## Four combinable output modes

Choose one or several modes with `1`, `1+3`, `1,2,4`, or `all`; `all` produces seven separate PNGs per source. After mode selection and before generation, the Skill explicitly asks for the whole finished canvas: the original-prompt `3:4`, an explicit source-aspect choice, a common ratio, or custom ratio/exact pixels. Source dimensions are never applied silently.

| Mode | Canvas rule | Result |
| --- | --- | --- |
| `top-bottom` | user-confirmed whole canvas | one complete generation: high-fidelity source above, 052 design below, approximately 50/50 |
| `left-right` | user-confirmed whole canvas | one complete generation: high-fidelity source left, 052 design right, approximately 50/50 |
| `design-only` | user-confirmed whole canvas | 052 design fills the canvas; source remains invisible |
| `wallpaper-pack` | confirmed per device | separate phone, iPad, desktop, and children's-watch PNGs |

Paired modes use the source as a high-fidelity edit/reference input and one complete style prompt to generate the finished composition directly, so photography, design, colour, light, typography, and meaning can cohere. Deterministic composition is fallback-only: after one targeted complete-canvas retry fails, when pixel-identical source preservation is explicitly required, when the active route cannot realise the canvas, or for lossless final pixel calibration.

Wallpapers may be linked or independent. A linked pack approves one iPad anchor, then recomposes every other device from the original plus that same anchor. An independent pack gives each device only the original. Neither crops another device output nor chains derivatives.

## Copy and locale

Automatic copy, exact custom copy, or text-free output is confirmed before generation. Copy follows the intended audience rather than the command language, and exact user wording remains verbatim.

Project-specific copy rule: derive one short title from place, subject identity, theme, or emotional tone; place small, refined, subtly handwritten native type beneath or along the strip, or gently within its space, so it reads like an artist signature rather than a commercial headline.

## Complete-canvas first, raster-only delivery

The image model owns the aesthetics of the entire finished composition; paired layouts also default to one complete-canvas generation. `scripts/compose_panel.py` remains only for condition-based recovery, lossless pixel calibration, and read-only audit. It is not run pre-emptively and does not judge aesthetic success.

Every deliverable is a raster PNG and every invocation creates a fresh task under `~/Desktop/xxd/`. The configured image route exposes sanitised status only—never providers, endpoints, credentials, headers, prompts, responses, or account details. SVG, HTML, Canvas, diagrams, and programmatic drawing are not substitutes for the final artwork.

## Selectable controls and inline parameters

When the host provides genuine interactive controls, the Skill prefers card-style selection: output modes and ordinary output sizes are multi-select, while copy mode and wallpaper relationship are single-select. Size choices include auto-fit, source aspect, 1:1, 3:4, 4:3, 4:5, 5:4, 2:3, 3:2, 9:16, 16:9, 21:9, 5:7, 7:5, and custom ratios or pixels. Without an interactive control, it falls back to a clear multiline numbered menu rather than showing fake checkboxes.

Every setting can also be supplied as an inline variable:

```text
/xxd-panel-052 photo.jpg --mode top-bottom,design-only --size auto,3:4,9:16 --text auto --locale ja-JP
```

Supported parameters include `--mode`, repeatable or comma-separated `--size`, `--text auto|custom|none`, `--locale`, `--copy`, `--wallpaper linked|independent`, `--wallpaper-size`, and `--out`. Complete parameters skip all preflight questions; partial parameters trigger only the missing questions. Different aspect ratios are independently recomposed, and the four-device wallpaper pack remains a separate branch rather than being multiplied by ordinary sizes.

## Image-model priority

GPT Image 2 is the default first choice. It keeps this project's established workflow: high-fidelity source reference, explicit whole-canvas selection before generation, one complete-canvas generation for paired modes, and scripted composition only as a conditional fallback.

Seedance 5.0 Pro, Nano Banana Pro (Gemini Image Pro), Nano Banana 2 (Gemini Image Flash), or another compatible bitmap model may also be used when it is actually available through the current tools or configured routes and can satisfy source fidelity, whole-canvas ratio, target-language text, and linked-wallpaper multi-reference requirements. An alternative changes only the generation route; it must not change modes, canvas, copy, locale, wallpaper relationship, or the complete-canvas-first strategy.

If no suitable route is available, the Skill asks the user to enable an image-generation tool or provide an API key. User-provided credentials may be used for the current task without being echoed, displayed, logged, or exposed. They are not persisted, and provider, account, billing, or global route configuration is not modified, unless the user explicitly requests that configuration change.

## Get started

```bash
git clone https://github.com/nevertoday/xxd-panel-052.git
mkdir -p ~/.codex/skills
ln -s "$(pwd)/xxd-panel-052" ~/.codex/skills/xxd-panel-052
```

Claude Code users may link the same folder under `~/.claude/skills/xxd-panel-052`. Restart the agent session after installation.

```text
$xxd-panel-052
Use this photograph, ask me for the modes and copy setting, then generate fresh raster outputs.
```

Full specifications: [Skill workflow](SKILL.md) · [source archive](references/052-source.md) · [English prompt](references/xxd-panel-052-prompt.en.md) · [Chinese prompt](references/xxd-panel-052-prompt.zh-CN.md)

## About XXD

XXD is Xiaoxiaodong's abbreviated brand name. Created and maintained by [@xiaoxiaodong01](https://x.com/xiaoxiaodong01).

## Support and membership

### In-depth consultation · CNY 299/hour

One-to-one in-depth consultation for using Skills. Contact Xiaoxiaodong through WeChat. [WeChat](https://xiaoxiaodong.pages.dev/assets/wechat-qr.png)

### Xiaoxiaodong Skills User Community · CNY 99

A one-time fee joins the Skills user community for workflow sharing and peer discussion; hourly consultation is separate.

### Knowledge Planet + Member Prompt Library · CNY 699/year

One CNY 699 annual payment opens both benefits. After joining Knowledge Planet, contact Xiaoxiaodong on WeChat for a Member Prompt Library redemption code; after self-service activation in the prompt library, contact Xiaoxiaodong on WeChat for an invitation to Knowledge Planet.

[Knowledge Planet](https://wx.zsxq.com/group/15554814142882) · [Member Prompt Library](https://vip.xiaoxiaodong.ai/)

<p align="center"><a href="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png"><img src="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png" alt="XXD WeChat" width="280"></a></p>

<div align="center"><strong>Let one light landscape strip carry the everyday detail worth remembering.</strong></div>

---

<div align="center">

## Support this open-source project

Chinese-language support may use Xiaoxiaodong's own WeChat or Alipay reward codes; other editions use Buy Me a Coffee. Support is optional and never changes access to the open-source project.


<p align="center"><a href="https://github.com/nevertoday/zhongguo-traditional-colors/blob/main/docs/images/buy-me-a-coffee-qr.png?raw=true"><img src="https://github.com/nevertoday/zhongguo-traditional-colors/blob/main/docs/images/buy-me-a-coffee-qr.png?raw=true" alt="Buy Me a Coffee" width="180"></a></p>

</div>
</div>
