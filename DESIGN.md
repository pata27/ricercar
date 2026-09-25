---
name: ricercar
description: Native bit-perfect music player for Linux; the streaming-app canon played straight, plus an honest signal path.
colors:
  accent-gold: "#d4a35a"
  on-accent-dark: "#121008"
  on-accent-light: "#ffffff"
  ground: "#0f0f11"
  panel: "#141417"
  raised: "#1c1c21"
  overlay: "#232329"
  hover: "#ffffff0d"
  press: "#ffffff17"
  selected: "#ffffff14"
  line: "#ffffff12"
  line-strong: "#ffffff24"
  scrim: "#000000a6"
  text: "#f3f2ef"
  text-secondary: "#b3b2b9"
  text-tertiary: "#8a8990"
  good: "#4cc38a"
  warn: "#e5ad4a"
  bad: "#ef5f5f"
  hires-gold: "#f0cf8a"
  listening-room: "#0b0b0d"
  ground-light: "#f6f5f2"
  panel-light: "#eeede8"
  raised-light: "#ffffff"
  text-light: "#151518"
  text-secondary-light: "#55545c"
  text-tertiary-light: "#75747c"
  good-light: "#1f8a57"
  warn-light: "#a86a06"
  bad-light: "#c9302c"
  hires-gold-light: "#93620c"
typography:
  display:
    fontFamily: "Inter Display, Inter, sans-serif"
    fontSize: "56px"
    fontWeight: 800
    letterSpacing: "-1.2px"
  headline:
    fontFamily: "Inter Display, Inter, sans-serif"
    fontSize: "36px"
    fontWeight: 800
    letterSpacing: "-0.8px"
  headline-sm:
    fontFamily: "Inter Display, Inter, sans-serif"
    fontSize: "26px"
    fontWeight: 700
  title:
    fontFamily: "Inter, sans-serif"
    fontSize: "20px"
    fontWeight: 700
  title-sm:
    fontFamily: "Inter, sans-serif"
    fontSize: "16px"
    fontWeight: 700
  body-strong:
    fontFamily: "Inter, sans-serif"
    fontSize: "14px"
    fontWeight: 600
  body:
    fontFamily: "Inter, sans-serif"
    fontSize: "13px"
    fontWeight: 400
  meta:
    fontFamily: "Inter, sans-serif"
    fontSize: "12px"
    fontWeight: 400
  label:
    fontFamily: "Inter, sans-serif"
    fontSize: "11px"
    fontWeight: 700
    letterSpacing: "0.6px"
  badge:
    fontFamily: "Inter, sans-serif"
    fontSize: "10px"
    fontWeight: 700
    letterSpacing: "0.4px"
rounded:
  sm: "4px"
  md: "8px"
  lg: "12px"
  pill: "9999px"
spacing:
  hairline: "2px"
  xs: "4px"
  sm: "8px"
  md: "12px"
  lg: "16px"
  xl: "24px"
  gutter: "32px"
  room: "48px"
components:
  button-primary:
    backgroundColor: "{colors.accent-gold}"
    textColor: "{colors.on-accent-dark}"
    typography: "{typography.body}"
    rounded: "{rounded.pill}"
    padding: "0 18px"
    height: "36px"
  button-secondary:
    backgroundColor: "{colors.hover}"
    textColor: "{colors.text}"
    typography: "{typography.body}"
    rounded: "{rounded.pill}"
    padding: "0 18px"
    height: "36px"
  button-secondary-hover:
    backgroundColor: "{colors.selected}"
  button-danger:
    backgroundColor: "{colors.hover}"
    textColor: "{colors.bad}"
    rounded: "{rounded.pill}"
    height: "36px"
  play-button:
    backgroundColor: "{colors.accent-gold}"
    textColor: "{colors.on-accent-dark}"
    rounded: "{rounded.pill}"
    size: "52px"
  transport-play:
    backgroundColor: "{colors.text}"
    textColor: "{colors.ground}"
    rounded: "{rounded.pill}"
    size: "40px"
  icon-button:
    backgroundColor: "transparent"
    textColor: "{colors.text-secondary}"
    rounded: "{rounded.pill}"
    size: "32px"
  icon-button-hover:
    backgroundColor: "{colors.hover}"
    textColor: "{colors.text}"
  text-field:
    backgroundColor: "{colors.hover}"
    textColor: "{colors.text}"
    typography: "{typography.body}"
    rounded: "{rounded.md}"
    padding: "0 8px 0 12px"
    height: "36px"
  text-field-focus:
    backgroundColor: "{colors.raised}"
  badge:
    backgroundColor: "transparent"
    textColor: "{colors.text-secondary}"
    typography: "{typography.badge}"
    rounded: "{rounded.sm}"
    height: "18px"
    padding: "0 6px"
  quality-chip:
    backgroundColor: "{colors.hover}"
    textColor: "{colors.text}"
    typography: "{typography.label}"
    rounded: "{rounded.pill}"
    height: "24px"
    padding: "0 10px 0 9px"
  nav-item:
    backgroundColor: "transparent"
    textColor: "{colors.text-secondary}"
    typography: "{typography.body-strong}"
    rounded: "{rounded.md}"
    height: "36px"
    padding: "0 12px"
  nav-item-active:
    backgroundColor: "{colors.selected}"
    textColor: "{colors.text}"
  track-row:
    backgroundColor: "transparent"
    textColor: "{colors.text}"
    rounded: "{rounded.md}"
    height: "52px"
    padding: "0 16px"
  track-row-hover:
    backgroundColor: "{colors.hover}"
  album-tile:
    rounded: "{rounded.md}"
    width: "176px"
  toggle:
    backgroundColor: "{colors.line-strong}"
    rounded: "{rounded.pill}"
    width: "38px"
    height: "22px"
  toggle-on:
    backgroundColor: "{colors.accent-gold}"
  menu:
    backgroundColor: "{colors.overlay}"
    rounded: "{rounded.md}"
    width: "236px"
    padding: "5px"
  dialog:
    backgroundColor: "{colors.overlay}"
    rounded: "{rounded.lg}"
    width: "420px"
    padding: "24px"
  toast:
    backgroundColor: "{colors.overlay}"
    textColor: "{colors.text}"
    rounded: "{rounded.pill}"
    height: "44px"
    padding: "0 20px 0 16px"
  sidebar:
    backgroundColor: "{colors.panel}"
    width: "240px"
    padding: "18px 12px 12px"
  player-bar:
    backgroundColor: "{colors.panel}"
    height: "88px"
    padding: "0 16px"
---

# Design System: ricercar

## Overview

**Creative North Star: "The Listening Room With the Lid Off"**

ricercar plays the streaming-app canon straight (the finish level of Apple Music, Spotify and the Qobuz desktop client): a near-black ground, covers that carry the colour, and chrome that steps back until it is needed. The one thing it adds to that canon is a readout nobody else ships honestly: the signal path, from file to DAC, with each hop marked untouched or altered. The system is otherwise conventional on purpose. Familiar placement is what lets the one new idea read clearly.

Density is calm, not dashboard. Pages sit in a 32px gutter, track rows are 52px, album covers are 176px, and the player bar is a fixed 88px strip. Colour comes from the music: one warm gold accent by default, re-tinted from the playing cover and then pushed to a readable contrast. Green, amber and red are reserved for chain truth and errors. The now-playing view turns the whole window into a dark room over a blurred cover, whatever the app theme.

The visual rejection is confirmed in PRODUCT.md: no skeuomorphic hi-fi costume (no brushed metal, VU needles, wood or LED segments) and no technical-dashboard density.

**Key Characteristics:**
- Near-black tonal layers (ground, panel, raised, overlay); a light theme mirrors every role.
- One accent at a time, cover-derived while playing, always lifted to 4.5:1 or better on the ground.
- Status colour means chain state: green bit-perfect, amber altered, red error or live.
- Inter for everything, Inter Display (ExtraBold, tight tracking) for page and hero titles.
- Pills for actions and chips, 8px corners for covers and rows, 12px for panels and dialogs.
- Short ease-out motion (140ms on state, 260ms on reveal).

## Colors

Near-black neutrals with a single warm accent that the music itself may re-tint, plus three status hues that each mean exactly one thing.

### Primary
- **Warm Gold** (accent-gold): the default accent. Primary buttons, the big play button, toggle on-state, the seek bar fill on hover, the active nav icon, the current track title, the favourite heart, selection highlights, the dot under an active round icon button. Seven user choices ship (gold, coral, rose, violet, blue, teal, green); the chosen one and the cover-derived one both pass through `readable_accent` before use.
- **Accent Ink** (on-accent-dark / on-accent-light): text and icons on an accent fill. Near-black on dark, white on light, because the accent is kept light on dark themes and dark on light themes.
- **Accent Wash** (accent at 16% alpha dark, 14% light): the soft accent tint; album and artist headers use a vertical accent-to-transparent wash (20% dark, 14% light) under the top bar.

### Tertiary (status)
- **Bit-Perfect Green** (good): the bit-perfect dot, untouched signal-path hops and their spine, the BIT-PERFECT device badge, success toasts.
- **Altered Amber** (warn): altered hops, the altered-chain dot, the SHARED device badge, and the volume fill whenever volume is below 100% (because that alone breaks bit-perfect).
- **Error Red** (bad): errors, destructive buttons and menu lines, and the LIVE marker for radio.
- **Hi-Res Gold** (hires-gold): the HI-RES badge only; a paler, separate gold so a format claim never reads as the interactive accent.

### Neutral
- **Ground** (ground): the page background and the colour the top bar fades to.
- **Panel** (panel): the sidebar and player bar, one step lifted from the ground.
- **Raised** (raised): cover placeholders, the focused text field, the selected segment.
- **Overlay** (overlay): menus, popovers, dialogs, toasts.
- **Interaction veils** (hover, press, selected): translucent white on dark, translucent black on light; laid over any layer, never opaque.
- **Hairlines** (line, line-strong): 1px dividers and borders; line-strong for the seek track, toggle off-state and menu borders.
- **Scrim** (scrim): behind modal dialogs.
- **Text ramp** (text, text-secondary, text-tertiary): titles; artists, meta and inactive nav; column headers, placeholders, group labels, hop labels.
- **Listening Room** (listening-room): the now-playing view's base under its blurred cover backdrop; this view uses literal white text tints (100%, 80%, 70%, 45%, 35%) regardless of theme.

### Named Rules
**The One Voice Rule.** Only one accent exists on screen at a time: the cover's while a track plays (if adaptive colour is on), otherwise the chosen base. Never introduce a second interactive hue.

**The Readable Accent Rule.** Every accent, chosen or cover-derived, is lifted toward white on dark or pushed toward black on light, hue preserved, until it clears 4.5:1 against the ground. Never feed a raw cover colour into the theme.

**The Colour Means Chain Rule.** Green, amber and red are never decoration. Green claims bit-perfect, amber flags an alteration, red is an error or live stream. If a surface is not stating chain truth or an error, it does not use them.

**The Golden-Angle Rule.** Genre tiles take hues spread by the golden angle (137.508 degrees, offset 18) at fixed saturation 0.42 and lightness 0.34, so neighbours never match and white text stays readable over a 135-degree darkening gradient.

## Typography

**Display Font:** Inter Display (Bold, ExtraBold), bundled
**Body Font:** Inter (Regular, Medium, SemiBold, Bold), bundled

**Character:** One family, two optical sizes. Inter Display at ExtraBold with negative tracking gives page and hero titles the dense, poster-like weight of the category; Inter at 13 to 14px carries everything else quietly.

### Hierarchy
- **Display** (Inter Display 800, 56px, -1.2px): album and playlist hero titles; drops to Headline size when an album title exceeds 40 characters.
- **Headline** (Inter Display 800, 36px, -0.8px): page titles (Home greeting, Albums, Artists, Tracks, Genres, Favorites, Radio, Settings, Search).
- **Headline Small** (Inter Display 700 to 800, 26px): library stats and the now-playing track title.
- **Title** (Inter 700, 20px): section titles above rows, dialog titles, genre tile names.
- **Title Small** (Inter 700, 16px): top-bar title once scrolled, empty-state headings.
- **Body Strong** (Inter 500 to 600, 14px): track, album and player-bar titles; nav items (600 when active, 500 at rest).
- **Body** (Inter 400 to 600, 13px): buttons (600), inputs, menu lines, album column, toasts, hop values.
- **Meta** (Inter 400, 12px): artists under titles, secondary meta, column headers, action links.
- **Label** (Inter 700, 11px, +0.6px): list-group labels (Playlists in the sidebar, Now playing and Next up in the queue) and the quality chip. Sentence case.
- **Badge** (Inter 700, 10px, +0.4px): HI-RES, format, BIT-PERFECT and SHARED badges. Uppercase text supplied literally.

Synced lyrics are a separate, view-local scale in Inter Display 700 at -0.3px: 30px for other lines, 34px and white for the current line (font size eases over 260ms), 20px when unsynced.

### Named Rules
**The Title Sits Alone Rule.** A page or hero title is never preceded by a small label or category tag; context goes below it in the meta line (artist · year · tracks · duration, then format · genre).

**The Two Weights of Chrome Rule.** Chrome text is 500 or 600; 700 and 800 belong to titles, labels and badges. Nothing in the chrome is set in Display.

## Layout

A fixed desktop frame: a 240px sidebar on the left, a scrolling content area, and a full-width 88px player bar at the bottom. Scrolling pages sit under a 56px top bar (back/forward, title) that is fully transparent at rest and fades to 96% ground over 60px of scroll once past a per-page threshold (40px on list pages, 220 to 250px on album, artist and playlist heroes); its hairline appears only past half fade.

Content uses a 32px horizontal gutter. Album and artist heroes are 280 to 300px tall with a 232px cover and the title block bottom-aligned beside it, 28px apart. Album rows use 176px tiles; artist tiles are 160px circles; genre tiles are 110px tall in a grid. Track tables share one column model: number (28px, right-aligned), optional 38px cover, title (stretch 3) with artist and badge on the line beneath, optional album (stretch 2), optional plays (56px), a 30px action slot, duration (44px), all 16px apart with 16px row padding, so header and rows align.

The player bar is three zones: now-playing and tools stretch equally from zero width (minimum 180px each) so the 520px transport stays centred whatever the title length. The now-playing view uses 48px padding (72px top), a cover sized to the lesser of window height minus 190px or 36% of width, and 56px between cover and content.

Spacing steps are 2, 4, 8, 12, 16, 24, 32 and 48px; 2px is reserved for stacked nav and list rows.

## Elevation & Depth

Depth is tonal first: ground, panel, raised and overlay step up in lightness, with 1px hairlines at the sidebar edge, player bar top and table header. Soft, dark, blurred drop shadows are then used for two things only: covers (so artwork reads as an object) and floating layers (menus, popovers, dialogs, toasts). Nothing in the page chrome casts a shadow.

### Shadow Vocabulary
- **Tile at rest** (blur 8px, y 3px, #00000059): album tiles; deepens to blur 18px, y 8px on hover over 260ms.
- **Play affordance** (blur 14px, y 4px, #00000066; hover play on tiles blur 10px, #00000080): round accent play buttons.
- **Hero cover** (blur 30px, y 12px, #00000080): album header cover.
- **Popover** (blur 24px, y 8 to 10px, #00000080 to #00000099): signal-path popover, context menus.
- **Toast** (blur 20px, y 6px, #00000099).
- **Modal and room** (blur 40px, y 16 to 18px, #000000b3): dialogs and the now-playing cover.

### Named Rules
**The Flat Chrome Rule.** Sidebar, player bar, top bar, rows and buttons are flat; depth there comes from tone and hairlines. Shadows belong to covers and to layers that float above the page.

## Shapes

Three corner radii and the pill. 4px for small inner things (badges, list-row covers, menu lines); 8px for covers, track rows, nav items and text fields; 12px for panels that float (signal-path popover, dialogs, genre tiles, the now-playing cover). Every action that is a single control is a full pill or circle: buttons, the play buttons, icon buttons, toggles, segmented controls, the quality chip, the toast. Artists are circles, albums are rounded squares. Borders are 1px and translucent; the only thicker stroke is the 2px ring of a signal-path hop.

## Components

### Buttons
Quiet pills; the accent is spent on one action per view.
- **Shape:** full pill, 36px tall, 18px side padding (14px on the icon side), 8px icon gap, 16px icons.
- **Primary:** accent fill with accent-ink text at 13px/600; hover brightens 8%, press darkens 15%.
- **Secondary:** hover-veil fill with a 1px line border; hover goes to the selected veil, press to the press veil.
- **Danger:** secondary shape with error-red label and icon.
- **Play button:** 52px accent circle with a filled play glyph at 40% of its size, nudged 3% right; scales 1.05 on hover. The transport play is inverted: a 40px circle in the text colour with a ground-coloured glyph, scaling 1.06.
- **Icon button:** 32px circle, 18px Lucide line icon in text-secondary, text colour on hover; active state turns the icon accent and adds a 4px accent dot beneath. Disabled icons drop to text-tertiary at half alpha.

### Chips
- **Quality chip:** 24px pill on the hover veil (selected veil on hover), a 7px status dot (green bit-perfect, amber altered, tertiary unknown) and the codec and rate in 11px/700. It is the entry to the signal path.
- **Segmented control:** 32px pill track on the hover veil; the selected segment is a raised pill with a 3px shadow. The now-playing tabs are the same shape in white-on-dark literals.

### Badges
Small 18px rounded rectangles (4px), 10px/700 uppercase, outlined in their tint at 60% alpha or filled. HI-RES uses hi-res gold (on a translucent black plate when over a cover); format badges in track rows sit on the artist line in text-tertiary; device badges read BIT-PERFECT in green or SHARED in amber.

### Cards / Containers
- **Album tile:** 176px cover, 8px corners, tile shadow; title 14px/600 (accent when current), artist 12px text-secondary. A 44px accent play button fades in at bottom right on hover and stays while that album plays.
- **Artist tile:** 160px circle, 12px inset cover, selected-veil halo on hover.
- **Genre tile:** 110px, 12px corners, golden-angle hue, darkening diagonal, 20px/800 white name, scale 1.02 on hover.
- **Cover:** raised-colour placeholder with a disc (or artist, radio, music) glyph at 36% size in tertiary; the image fades in over 260ms.

### Inputs / Fields
- **Style:** 36px, 8px corners, hover-veil fill, 1px line border, 16px leading icon in text-tertiary, 13px text, tertiary placeholder, optional clear button.
- **Focus:** fill becomes raised, border becomes accent at 70%, icon becomes text colour; selection is accent at 35%.
- **Toggle:** 38 by 22px pill, line-strong off, accent on, 16px knob sliding over 140ms.

### Navigation
- **Sidebar:** panel colour, 240px, 1px right hairline. Wordmark (26px icon, "ricercar" in Inter Display 800 21px, -0.4px), search field, library nav, a Playlists group label with a plus button, scrolling playlists with track counts, Settings pinned at the bottom.
- **Nav item:** 36px, 8px corners, 18px icon and 14px label 12px apart. Rest: text-secondary; hover: hover veil, text colour; active: selected veil, 600 weight, accent icon.

### Track Table
Rows are 52px with 8px corners and a 90ms hover veil; double-click plays. The number column swaps to a play glyph on hover and to animated three-bar equaliser (accent) for the playing track, whose title turns accent. Header row is 34px in 12px text-tertiary with a clock icon for duration, over a hairline.

### Player Bar
88px panel strip. Left: 58px cover (6px corners, click opens now playing), title 14px/600, artist 12px, optional origin line in accent, heart. Centre: shuffle, previous, play, next, repeat 10px apart over a seek row (44px times in 11px, 4px track thickening to 6px on hover with a 12px knob, fill in text colour turning accent on hover). Right: quality chip, lyrics, queue, mute and a 96px volume bar whose fill turns amber below 100%.

### Signal Path (signature)
The honest chain readout. A 330px overlay popover (12px corners, popover shadow, 16px padding) opened from the quality chip, and a full tab in the now-playing view. Header: a 9px status dot and the verdict (Bit-perfect, Altered signal path, or Signal path when unknown). Each hop is a 2px ring (green untouched, amber altered, tertiary unknown) with its label in 11px tertiary and value in 13px text; a 2px spine at 45% alpha in the upper hop's colour joins each ring to the next. A plain-language sentence closes the panel, explaining either why the chain is untouched or what alters it.

### Now Playing
The listening room: listening-room base, the cover as a blurred backdrop at 90%, a horizontal black gradient (70%, 50%, 70%) and an 8% accent wash. Large cover left (12px corners, modal shadow), title, artist and album, and a status dot with the format line. Right: Lyrics, Queue and Signal path tabs. Synced lyrics scroll with a 420ms ease-out; the current line grows and turns white, past lines dim further than upcoming ones.

### Overlays
- **Menu:** 236px, overlay fill, 8px corners, line-strong border, 5px padding, 34px lines (16px icon, 13px text), 9px separators; destructive lines in red.
- **Dialog:** 420px on the scrim, 12px corners, 24px padding, 20px/700 title, buttons right-aligned.
- **Toast:** 44px pill, max 560px, check or alert icon in green or red, border turns red at 60% on error; slides and fades over 260ms.

## Do's and Don'ts

### Do:
- **Do** take every colour from the Theme global and let the light theme mirror it; white and black literals belong only on surfaces that are dark in both themes (the now-playing room, genre tiles, plates and veils laid over artwork).
- **Do** run any new accent source through `readable_accent` before it reaches `base-accent` or `cover-accent`.
- **Do** show chain state wherever format is shown: a status dot beside the codec and rate, green only when the chain is proven bit-perfect.
- **Do** keep single-control actions as pills or circles and containers at 8px or 12px.
- **Do** animate state changes at 140ms ease-out and reveals at 260ms ease-out.
- **Do** keep the transport centred by giving the two side zones of the player bar equal stretch from zero width.
- **Do** keep track-table columns on the shared column model so headers and rows align, with format badges on the artist line.

### Don't:
- **Don't** use skeuomorphic hi-fi costume (brushed metal, VU meters, LED digits, wood) or dashboard density.
- **Don't** use green, amber or red for decoration, categories or emphasis.
- **Don't** place a small label, tag or category line above a page or hero title.
- **Don't** add shadows to chrome (sidebar, player bar, top bar, rows, pill buttons); the only exceptions are round play buttons and the selected segment's 3px lift.
- **Don't** show a solid top bar at rest; it stays transparent until the page scrolls past its threshold.
- **Don't** claim bit-perfect when the chain is unknown; unknown is tertiary grey.
