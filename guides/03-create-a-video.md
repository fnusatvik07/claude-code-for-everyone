# 3. Create an explainer video

Goal: turn a description into a real animated explainer, with **narration, captions, and motion**, using **HyperFrames**. The example in this workshop is a 30-second **ETL data pipeline** explainer (watch it in [`../video/etl-explainer.mp4`](../video/etl-explainer.mp4)).

> Same loop again: describe it, watch it back, describe the fix, it re-renders.

---

## Setup (one time)

HyperFrames runs through `npx`. You need **Node.js 22+** and **FFmpeg** installed. Then everything is `npx hyperframes ...`, no install step.

---

## Step 1 Describe the video (the prompt)

This is the entire prompt that made the example. Name the **topic, length, example, style, and ask for narration**:

```
Make a 30-second explainer about how an ETL data pipeline works, using a retail
cloud-migration example. Cover extract, transform, load, batch vs streaming, and
data lake to warehouse. Databricks style, with narration.
```

Claude writes the video as HTML + an animation timeline, then renders every frame.

---

## Step 2 Know what you can control

You can ask for any of these, all by describing them:

| Feature | What it does |
|---|---|
| **Scenes & motion** | GSAP timelines, entrances, transitions between scenes |
| **Narration** | text-to-speech voiceover from your script |
| **Captions** | synced word-by-word to the voice |
| **Music & audio** | background tracks, volume, ducking under narration |
| **Audio-reactive** | glow and pulse on the beat |
| **Effects** | 3D, shaders, Lottie, animated charts |

---

## Step 3 Review it

Watch the render back and check three things, then say what to fix:

- Is the **narration in sync** with what's on screen?
- Is any **text cut off**? (ask Claude to run `inspect` to catch overflow)
- Does the **pacing** feel right, or too fast/slow?

---

## Step 4 Improve it (say what's wrong)

| When it's | Say this |
|---|---|
| Too fast | "Slow scene 2 down and hold the title longer." |
| Flat | "Add a crossfade between scenes and stagger the entrances." |
| Needs a voice | "Add narration with this script, and sync captions to it." |
| Silent | "Add soft background music at 30%, duck it under the voice." |
| Text cut off | "Run inspect and fix the overflow on that card." |
| Off-brand | "Use these colors and this font across every scene." |

Each time, it re-renders. Stop when it's good, then export the MP4 and share it.

---

⬅️ Back to the [README](../README.md) · See [resources](../resources.md) for more skills & tools.
