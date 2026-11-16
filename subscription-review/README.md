# PR #3659 subscription settings review

Before: d31d9658496ed4cbed7a100092df293d9c8cf78b.
After: bb43cfb9 (2026-11-16, merged official main 72120988).

Screenshots use the real templates, styles and frontend JavaScript with simulated account APIs. All account/model data are fixtures (`demo@example.test`, `gpt-5-demo`); no real credentials or user data are included. Desktop: 1100×1000. Mobile: 390×844.

- before-signed-out.png: original top-of-page card, signed out. The old page has no collapsed state.
- before-signed-in.png: original connected card, before the automatic setup toggle existed.
- after-collapsed.png: default collapsed section between API key book and custom API settings.
- after-signed-out.png: expanded, signed out, subscription toggle disabled.
- after-enabled.png: signed in, confirmed and enabled, configuration saved.
- after-mobile.png: enabled state on a narrow viewport.
