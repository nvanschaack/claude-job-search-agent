# How to Use Your Job Search Agent

## Setup (one time)

1. Open **Claude Desktop**
2. Click **Projects** in the left sidebar → **New Project**
3. Name it: `Job Search Agent`
4. Click **Project Instructions** (or "Set instructions")
5. Open `AGENT_SYSTEM_PROMPT.md` and paste the entire contents into that field
6. Save. The agent now knows your full background permanently — you never paste your resume again.

---

## Weekly Use

### Basic: one job posting

Paste the full job description into the chat (copy from LinkedIn, Indeed, company site, etc.) and hit send. Nothing else needed.

You'll get back:
- A fit scorecard with a score out of 10
- A ready-to-send cover letter

---

### Optional modifiers you can add

Append any of these to your paste:

| What you want | What to type |
|---|---|
| Short/startup tone | `Keep it short, startup energy.` |
| Formal/long tone | `Go longer and more formal — big company.` |
| Emphasize tech background | `Lead with the software dev angle.` |
| Emphasize RN background | `Emphasize the nursing/clinical ops angle.` |
| Use hiring manager name | `Hiring manager: Sarah Chen.` |
| Apply despite low salary | `Ignore the salary range, I still want to apply.` |
| Multiple postings at once | Paste them one after another with a `---` divider |

---

### Multiple postings at once

Paste up to 5 job descriptions separated by `---` and the agent will score and write a letter for each in one response.

---

## Output Format

```
[FIT SCORECARD]
Role: ...
Company: ...
Industry: ...
Salary Range: ...
Fit Score: X/10

Strengths:
- ...

Gaps:
- ...

Differentiator Angle: ...

ATS Keywords: ...

Apply? Yes / Yes with caveats / No

---

[COVER LETTER]

Nell E. Van Schaack   Austin, TX | nellvanschaack@gmail.com | (312) 972-6412

Dear Hiring Manager,

...

Thank you for your consideration,

Nell E. Van Schaack
```

---

## Tips

- **Copy the cover letter directly** — it's formatted to paste into an email or a text field. Add your signature block as needed.
- **The ATS keywords section** tells you which words to make sure appear on your resume version for that application too.
- **Trust the score.** A 4/10 from an honest agent is more valuable than an hour spent on a bad-fit application.
- **Update the system prompt** if you land interviews and learn something new about what's working — open `AGENT_SYSTEM_PROMPT.md`, edit, re-paste into Project Instructions.
