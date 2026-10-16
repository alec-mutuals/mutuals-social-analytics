---
name: Collection report
description: A readable, source-linked review of a saved post collection.
colors:
  bg: "#f5f5f3"
  surface: "#ffffff"
  ink: "#171b1d"
  muted: "#545e62"
  line: "#d7dcdd"
  accent: "#236658"
typography:
  body:
    fontFamily: '-apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif'
    fontSize: "16px"
    fontWeight: 400
    lineHeight: 1.55
  display:
    fontSize: "42px"
    fontWeight: 700
    lineHeight: 1.12
    letterSpacing: "-0.035em"
  headline:
    fontSize: "26px"
    fontWeight: 700
    lineHeight: 1.25
    letterSpacing: "-0.02em"
rounded:
  control: "6px"
  card: "8px"
  inspection-panel: "12px"
spacing:
  control-gap: "12px"
  group-gap: "16px"
  card-padding: "20px"
  grid-gap: "24px"
components:
  button-primary:
    backgroundColor: "{colors.accent}"
    textColor: "{colors.surface}"
    rounded: "{rounded.control}"
    padding: "10px 16px"
  button-secondary:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.ink}"
    rounded: "{rounded.control}"
    padding: "10px 16px"
  search-input:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.ink}"
    rounded: "{rounded.control}"
    padding: "10px 12px"
  post-card:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.ink}"
    rounded: "{rounded.card}"
  inspection-panel:
    backgroundColor: "{colors.bg}"
    textColor: "{colors.ink}"
    rounded: "{rounded.inspection-panel}"
    width: "min(1100px, calc(100% - 48px))"
---

# Collection report

Mode: Read / Operate. Inherits the supplied collection sheet’s white and neutral-gray palette, system sans typography, green share-rate emphasis, clear data hierarchy. Extend the existing review page’s source-linked cards and methodology details.

Tokens: background #f5f5f3; surface #fff; ink #171b1d; secondary #545e62; border #d7dcdd; accent #236658. Body 16px / 1.55. Max content 1200px. Cards responsive 3 / 2 / 1 columns. Focus 3px accent.

## Layout

The inspection panel uses a 310px evidence column beside flexible reading content, with a 36px gap. At 800px and below, the evidence column becomes 240px and the gap becomes 24px. At 600px and below, the panel stacks into one column, uses 8px corners and 8px viewport margins, and places the five engagement metrics in one row. The original collection grid retains its 900px and 560px breakpoints.

## Elevation & Depth

The inspection panel uses a soft offset shadow (`0 16px 55px rgba(0,0,0,.2)`) and dark backdrop (`rgba(13,21,19,.65)`) to separate the focused record from the collection. Other report surfaces retain their existing flat borders.

## Components

### Visual inspection panel

A native dialog opens from the six overview-image targets and selected-post controls. It holds an evidence frame, observed metrics, analysis and method limits. The header carries a Close button; Escape also dismisses the panel. Desktop evidence stays beside the reading column; mobile evidence sits above it. Selecting a sampled scene updates the image and caption, and on mobile scrolls back to the evidence. Scene buttons use a green border and pale green fill (`#eaf3ee`) for the selected state. Their timestamp, label and observation remain readable as separate elements.

The analysis heading uses 30px text on desktop and 25px at the 600px breakpoint. Coverage text distinguishes sampled visual evidence from continuous playback and audio review. Proposed creative tests remain labeled as hypotheses.

Footer extension: linked Alec Pacey credit with muted monochrome X, TikTok and Instagram SVG marks. Social links use #626b70, darkening to #30383c on hover, with 18px icons and 44px link targets. Credit and links wrap onto separate rows below560px.
