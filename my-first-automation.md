# My First Automation Idea

## What I want to automate
(Copy new email leads into a spreadsheet)

## Why it's repetitive
(The work takes hours)

## Tools involved
(Gmail, excel, and Make)

## The trigger
(A new email arrives)

## The steps
1. sign up Go to zapier.com or make.com and create a free account.
2. Create a new "Zap"
Click "+ Create Zap". A Zap = one automation.
3. Set your Trigger
Choose app: Gmail (or Outlook)
Choose trigger event: "New Email" or "New Email Matching Search"
Connect your Gmail account
Set a filter, e.g. only emails with subject containing "lead" or from a specific sender like your contact form
4.  Set your Action
Choose app: Google Sheets
Choose action: "Create Spreadsheet Row"
Connect your Google account
Select your spreadsheet and the specific sheet (tab)
Map the fields:
Column A ← Email sender's name
Column B ← Email address
Column C ← Subject line
Column D ← Date received
Column E ← Email body (or part of it)
5. Test it
Zapier will ask you to test the Zap with a real email. Check that a row appears in your spreadsheet.
6. Turn it on
Flip the toggle to ON. You're done!
## The desired outcome
(Copy email leads to a Spreadsheet)

## Claude's suggested plan
Great goal — this is one of the most popular beginner automations, and totally doable without writing any code! Here's a full beginner-friendly breakdown:

---

## 📧 → 📊 Automation: Copy Email Leads to a Spreadsheet

---

### 1. 🔍 Break Down the Task

1. A new email arrives in your inbox
2. The automation reads the email
3. It extracts the lead info (name, email, maybe phone or message)
4. It adds a new row to your spreadsheet with that info

---

### 2. ⚡ The Trigger (What Starts It)

> **"A new email arrives"** — specifically one that looks like a lead (e.g., from a contact form, inquiry, or a subject line like "New Lead" or "New Form Submission")

---

### 3. 🛠️ Tools/Apps Involved

| Role | App |
|---|---|
| **Email** | Gmail or Outlook |
| **Spreadsheet** | Google Sheets or Excel |
| **Automation glue** | Make, Zapier, or n8n |

---

### 4. 🤔 Which No-Code Tool Should You Use?

| Tool | Best For | Verdict |
|---|---|---|
| **Zapier** | True beginners, fastest setup | ✅ Best for you if you want something working in 15 minutes |
| **Make.com** | More visual, more power, cheaper | ✅ Great second choice — free plan is generous |
| **n8n** | Technical users, self-hosted | ⚠️ Skip for now — steeper learning curve |

**👉 My recommendation: Start with Zapier** if speed matters, or **Make.com** if you want more flexibility for free.

---

### 5. 📋 Plain-English Automation Plan

Here's your step-by-step plan using **Zapier** (the easiest starting point):

---

**Step 1 — Sign up**
Go to [zapier.com](https://zapier.com) and create a free account.

**Step 2 — Create a new "Zap"**
Click **"+ Create Zap"**. A Zap = one automation.

**Step 3 — Set your Trigger**
- Choose app: **Gmail** (or Outlook)
- Choose trigger event: **"New Email"** or **"New Email Matching Search"**
- Connect your Gmail account
- Set a filter, e.g. only emails with subject containing *"lead"* or from a specific sender like your contact form

**Step 4 — Set your Action**
- Choose app: **Google Sheets**
- Choose action: **"Create Spreadsheet Row"**
- Connect your Google account
- Select your spreadsheet and the specific sheet (tab)
- Map the fields:
  - Column A ← Email sender's name
  - Column B ← Email address
  - Column C ← Subject line
  - Column D ← Date received
  - Column E ← Email body (or part of it)

**Step 5 — Test it**
Zapier will ask you to test the Zap with a real email. Check that a row appears in your spreadsheet.

**Step 6 — Turn it on**
Flip the toggle to **ON**. You're done! 🎉

---

### 💡 Pro Tips for Beginners

- **Set up your Google Sheet first** with column headers before building the Zap — it makes mapping much easier
- If your leads come from a **contact form** (like Typeform, Gravity Forms, or Jotform), you can trigger directly from those instead of email — even cleaner!
- Zapier's free plan allows **100 tasks/month** — enough to test and get started

---

Want me to help you with a specific part — like setting up the Google Sheet template, or if your leads come from a specific source like a website form?