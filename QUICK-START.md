# Quick Start Guide

## 🚀 Generate a Landing Page in 3 Steps

### Step 1: Get YAML from Claude
1. Open your Claude conversation (or create a Claude Project for reusability)
2. Use this prompt:
   ```
   Generate landing page content in YAML format for: [YOUR TOPIC]
   
   [Copy the full structure from claude-prompt-template.md]
   ```
3. Copy the YAML output Claude generates

### Step 2: Convert to HTML
1. Open `index.html` in your browser
2. Paste the YAML into the left panel
3. Click **"Generate HTML →"**

### Step 3: Get Your Landing Page
1. Click **"Copy HTML"** to copy to clipboard
2. Or click **"Download"** to save as a file
3. Paste into WordPress or your website!

---

## 💡 Pro Tips

### For Best Results:
- Be specific with your topic ("AI-powered fitness coaching for busy executives" not just "fitness coaching")
- You can edit the YAML before generating HTML
- Use the "Load Example" button to see a complete working example

### Reusable Workflow:
1. Create a Claude Project
2. Add the YAML structure to the project knowledge
3. Just provide the topic each time and get instant YAML

### Sharing with Your Team:
- Host `index.html` on GitHub Pages (free, 2-minute setup)
- Or just give them the folder - works offline once loaded!

---

## 📁 What's in the Folder

- `index.html` - The converter tool ⭐ **Start here**
- `the-good-landing-page-template.html` - Your WordPress template (don't edit)
- `example-content.yaml` - See a complete example
- `claude-prompt-template.md` - Copy-paste prompt for Claude
- `README.md` - Full documentation

---

## ❓ Quick Troubleshooting

**Nothing happens when I click Generate HTML?**
- Make sure all 3 files (index.html, template, example) are in the same folder
- Check browser console for errors (F12)

**YAML parsing error?**
- Make sure Claude returned valid YAML (no extra text)
- Check for quotes around special characters
- Compare with `example-content.yaml`

**Some content is missing?**
- Check that variable names match exactly (case-sensitive)
- Not all fields are required - empty ones are fine

---

## 🎯 Your First Landing Page

Try this right now:

1. Open `index.html`
2. Click **"Load Example"**
3. Click **"Generate HTML →"**
4. Click **"Copy HTML"**
5. Done! You have a landing page in your clipboard

Now try with your own topic using Claude!
