# 1. Make a presentation

Goal: go from a plain prompt to a deck you'd actually present. Same topic the whole way, leveling up each step.

> The whole skill is one move: **describe what you want → look at the slide → describe the fix.**

---

## Step 1 Just ask (the plain prompt)

Type this into Claude Code:

```
Make me an 8-slide investor pitch deck for a neighborhood coffee shop.
Save it as a PowerPoint file.
```

You get a real `.pptx` in seconds. It works, but it's flat. That's expected, now you level it up **without touching a single slide.**

---

## Step 2 Fix it by talking

This is the most important step. You don't need design words; you need a **complaint in plain English**. Look at the deck and say what's wrong:

```
Too many words. Max 4 bullets per slide, one idea each, and move the detail into speaker notes.
```
```
Use a bold color palette that fits the topic, and put one relevant image or icon on every slide.
```
```
Render every slide as an image, then check for overlaps, overflow, and low-contrast text, and fix them before you finish.
```

The full list of "when it looks wrong, say this" is in the [cheatsheet](../prompts/cheatsheet.md).

---

## Step 3 Make Claude review it for you

Don't trust your eyes alone, make Claude grade its own deck:

```
Rate this deck out of 10 on clutter, structure, color, type hierarchy, imagery, layout
variety, data, headlines, polish, and format. Fix anything that scores under 8.
```

It finds the weak slides and fixes them.

---

## Step 4 Use a skill (the design done for you)

A **skill** is a packaged workflow. Install the official ones once:

```
/plugin marketplace add anthropics/skills
```

Then:

```
Using the pptx skill, redo that coffee-shop deck. Make it visually designed with a warm bold
palette, one visual element per slide, and strong title/body contrast. Then review your own
slides as images and fix any overlaps or overflow.
```

Want to pick a look from previews and get a shareable link? Install `frontend-slides`:

```
/plugin marketplace add https://github.com/zarazhangrui/frontend-slides
/plugin install frontend-slides@frontend-slides
```
```
/frontend-slides:frontend-slides
I want a pitch deck for a neighborhood coffee shop for local investors.
```
Then: `Deploy this to a live URL so I can open it on my phone.`

---

## Step 5 The ceiling: PitchCraft (my plugin)

For cinematic, story-first decks (real diagrams, citations, self-checks):

```
/plugin marketplace add fnusatvik07/pitchcraft
/plugin install pitchcraft@pitchcraft
```
```
/deck "the economics of a coffee shop"
```

---

## The other option: Gamma

[Gamma](https://gamma.app) is a separate website (not part of Claude). Use this map:

- Need a decent deck in **2 minutes**, in a browser? → **Gamma**
- Want to **own the file**, keep refining, or do more than decks? → **Claude Code**
- Want the cinematic ceiling or a repeatable workflow? → **a skill** (pptx · frontend-slides · PitchCraft)

---

➡️ Next: [Build a portfolio website](02-build-a-portfolio.md)
