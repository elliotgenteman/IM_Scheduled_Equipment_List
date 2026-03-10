# Equipment Schedule Tool — Deployment Guide

## What You Need
- A free Vercel account (vercel.com)
- Your Anthropic API key

---

## Step-by-Step: How to Deploy

### 1. Create a free Vercel account
- Go to **vercel.com**
- Click "Sign Up" — you can sign up with your email
- No credit card required

### 2. Upload the project
- Once logged in, click **"Add New Project"**
- Look for the option that says **"Upload"** or drag the entire `equipment-schedule-app` folder into the window
- Vercel will detect it automatically

### 3. Add your API key (this keeps it secure)
- Before clicking Deploy, look for **"Environment Variables"**
- Click "Add"
- In the Name field type exactly:  `ANTHROPIC_API_KEY`
- In the Value field, paste your Anthropic API key
- Click Save

### 4. Deploy
- Click the **Deploy** button
- Wait about 60 seconds
- Vercel will give you a link like: `your-tool.vercel.app`

### 5. Share the link
- Copy that link and share it with your team via email, Teams, or paste it into SharePoint as a link
- Anyone who opens it can use the tool immediately — no downloads, no installs

---

## That's it!

Your coworkers just need to:
1. Open the link
2. Upload their PDF form
3. Enter the rate and deductible
4. Click Generate
5. Download their spreadsheet

---

## If Something Goes Wrong
- Double-check your API key was entered correctly in Vercel (no extra spaces)
- Make sure the PDF is an ACORD 146 or Applied 146SE form
- If the tool stops working, your API key may need to be renewed — update it in Vercel under Project Settings → Environment Variables
