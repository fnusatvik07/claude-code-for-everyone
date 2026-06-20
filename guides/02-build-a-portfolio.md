# 2. Build a portfolio website

Goal: turn a resume PDF into a polished personal website with a **live URL you can share**, in minutes. Uses my custom **portfolio-pro** plugin so the design is fixed and the result is consistent every time.

> Same loop as before: you describe changes in plain words, it rebuilds.

---

## Step 1 Install the plugin (one time)

```
/plugin marketplace add fnusatvik07/portfolio-pro-plugin
/plugin install portfolio-pro@claude4everyone
```

---

## Step 2 Drop your resume and run it

Put your resume **PDF** into the project folder. Then:

```
/portfolio
```

Claude reads the PDF itself (no copy-paste), shows you the details it extracted, and asks you to confirm before building.

> Your photo is picked up automatically, from the PDF, your public GitHub avatar, or one you drop in. No photo? It uses a clean monogram.

---

## Step 3 Make it yours

Ask for any of these in plain words, or pass them as options:

| You can change | Say something like |
|---|---|
| Theme | "make it dark" / "light" / "auto" |
| Accent color | "use a warm coral accent" or your brand hex |
| Font | "use a serif font" / "clean" / "grotesk" |
| Sections | "add a projects section with 3 cards" |

It rebuilds the site each time. Keep going until it looks right.

---

## Step 4 Review it

```
Show me the site, then make the hero full-screen and animate the timeline on scroll.
```

You describe what you want changed; you never edit the HTML.

---

## Step 5 Deploy to a live URL

When you're happy, publish it to **GitHub Pages**:

```
Deploy this to GitHub Pages so I have a live link to share.
```

What happens:
1. **You approve** the deploy (Claude never publishes a public site without your go-ahead).
2. You **sign in to GitHub once** (`gh auth login`).
3. The plugin **creates the repo, pushes the site, and enables Pages**.
4. You get a **live URL** like `https://yourname.github.io/portfolio`, open it on your phone. 🎉

> Reusable: swap the resume PDF, run `/portfolio` again, and you have a new site for anyone.

---

➡️ Next: [Create an explainer video](03-create-a-video.md)
