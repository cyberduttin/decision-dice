# Decision Dice — a teaching demo

> **This is not a product.** Decision Dice is a deliberately trivial demo app, built in
> about five minutes, so we can walk clients through getting an Android app from
> zero to **live on Google Play**, end to end.

The app is one screen and one button. It answers YES, NO, or ASK AGAIN. That's all it does,
and that's on purpose.

## Why so simple?

The lesson is the **publishing pipeline**, not the app. A real feature set would bury it.
Keeping the app tiny (the KISS principle) keeps the session on the parts clients
actually get stuck on:

1. Create the project and produce a **signed release bundle** (`.aab`)
2. Set up **upload keys** and **Play App Signing**
3. Set up the **Play Console**: app content, data safety, content rating, target audience
4. Prepare the **store listing**: icon, feature graphic, screenshots, description
5. Publish a **privacy policy** at a public URL (this repo)
6. Go through **testing tracks → production review → live**

Each of those steps is the same whether the app is a dice roller or a banking app.
With nothing in the app to discuss, the whole session goes to the process.

## What's in this repo

| File | Purpose |
|---|---|
| `index.html` | The app's privacy policy, served through GitHub Pages at <https://cyberduttin.github.io/decision-dice/>. Google Play requires a public privacy-policy URL, so this repo exists to provide one. |

This repo also shows a useful trick: for a simple app, a free GitHub Pages site is a perfectly
good place to host the required privacy policy.

## Out of scope, on purpose

No backend, accounts, analytics, ads, monetization, or permissions. Each one adds
Console forms, policy obligations, and review risk, which belong in a follow-up lesson.

---

Built by **Infinite Improbability LLC** as client training material.
