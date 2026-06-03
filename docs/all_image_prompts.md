# Image Generation Prompts — Full Export
## 腾讯云 × 创芽OPC AI Agent 活动物料

---

## Prompt 1 — Color Scheme Draft A (浅色系草图)

> Used with: `generate_image` → `scheme_a_draft.png` *(deleted after selection)*

```
A vertical event poster color scheme draft for a Chinese tech summit.

SCHEME A — LIGHT / CLEAN:
Overall background: Pure white (#FFFFFF) fading into a very soft lavender-blue gradient (#EEF2FF to #F5F3FF) at the bottom. Bright, airy, modern SaaS feel.
Top header: Three logos floating directly on the gradient — no white box, no border. Left: "腾讯全球数字生态大会·城市峰会" small badge logo. Center: "Tencent 腾讯 | 腾讯云" joint logo. Right: "创芽OPC社区" green sprout logo.
Main title typography: "腾讯云 AI Agent 助力 OPC 创业专场" in deep navy blue (#1E3A8A) to lavender purple (#C4B5FD) gradient, bold, large.
Accent color: Lavender #C4B5FD used for tags, card borders, badges.
Info card: Rounded white card with soft lavender border, glassmorphism style.
Mascot: Cute 3D hamster with green sprout on head, placed on the right side.
3D element: Soft white-blue cloud with "AI" text, glowing gently.
Bottom: QR code placeholder, handwritten slogan bottom-right.
Color palette swatch shown at the bottom: #1E3A8A (deep blue), #C4B5FD (lavender), #FFFFFF (white), #EEF2FF (ice blue), #00C35A (accent green).
Label at top: "SCHEME A — Light & Clean"
```

---

## Prompt 2 — Color Scheme Draft B (中间调草图)

> Used with: `generate_image` → `scheme_b_draft.png` *(deleted after selection)*

```
A vertical event poster color scheme draft for a Chinese tech summit.

SCHEME B — MID-TONE / PROFESSIONAL:
Overall background: Soft blue-gray (#F0F4FF) with a subtle cool gradient. More structured and corporate than Scheme A.
Top header: Three logos floating on the gradient background. Left: "腾讯全球数字生态大会·城市峰会" badge. Center: "Tencent 腾讯 | 腾讯云" joint logo. Right: "创芽OPC社区" green logo.
Main title typography: "腾讯云 AI Agent 助力 OPC 创业专场" in pure deep navy (#0052D9), bold, strong weight — no gradient on text.
Accent color: Lavender #C4B5FD used only as gradient tail on orbital sphere, badge highlight.
Info card: Frosted glass card with a stronger blue border (#0052D9 at 30% opacity).
3D element: A glowing blue orbital sphere/cloud with "AI" text, more saturated blue than Scheme A.
Mascot: Same cute 3D hamster with green sprout, slightly smaller.
Bottom: QR code placeholder, handwritten slogan bottom-right.
Color palette swatch: #0052D9 (Tencent blue), #C4B5FD (lavender accent), #F0F4FF (blue-gray bg), #FFFFFF (card), #00C35A (green).
Label at top: "SCHEME B — Mid-tone & Professional"
```

---

## Prompt 3 — Official Poster v2 (正式海报，方案A)

> Used with: `generate_image` → `guest_invitation_poster_v2.png` *(replaced by v3)*

```
A vertical event invitation poster (9:16), SCHEME A light color palette.

OVERALL: Pure white to very soft lavender-blue gradient background (#FFFFFF → #EEF2FF → #F5F3FF). Clean, modern, airy. No dark background.

TOP HEADER (no white box — logos float directly on gradient):
- Far left: "腾讯全球数字生态大会 · 城市峰会" small horizontal logo badge (dark blue text + small square icon)
- Center-right: "Tencent 腾讯 | 腾讯云" joint logo (dark blue Tencent wordmark + cloud icon)
- Far right: "创芽OPC社区" green logo (green "1" with sprout + 创芽OPC text)
All logos are on transparent backgrounds, floating on the same gradient as the poster.

MAIN VISUAL (upper half):
- Left-center: A soft 3D white-blue cloud with glowing "AI" letters inside, surrounded by a thin blue orbital ring. Gentle glow, not too saturated.
- Right of cloud: A cute 3D cartoon hamster mascot, chubby, warm brown fur, green sprout on head, smiling. Represents the solo entrepreneur spirit.

MAIN TITLE (center):
- Line 1: "腾讯云 AI Agent" — oversized bold Chinese + English, deep navy to lavender gradient (#1E3A8A → #C4B5FD)
- Line 2: "助力 OPC 创业专场" — same style
- Subtitle: "// AI 赋能创业，人人皆可入局 //" in medium gray-blue

EVENT INFO CARD (rounded white glassmorphism card, lavender border):
- 🕐 2026 / 06.12   14:00–17:00
- 📍 长沙梅溪湖金茂豪华精选酒店
- Badge pill: "2026 腾讯云城市峰会 · 长沙站" (deep blue fill, white text)

INVITATION CARD (glassmorphism frosted card, lavender gradient border):
- Title: ★ 嘉宾邀请函 ★
- Body: 诚邀您莅临，与我们相聚长沙，共启 AI 创业新征程

BOTTOM:
- Left: 创芽OPC社区 logo (green, small)
- Center: QR code placeholder square (white border, light gray fill, "扫码报名" below)
- Bottom-right: Handwritten-style slogan "AI时代，从一个人开始伟大的创业！" with a small arrow

STYLE: Professional Chinese tech event poster. Soft lavender-blue palette. Glassmorphism cards. Clean typography. Ultra HD.
--ar 9:16
```

---

## Prompt 4 — Official Poster v3 (正式海报修订版，当前最终版)

> Used with: `generate_image_variation` (reference: v2 poster + 3 logo files) → `guest_invitation_poster_v3.png` ✅ **CURRENT FINAL**

```
Modify this event poster with these three specific changes:

1. TOP AREA BACKGROUND: Remove the separate white header bar at the top. The top area background must seamlessly blend with the overall poster background — the same soft white-to-lavender-blue gradient (#FFFFFF to #EEF2FF to #F5F3FF) that covers the entire poster. No white box, no separate color block, no border or dividing line at the top. The logos at the top float directly on the same gradient background as the rest of the poster.

2. TOP LOGOS: Keep the logo arrangement at the top but they should sit directly on the gradient background (no white box behind them). Left side: "腾讯全球数字生态大会 · 城市峰会" logo with transparent background. Center-right: "Tencent 腾讯 | 腾讯云" joint logo with transparent background. Far right: "创芽OPC社区" green logo (number 1 with sprout + 创芽OPC text) with transparent background. All logos in their original colors, no white backing.

3. BOTTOM LEFT: Remove the "创芽OPC社区 One Person Company" logo from the bottom-left corner entirely. Leave that bottom-left area completely blank/empty — just the poster background gradient, no text, no logo, no icon.

Keep everything else exactly the same: the 3D cloud with AI text, the cute hamster mascot, the main title "腾讯云 AI Agent 助力 OPC 创业专场", subtitle, event info card, invitation card "嘉宾邀请函", QR code placeholder in center-bottom, and the handwritten slogan on the bottom-right.
```

---

## Summary Table

| # | Output File | Tool | Status |
|---|---|---|---|
| 1 | `scheme_a_draft.png` | `generate_image` | Deleted (replaced by v3) |
| 2 | `scheme_b_draft.png` | `generate_image` | Deleted (not selected) |
| 3 | `guest_invitation_poster_v2.png` | `generate_image` | Deleted (replaced by v3) |
| 4 | `guest_invitation_poster_v3.png` | `generate_image_variation` | **Active / Final** |
