# 🎯 The prompt cheatsheet

The one move: **look at what it made → say what's wrong in plain English → Claude fixes it.** You never edit files. Keep this open while you build.

---

## The 3 rules behind every good prompt

1. **Say the audience + goal + format.** ("for investors", "8 slides", "as a PowerPoint", "30 seconds")
2. **Give it material.** Paste the outline or drop the file, don't make it guess.
3. **Iterate in plain English.** Name what you *see* wrong; let Claude pick the fix.

---

## 📊 Fixing a presentation

| When it looks | Say this |
|---|---|
| Too crowded | `Max 4 bullets per slide, one idea each. Move detail to speaker notes.` |
| Boring / flat | `Use a bold palette that fits the topic, and one image or icon on every slide.` |
| Hard to read | `Make the titles bigger and add stronger contrast between title and body.` |
| Text cut off | `Render the slides as images and fix any overflow.` |
| Every slide same | `Vary the layouts, two-column, big quote, stat grid.` |
| Numbers buried | `Turn the stats into a bar chart.` |
| Off-brand | `Use these colors: #6F4E37 and #E8C9A0, consistent across all slides.` |
| Wrong length | `Cut slide 4.` / `Add a slide with 2 real examples.` |
| Want a grade | `Rate this deck 1-10 on clutter, structure, color, hierarchy, imagery, layout, data, headlines, polish, format. Fix anything under 8.` |

**Tell it the sections.** The secret beginners miss, a deck is just sections, so name them:

```
Make a pitch deck with these slides: 1) title, 2) the problem, 3) our solution,
4) how it works, 5) the market, 6) traction, 7) the team, 8) the ask. Audience: investors.
```

---

## 🎬 Fixing a video

| When it's | Say this |
|---|---|
| Too fast | `Slow scene 2 down and hold the title longer.` |
| Flat | `Add a crossfade between scenes and stagger the entrances.` |
| Needs a voice | `Add narration with this script, and sync captions to it.` |
| Silent | `Add soft background music at 30%, duck it under the voice.` |
| Text cut off | `Run inspect and fix the overflow on that card.` |
| Off-brand | `Use these colors and this font across every scene.` |

---

## 🌐 Fixing a website / portfolio

| When you want | Say this |
|---|---|
| A different feel | `Make it dark` / `light` / `use a warm coral accent` |
| More content | `Add a projects section with 3 cards.` |
| More polish | `Make the hero full-screen and animate the timeline on scroll.` |
| A different font | `Use a clean serif font.` |
| It live | `Deploy this to GitHub Pages so I have a link to share.` |

---

## 🪂 You can't break anything

Don't like a change? `Undo that.` or `Go back to the version before the colors.` There's no wrong move.
