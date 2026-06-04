# ZOREX Brand Launch Implementation Plan

> **For agentic workers:** REQUIRED SUB-SKILL: Use superpowers:subagent-driven-development (recommended) or superpowers:executing-plans to implement this plan task-by-task. Steps use checkbox (`- [ ]`) syntax for tracking.

**Goal:** Get ZOREX fully set up with brand assets, a domain, and a basic online presence ready to use in outreach.

**Architecture:** Create SVG logo files first (source of truth), export to PNG for social/web use, register domain, set up LinkedIn company page, then optionally a simple one-page site.

**Tech Stack:** SVG (logo files), Namecheap or Cloudflare (domain), LinkedIn, Netlify (if site needed)

---

### Task 1: Create Logo SVG Files

**Files:**
- Create: `brand/logo-light.svg` (icon + wordmark on light background)
- Create: `brand/logo-dark.svg` (icon + wordmark on dark background)
- Create: `brand/icon-only.svg` (mark only, no wordmark)

- [ ] **Step 1: Create the light logo SVG**

Save to `brand/logo-light.svg`:

```svg
<svg xmlns="http://www.w3.org/2000/svg" width="220" height="48" viewBox="0 0 220 48">
  <!-- Icon container -->
  <rect width="48" height="48" rx="9" fill="#0a0a0a"/>
  <!-- Convergence mark -->
  <line x1="24" y1="8" x2="24" y2="40" stroke="#f5f5f5" stroke-width="2.5" stroke-linecap="round"/>
  <line x1="8" y1="24" x2="40" y2="24" stroke="#f5f5f5" stroke-width="2.5" stroke-linecap="round"/>
  <line x1="11" y1="11" x2="37" y2="37" stroke="#f5f5f5" stroke-width="2.5" stroke-linecap="round"/>
  <circle cx="24" cy="24" r="3.5" fill="#f5f5f5"/>
  <!-- Wordmark -->
  <text x="64" y="31" font-family="Helvetica Neue, Helvetica, Arial, sans-serif"
        font-weight="300" font-size="18" letter-spacing="4.5" fill="#0a0a0a">ZOREX</text>
</svg>
```

- [ ] **Step 2: Create the dark logo SVG**

Save to `brand/logo-dark.svg`:

```svg
<svg xmlns="http://www.w3.org/2000/svg" width="220" height="48" viewBox="0 0 220 48">
  <!-- Icon container -->
  <rect width="48" height="48" rx="9" fill="#1a1a1a" stroke="#2a2a2a" stroke-width="1"/>
  <!-- Convergence mark -->
  <line x1="24" y1="8" x2="24" y2="40" stroke="#f5f5f5" stroke-width="2.5" stroke-linecap="round"/>
  <line x1="8" y1="24" x2="40" y2="24" stroke="#f5f5f5" stroke-width="2.5" stroke-linecap="round"/>
  <line x1="11" y1="11" x2="37" y2="37" stroke="#f5f5f5" stroke-width="2.5" stroke-linecap="round"/>
  <circle cx="24" cy="24" r="3.5" fill="#f5f5f5"/>
  <!-- Wordmark -->
  <text x="64" y="31" font-family="Helvetica Neue, Helvetica, Arial, sans-serif"
        font-weight="300" font-size="18" letter-spacing="4.5" fill="#f5f5f5">ZOREX</text>
</svg>
```

- [ ] **Step 3: Create the icon-only SVG**

Save to `brand/icon-only.svg`:

```svg
<svg xmlns="http://www.w3.org/2000/svg" width="48" height="48" viewBox="0 0 48 48">
  <rect width="48" height="48" rx="9" fill="#0a0a0a"/>
  <line x1="24" y1="8" x2="24" y2="40" stroke="#f5f5f5" stroke-width="2.5" stroke-linecap="round"/>
  <line x1="8" y1="24" x2="40" y2="24" stroke="#f5f5f5" stroke-width="2.5" stroke-linecap="round"/>
  <line x1="11" y1="11" x2="37" y2="37" stroke="#f5f5f5" stroke-width="2.5" stroke-linecap="round"/>
  <circle cx="24" cy="24" r="3.5" fill="#f5f5f5"/>
</svg>
```

- [ ] **Step 4: Verify files open correctly in a browser**

Open each file in Chrome/Safari to confirm they render as expected.

---

### Task 2: Register Domain

- [ ] **Step 1: Check zorex.ai availability**

Go to [Cloudflare Registrar](https://www.cloudflare.com/products/registrar/) or [Namecheap](https://www.namecheap.com) and search `zorex.ai`.

- [ ] **Step 2: If zorex.ai is available, register it**

Cloudflare is preferred — at-cost pricing, no markup, free WHOIS privacy. Register for 1 year minimum.

- [ ] **Step 3: If zorex.ai is taken, fall back to zorex.co**

Search and register `zorex.co` using the same registrar.

- [ ] **Step 4: Point domain to a holding page or leave parked**

No site needed immediately. Parking the domain is fine until Task 5.

---

### Task 3: Export PNG Assets for Social Use

- [ ] **Step 1: Open `brand/icon-only.svg` in a browser**

Right-click → open in browser tab.

- [ ] **Step 2: Export a 400×400 PNG for LinkedIn company logo**

Use any of:
- [svgtopng.com](https://svgtopng.com) — paste SVG code, export at 400×400
- Mac Preview: open SVG → Export as PNG at 2x scale

Save as `brand/icon-400px.png`.

- [ ] **Step 3: Export a 1200×627 PNG for LinkedIn banner**

Create a simple banner: black background (`#0a0a0a`), ZOREX wordmark centered in white.

Simplest method — open `brand/logo-dark.svg` in browser, screenshot at high resolution, or use [Canva](https://canva.com):
- Background: `#0a0a0a`
- Text: ZOREX, white, light weight, wide tracking
- Size: 1200×627px

Save as `brand/linkedin-banner.png`.

---

### Task 4: Set Up LinkedIn Company Page

- [ ] **Step 1: Go to LinkedIn → Work → Create a Company Page**

URL: linkedin.com/company/setup/new

- [ ] **Step 2: Fill in details**

| Field | Value |
|-------|-------|
| Name | Zorex |
| URL | linkedin.com/company/zorex (or zorex-ai if taken) |
| Website | zorex.ai (or zorex.co once registered) |
| Industry | Information Technology & Services |
| Size | 1–10 employees |
| Type | Privately Held |
| Tagline | Custom AI for industries that don't fit the mold |

- [ ] **Step 3: Upload logo and banner**

- Logo: `brand/icon-400px.png`
- Banner: `brand/linkedin-banner.png`

- [ ] **Step 4: Write the About section**

```
Zorex builds custom AI software and hardware for niche industries that off-the-shelf tools don't serve.

We work with mid-size businesses to identify the specific problems where AI can create real leverage — then build and deploy solutions tailored to their space. Once built, those solutions become products we bring to others in the same industry.

Based in Texas.
```

- [ ] **Step 5: Add Haadi and Ali as employees**

Both founders update their personal LinkedIn profiles: Current position → Zorex, Co-Founder.

---

### Task 5: Simple One-Page Website (Optional — skip if not needed yet)

*Only do this task if you need a web presence before the LinkedIn page is enough.*

- [ ] **Step 1: Create `index.html` in the project root**

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Zorex</title>
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; }
    body {
      background: #0a0a0a;
      color: #f5f5f5;
      font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;
      min-height: 100vh;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      gap: 32px;
      padding: 40px;
    }
    .logo {
      display: flex;
      align-items: center;
      gap: 16px;
    }
    .icon {
      width: 48px;
      height: 48px;
    }
    .wordmark {
      font-size: 1.5rem;
      font-weight: 300;
      letter-spacing: 0.25em;
      color: #f5f5f5;
    }
    .tagline {
      font-size: 0.85rem;
      font-weight: 300;
      letter-spacing: 0.1em;
      color: #555;
      text-align: center;
      text-transform: uppercase;
    }
    .contact {
      font-size: 0.8rem;
      color: #333;
      letter-spacing: 0.05em;
    }
    .contact a { color: #555; text-decoration: none; }
    .contact a:hover { color: #f5f5f5; }
  </style>
</head>
<body>
  <div class="logo">
    <svg class="icon" viewBox="0 0 48 48" fill="none" xmlns="http://www.w3.org/2000/svg">
      <rect width="48" height="48" rx="9" fill="#1a1a1a" stroke="#2a2a2a" stroke-width="1"/>
      <line x1="24" y1="8" x2="24" y2="40" stroke="#f5f5f5" stroke-width="2.5" stroke-linecap="round"/>
      <line x1="8" y1="24" x2="40" y2="24" stroke="#f5f5f5" stroke-width="2.5" stroke-linecap="round"/>
      <line x1="11" y1="11" x2="37" y2="37" stroke="#f5f5f5" stroke-width="2.5" stroke-linecap="round"/>
      <circle cx="24" cy="24" r="3.5" fill="#f5f5f5"/>
    </svg>
    <span class="wordmark">ZOREX</span>
  </div>
  <p class="tagline">Custom AI for industries that don't fit the mold</p>
  <p class="contact"><a href="mailto:hello@zorex.ai">hello@zorex.ai</a></p>
</body>
</html>
```

- [ ] **Step 2: Deploy to Netlify**

1. Go to [netlify.com](https://netlify.com) → Add new site → Deploy manually
2. Drag the project folder into Netlify's deploy dropzone
3. Set custom domain to `zorex.ai` (or `zorex.co`)

---

### Task 6: Update BRAIN

- [ ] **Step 1: Note brand decisions in BRAIN**

Open `/Users/haadisiddiqui/Desktop/BRAIN/` and add a note under the consulting firm project with:
- Name: ZOREX
- Domain: zorex.ai (or zorex.co)
- LinkedIn: linkedin.com/company/zorex (or variant)
- Brand assets location: `~/Desktop/Projects/ConsultingFirm/brand/`
- Color palette: monochromatic (#0a0a0a, #1a1a1a, #f5f5f5)
- Logo style: convergence mark + wide-light wordmark

---

## Execution Order

1 → 2 → 3 → 4 → 6 (required)  
5 is optional — skip unless you need a web presence immediately.
