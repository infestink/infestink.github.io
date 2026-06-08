# 📊 Expense Tracker — User Research Survey

A lightweight, privacy-first survey built as a single HTML file and hosted via GitHub Pages. Used to gather user research for an upcoming web & mobile app that auto-generates expense overviews from Revolut and Wise bank statements — no bank linking required.

---

## 🔗 Live Survey

**[infestink.github.io](https://infestink.github.io/)**

Share this link directly with friends, colleagues, or anyone in your target audience. No login, no tracking, no server — just open and answer.

---

## 💡 What This Is

This survey is part of **Phase 1 product research** for a personal finance tool. The goal is to understand:

- How people currently track their expenses (or why they don't)
- Their biggest frustrations with existing tools
- Their comfort level with uploading bank statement files
- Which features they'd actually use
- What they'd pay for a solution that saves them time

The findings will directly shape the product's positioning, feature prioritization, and monetization model.

---

## 🛠️ How It Works

The survey is a **single self-contained HTML file** with no dependencies, no backend, and no data collection on our end.

When a respondent completes the survey:
1. They click **Send my answers**
2. A formatted text summary of their responses is generated locally in the browser
3. They copy it and paste it back via WhatsApp, Telegram, or email

All processing happens client-side. Nothing is stored, transmitted, or logged anywhere.

---

## 📁 Repo Structure

```
infestink.github.io/
├── index.html        # The survey (self-contained, no dependencies)
├── .nojekyll         # Disables Jekyll so GitHub Pages serves HTML directly
└── README.md         # This file
```

---

## 🚀 Deployment

Hosted on **GitHub Pages** from the `main` branch root.

To update the survey:
1. Edit `index.html` locally or via the GitHub editor
2. Commit and push to `main`
3. Changes go live within ~60 seconds

To disable Jekyll processing (required for plain HTML sites):
```bash
touch .nojekyll
git add .nojekyll
git commit -m "disable jekyll"
git push
```

---

## 📬 Collecting Responses

Since this is a no-backend setup, responses come back manually:

1. Share the link with your target group
2. Ask them to copy their result and send it back to you
3. Paste all responses into a doc or spreadsheet
4. Analyze patterns across Q3 (frustrations), Q6 (upload comfort), Q7 (features), Q8 (pricing)

For larger scale collection (50+ responses), consider moving to [Tally](https://tally.so) or [Typeform](https://typeform.com) using the same question set.

---

## 🎯 Research Goals

| Question | What it measures |
|---|---|
| Q1 + Q2 | Current behavior baseline |
| Q3 | Core pain point for messaging |
| Q4 | Platform fit (Revolut/Wise audience) |
| Q5 | Financial self-awareness |
| Q6 | Privacy sensitivity / trust barrier |
| Q7 | Feature priority ranking |
| Q8 | Willingness to pay / pricing model |
| Q9 | Qualitative signals |

---

## 🔒 Privacy

- No analytics or tracking scripts
- No cookies
- No data leaves the respondent's browser
- Respondents choose what to share and how

---

## 📄 License

This survey and its code are for personal research use. Not intended for redistribution.
