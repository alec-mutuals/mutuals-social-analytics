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
---

# Collection report

Mode: Read / Operate. Inherits the supplied collection sheet’s white and neutral-gray palette, system sans typography, green share-rate emphasis, clear data hierarchy. Extend the existing review page’s source-linked cards and methodology details.

Tokens: background #f5f5f3; surface #fff; ink #171b1d; secondary #545e62; border #d7dcdd; accent #236658. Body 16px / 1.55. Max content 1200px. Cards responsive 3 / 2 / 1 columns. Focus 3px accent.
