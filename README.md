# Landing Page Generator

A simple web tool to generate landing pages from YAML content.

## Files Included

- **index.html** - The main generator tool (open this in your browser)
- **the-good-landing-page-template.html** - Your WordPress landing page template
- **example-content.yaml** - Example YAML showing all available variables

## How to Use

### Setup

1. Place all three files in the same folder
2. Open `index.html` in your web browser or run `npx http-server -p 8000`

### Workflow

1. **Generate YAML with Claude**: In your Claude Project, ask Claude to generate landing page content in YAML format for your topic
2. **Copy the YAML**: Copy the YAML output from Claude
3. **Paste into tool**: Paste it into the left panel of the generator
4. **Generate HTML**: Click "Generate HTML →"
5. **Copy or Download**: Get your finished landing page!

### Example Claude Prompt

```
Generate landing page content in YAML format for: [YOUR TOPIC]

Use this structure:

Main Headline: ""
Sub-headline: ""
Primary CTA Button: ""
Value Proposition: ""
Pain point 1: ""
Pain point 2: ""
Pain point 3: ""
Pain point 4: ""
Pain point 5: ""
Main point 1: ""
Main point 2: ""
Main point 3: ""
Process / How it works: ""
Process step 1 description: ""
Process step 2 description: ""
Process step 3 description: ""
Optional: process step 4 description: ""
Optional: process step 5 description: ""
Differentiator/why us header: ""
Differentiation point 1: ""
Differentiation point 2: ""
Differentiation point 3: ""
Differentiation point 4: ""
Differentiation point 5: ""
Differentiation point 6: ""
Social proof section heading: ""
Case study 1: ""
Case study 1 description: ""
Case study 2: ""
Case study 2 description: ""
Case study 3: ""
Case study 3 description: ""
Pricing/Offer Call Out: ""
Offer detail 1: ""
Offer detail 2: ""
Offer detail 3: ""
Offer detail 4: ""
Offer detail 5: ""
Supporting description: ""
Summary of the page: ""
CTA to get in touch and schedule a call: ""
cta button 1: ""
CTA Button 2: ""
Final CTA header: ""
FAQ 2: ""
FAQ 2 answer: ""
FAQ 3 answer: ""
FAQ 4 answer: ""
FAQ 5 answer: ""
FAQ 6 answer: ""
FAQ 7 answer: ""
FAQ 8 answer: ""
FAQ 9 answer: ""
FAQ 10 answer: ""
FAQ 11 answer: ""

Make the content compelling and professional for this topic.
```

## YAML Variables

Your template has 57 content variables organized into these sections:

**Hero Section:**

- Main Headline
- Sub-headline
- Primary CTA Button

**Value Proposition:**

- Value Proposition
- Pain point 1-5
- Main point 1-3

**Process:**

- Process / How it works
- Process step 1-3 description
- Optional: process step 4-5 description

**Differentiation:**

- Differentiator/why us header
- Differentiation point 1-6

**Social Proof:**

- Social proof section heading
- Case study 1-3 (name and description)

**Offer:**

- Pricing/Offer Call Out
- Offer detail 1-5

**CTAs:**

- CTA to get in touch and schedule a call
- cta button 1
- CTA Button 2
- Final CTA header

**FAQ:**

- FAQ 2-11 (questions and answers)

**Supporting:**

- Supporting description
- Summary of the page

## Tips

- **Use Claude Projects**: Set up a Claude Project with the YAML structure so you can quickly generate content
- **Edit as needed**: You can always manually edit the YAML before generating HTML
- **Partial content**: You don't need to fill every field - leave fields empty if not needed
- **Consistency**: Use consistent voice/tone across all fields for best results
- **CTAs**: Make sure your CTA buttons have clear, action-oriented text

## Deployment

To share this tool:

1. **GitHub Pages** (free, easiest):

   - Create a GitHub repo
   - Upload all three files
   - Enable GitHub Pages in settings
   - Share the URL

2. **Netlify** (free, drag-and-drop):

   - Go to netlify.com
   - Drag your folder onto Netlify
   - Get instant URL

3. **Any web host**: Just upload all three files to the same directory

## Troubleshooting

**"Template not loaded"**: Make sure all three files are in the same folder

**YAML parsing error**:

- Make sure you're using proper YAML syntax
- Strings with special characters should be in quotes
- Check for proper indentation
- Look at example-content.yaml for correct format

**Missing content in output**:

- Some variables may not be in your YAML
- Check variable names match exactly (case-sensitive)
- Reference example-content.yaml for the complete list
