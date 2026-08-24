<p align="center"><img src="./assets/banner.svg" alt="XXD Panel 043 project banner" width="1200"></p>

<div align="center">

# 🦁 XXD Panel 043

### Let real soap foam redraw the subject on a dark wet plane

[![Codex Skill](https://img.shields.io/badge/Codex-Skill-000000?style=flat-square)](./SKILL.md)
[![Modes](https://img.shields.io/badge/Modes-4-5AAFA7?style=flat-square)](#)
[![Output](https://img.shields.io/badge/Output-PNG-173F46?style=flat-square)](#)

<a href="README.md">简体中文</a> · <strong>English</strong> · <a href="README.ja.md">日本語</a> · <a href="README.ko.md">한국어</a> · <a href="README.ar.md">العربية</a>

</div>

<div>

> REAL LATHER · FRONTAL FLAT-LAY · SOURCE-DARK GROUND · MICRO-BUBBLE EDGE · QUIET SPACE

The subject forms directly from real white lather, microbubbles, translucent membranes, wet edges, popped gaps, and residue on a deep source-related plane, photographed frontally without perspective distortion.

## Why this Skill exists

The style is source-dependent, not a decorative preset. Its operative transformation is:

```text
lock decisive contour and action → preserve three cues → translate solid form into foam density, gaps, membranes, and residue → choose one source-related deep clean ground → photograph frontally with no perspective distortion → leave only a few scattered bubbles and wet traces → integrate copy as a mark already present on the plane
```

If an unrelated photograph could replace the source without materially changing recognition, construction, placement, material, colour, whitespace, and copy, the result does not belong to this Panel.

## The visual contract

- Preserve at least three cues across outline, proportion, pose, direction, action, opening, or structural turn.
- Use genuine white, off-white, and translucent soap foam with varied microbubble size, bubble film, wet edge, popped cavities, merging, thinning, and small liquid residue.
- Use a perfectly frontal, level, flat-lay photographic viewpoint with accurate horizontal and vertical relations and no wide-angle, tilt, depth exaggeration, or edge distortion.
- Choose a deep, clean, low-reflection, subtly wet flat ground derived from or harmonised with source hue and temperature. Keep strong restrained light-dark contrast.
- Allow only a few scattered bubbles, droplets, seams, and wet traces around one subject; preserve large quiet space.

Complete aesthetic constraints and rejection rules live in the Skill and production prompts. They preserve the original brief without turning its historical 3:4 canvas into a hidden default. [SKILL.md](SKILL.md) · [production prompt](references/xxd-panel-043-prompt.en.md)

## Samples · From X

> [Xiaoxiaodong (@xiaoxiaodong01)](https://x.com/xiaoxiaodong01/status/2091148211050127565) · 22 August 2026<br>
> GPT2 × foam × reconstruction × aesthetic prompt × VOL.043

<table>
  <tr>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2091148211050127565"><img src="./assets/examples/sample-01.jpg" alt="XXD Panel 043 sample 1"></a></td>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2091148211050127565"><img src="./assets/examples/sample-02.jpg" alt="XXD Panel 043 sample 2"></a></td>
  </tr>
  <tr>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2091148211050127565"><img src="./assets/examples/sample-03.jpg" alt="XXD Panel 043 sample 3"></a></td>
  </tr>
</table>

<p align="center"><a href="https://x.com/xiaoxiaodong01/status/2091148211050127565">View the original post and full prompt →</a></p>

These samples demonstrate the 043 aesthetic motive. Their subjects, composition, palette, copy, and earlier canvas ratio never become generation references or current defaults.

## Four combinable output modes

Choose one or several modes with `1`, `1+3`, `1,2,4`, or `all`; `all` produces seven separate PNGs per source. After mode selection and before generation, the Skill explicitly asks for the whole finished canvas: the original-prompt `3:4`, an explicit source-aspect choice, a common ratio, or custom ratio/exact pixels. Source dimensions are never applied silently.

| Mode | Canvas rule | Result |
| --- | --- | --- |
| `top-bottom` | user-confirmed whole canvas | one complete generation: high-fidelity source above, 043 design below, approximately 50/50 |
| `left-right` | user-confirmed whole canvas | one complete generation: high-fidelity source left, 043 design right, approximately 50/50 |
| `design-only` | user-confirmed whole canvas | 043 design fills the canvas; source remains invisible |
| `wallpaper-pack` | confirmed per device | separate phone, iPad, desktop, and children's-watch PNGs |

Paired modes use the source as a high-fidelity edit/reference input and one complete style prompt to generate the finished composition directly, so photography, design, colour, light, typography, and meaning can cohere. Deterministic composition is fallback-only: after one targeted complete-canvas retry fails, when pixel-identical source preservation is explicitly required, when the active route cannot realise the canvas, or for lossless final pixel calibration.

Wallpapers may be linked or independent. A linked pack approves one iPad anchor, then recomposes every other device from the original plus that same anchor. An independent pack gives each device only the original. Neither crops another device output nor chains derivatives.

## Copy and locale

Automatic copy, exact custom copy, or text-free output is confirmed before generation. Copy follows the intended audience rather than the command language, and exact user wording remains verbatim.

Project-specific copy rule: Use one extremely short subject, action, emotion, or metaphor title plus at most two state words. Align native type to the contour, flat-plane axis, foam edge, or negative gap; it may be partly occluded by foam but must stay legible and physical to the plane.

## Complete-canvas first, raster-only delivery

The image model owns the aesthetics of the entire finished composition; paired layouts also default to one complete-canvas generation. `scripts/compose_panel.py` remains only for condition-based recovery, lossless pixel calibration, and read-only audit. It is not run pre-emptively and does not judge aesthetic success.

Every deliverable is a raster PNG and every invocation creates a fresh task under `~/Desktop/xxd/`. The configured image route exposes sanitised status only—never providers, endpoints, credentials, headers, prompts, responses, or account details. SVG, HTML, Canvas, diagrams, and programmatic drawing are not substitutes for the final artwork.

## Image-model priority

GPT Image 2 is the default first choice. It keeps this project's established workflow: high-fidelity source reference, explicit whole-canvas selection before generation, one complete-canvas generation for paired modes, and scripted composition only as a conditional fallback.

Seedance 5.0 Pro, Nano Banana Pro (Gemini Image Pro), Nano Banana 2 (Gemini Image Flash), or another compatible bitmap model may also be used when it is actually available through the current tools or configured routes and can satisfy source fidelity, whole-canvas ratio, target-language text, and linked-wallpaper multi-reference requirements. An alternative changes only the generation route; it must not change modes, canvas, copy, locale, wallpaper relationship, or the complete-canvas-first strategy.

If no suitable route is available, the Skill asks the user to enable an image-generation tool or provide an API key. User-provided credentials may be used for the current task without being echoed, displayed, logged, or exposed. They are not persisted, and provider, account, billing, or global route configuration is not modified, unless the user explicitly requests that configuration change.

## Get started

```bash
git clone https://github.com/nevertoday/xxd-panel-043.git
mkdir -p ~/.codex/skills
ln -s "$(pwd)/xxd-panel-043" ~/.codex/skills/xxd-panel-043
```

Claude Code users may link the same folder under `~/.claude/skills/xxd-panel-043`. Restart the agent session after installation.

```text
$xxd-panel-043
Use this photograph, ask me for the modes and copy setting, then generate fresh raster outputs.
```

Full specifications: [Skill workflow](SKILL.md) · [source archive](references/043-source.md) · [English prompt](references/xxd-panel-043-prompt.en.md) · [Chinese prompt](references/xxd-panel-043-prompt.zh-CN.md)

## About XXD

XXD is Xiaoxiaodong's abbreviated brand name. Created and maintained by [@xiaoxiaodong01](https://x.com/xiaoxiaodong01).

## Support and membership

### In-depth consultation · CNY 299/hour

One-to-one in-depth consultation for using Skills. Contact Xiaoxiaodong through WeChat. [WeChat](https://xiaoxiaodong.pages.dev/assets/wechat-qr.png)

### Xiaoxiaodong Skills User Community · CNY 99

A one-time fee joins the Skills user community for workflow sharing and peer discussion; hourly consultation is separate.

### Knowledge Planet + Member Prompt Library · CNY 699/year

One annual payment opens both Knowledge Planet and the member prompt library. Join either side, then contact Xiaoxiaodong on WeChat for the other access.

[Knowledge Planet](https://wx.zsxq.com/group/15554814142882) · [Member Prompt Library](https://vip.xiaoxiaodong.ai/)

<p align="center"><a href="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png"><img src="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png" alt="XXD WeChat" width="280"></a></p>

<div align="center"><strong>The subject appears where bubbles gather—and remains where they begin to break.</strong></div>

---

<div align="center">

## Support this open-source project

Chinese-language support may use Xiaoxiaodong's own WeChat or Alipay reward codes; other editions use Buy Me a Coffee. Support is optional and never changes access to the open-source project.


<p align="center"><a href="https://github.com/nevertoday/zhongguo-traditional-colors/blob/main/docs/images/buy-me-a-coffee-qr.png?raw=true"><img src="https://github.com/nevertoday/zhongguo-traditional-colors/blob/main/docs/images/buy-me-a-coffee-qr.png?raw=true" alt="Buy Me a Coffee" width="180"></a></p>

</div>
</div>
