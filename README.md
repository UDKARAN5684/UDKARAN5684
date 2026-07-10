# 🚀 Go-Live Guide — Publish Your Professional Profile

Follow these in order. Total time: ~15 minutes. No coding — just copy, paste, click.

Your profile repo is: **[github.com/UDKARAN5684/UDKARAN5684](https://github.com/UDKARAN5684/UDKARAN5684)**

---

## PART 1 — Update your profile README (2 min · instant result)

1. Open **[your profile repo](https://github.com/UDKARAN5684/UDKARAN5684)**.
2. Click **README.md**, then the **pencil ✏️ (Edit)** icon.
3. Select all the old text (**Ctrl+A**) and **delete** it.
4. Open `README.md` (in this folder), **copy everything**, and **paste** it in.
5. Click **Commit changes**.

✅ Refresh your profile — the wave header, badges, stats, trophies, and projects appear right away.

⚠️ Three images will look broken for now: **Metrics**, the **Snake**, and (briefly) stats. They fill in after Parts 3–4. That's normal.

---

## PART 2 — Turn on Actions write permission (1 min · needed for Snake & Metrics)

1. Go to **[Actions settings](https://github.com/UDKARAN5684/UDKARAN5684/settings/actions)**.
2. Scroll to **Workflow permissions**.
3. Select **Read and write permissions** → click **Save**.

---

## PART 3 — Metrics dashboard (7 min · the screenshot look)

Three small steps: **make a token → save it as a secret → add the workflow.**

### 3a — Create a Personal Access Token

1. Open **[Generate new token (classic)](https://github.com/settings/tokens/new)**.
2. **Note:** `metrics token`
3. **Expiration:** `No expiration` (or 1 year).
4. **Scopes:** tick ✅ `repo`, ✅ `read:org`, ✅ `read:user`.
5. Click **Generate token** and **COPY** it (starts with `ghp_...`). You won't see it again.

### 3b — Save it as a secret

1. Open **[Actions secrets](https://github.com/UDKARAN5684/UDKARAN5684/settings/secrets/actions)**.
2. Click **New repository secret**.
3. **Name:** `METRICS_TOKEN` (exactly, all caps).
4. **Secret:** paste your `ghp_...` token.
5. Click **Add secret**.

### 3c — Add the workflow file

1. On the repo, click **Add file → Create new file**.
2. Filename (type exactly): `.github/workflows/metrics.yml`
3. Copy the contents of `.github/workflows/metrics.yml` (in this folder) and paste it in.
4. Click **Commit changes**.

---

## PART 4 — Contribution Snake (2 min)

The snake uses GitHub's built-in token — no personal token needed (you already enabled write access in Part 2).

1. On the repo, click **Add file → Create new file**.
2. Filename (type exactly): `.github/workflows/snake.yml`
3. Copy the contents of `.github/workflows/snake.yml` (in this folder) and paste it in.
4. Click **Commit changes**.

---

## PART 5 — Run both actions the first time (2 min)

1. Open the **[Actions tab](https://github.com/UDKARAN5684/UDKARAN5684/actions)**.
2. Click **Metrics** on the left → **Run workflow → Run workflow**. Wait for the green ✅.
3. Click **Generate Snake** on the left → **Run workflow → Run workflow**. Wait for the green ✅.
4. Refresh your profile — the **Metrics dashboard** and **Snake** now show. Both auto-update daily. 🎉

> ❗ If your default branch is `master` (not `main`), edit the Metrics image line in `README.md`
> and change `/main/github-metrics.svg` to `/master/github-metrics.svg`.

---

## PART 6 — Quick wins that make you look pro (5 min)

Recruiters click into your repos, so this matters as much as the README.

1. **Add a description to every repo** (repo → ⚙️ gear next to "About"):
   - `Cyberbullying_Detection_NLP` → *NLP model that detects cyberbullying & abusive content.*
   - `AU_Activity_Record` → *Student-activity tracking app with an Appwrite backend.*
   - `Moodify-App` → *Mood-based mobile app built with Flutter & Dart.*
   - `E-Commerce_Website` → *Full e-commerce website with cart & checkout (PHP + MySQL).*
   - `Banking_System` → *Console-based banking management system written in C.*

2. **Add topics/tags** (same "About" box): `python`, `machine-learning`, `nlp`, `deep-learning`, `llm`, `flutter`, `appwrite`.

3. **Hide the `Test` repo** → repo **Settings** → scroll down → **Change visibility** (make private) or **Delete**.

4. **Pin your best 6** → on your profile click **Customize your pins** and choose:
   `Cyberbullying_Detection_NLP`, `AU_Activity_Record`, `Moodify-App`, `E-Commerce_Website`, `Banking_System`, `cognitive-lab`.

5. **Add a short README to each project repo** (what it does + how to run it). Biggest credibility boost after your profile — I can draft these for you, just ask.

---

## 🎨 Change the color theme later

Stat cards use `github_dark`. Find-and-replace `github_dark` in `README.md` with any of:
`tokyonight`, `dracula`, `radical`, `gruvbox`, `catppuccin_mocha`.
(Activity graph uses `github-dark` with a hyphen; the trophy uses `gitdimmed`.)

---

Do **Part 1** first for the instant win, then work down. You've got this! 🚀
