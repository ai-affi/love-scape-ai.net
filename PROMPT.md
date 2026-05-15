# PROMPT: Build love-scape-ai.net — Lovescape AI Review Landing Page

## Objective
Build a complete, high-converting affiliate review landing page for **Lovescape** (lovescape.com) — an AI porn generator & AI companion platform — targeting the domain **love-scape-ai.net**.

**Target word count:** 1,300–15,000 words (aim for ~3,000–5,000 words of dense, SEO-rich content).

**Repo:** https://github.com/ai-affi/love-scape-ai.net
**Architecture:** Mode B (Single-language English) — `content.json` + pure HTML template, ZERO text in HTML.

---

## Scraped Data Summary (from lovescape.com)

### Platform Overview
- **Name:** Lovescape
- **Tagline:** "AI Porn Generator – Unfiltered Images & Videos | Lovescape"
- **Publisher:** Warmtech Ltd, Limassol, Cyprus
- **Type:** AI companion + AI porn generator platform (NSFW/Adult)
- **Languages supported:** EN, DE, ES, FR, IT, JA, NL, PT, RU

### Core Features (to highlight)
1. **AI Porn Image Generator** — Photorealistic adult images, up to 4K resolution, 8–25s generation, negative prompts, OpenPose/Depth/Canny pose control, inpainting, remix feature
2. **AI Porn Video Generator** — Full video generation with motion, body physics, transitions, lip-sync, 720p–1080p (4K coming), 5s–2min duration, cinematic/POV/slow-mo camera styles
3. **AI Porn Chats** — Unfiltered real-time conversations with AI companions, voice & video integration, erotic roleplay
4. **AI Girlfriend / AI Boyfriend Creator** — Custom character creation with look, personality, voice, backstory, memory
5. **Image Editing** — Edit generated images before animating (fix poses, faces, hands, backgrounds)
6. **Live Cam Chat** — Visual interactive format beyond text
7. **Memory Engine** — Remembers past interactions for evolving personalized content
8. **Character Consistency** — Same face across images, chat, and video
9. **Voice Customization** — Pitch, pace, accent tuning for voice notes & calls
10. **Privacy & Security** — End-to-end encryption (TLS 1.3+), AES-256 at rest, strict no-log policy, anonymous signup, discreet billing ("LS Digital Services"), 2FA, right to deletion

### Categories Available
AI Girlfriend, AI Boyfriend, Anime, Asian, Hentai, FUTA, Big Tits, MILF, Male, Gay, BBW, Teen 18+, GILF, Skinny, Big Ass, Blond, Brunette, Ebony, Curvy, Indian MILF AI, Small Tits, AI Latina MILF, Arab, Spicy AI Chat, Crush on AI

### Blog Content Available (for SEO depth)
- "How to Create Your Own AI Girlfriend: A Step-by-Step Tutorial"
- "What Is an AI Girlfriend Chatbot? A Practical Guide"
- "AI Girlfriend Video Calls: How Virtual Companions Feel Real"
- "How to Create the Perfect AI Boyfriend in 2026"
- "Best AI Roleplay Scenarios to Try in 2026"
- "How to Chat With Your AI Girlfriend So It Actually Feels Real"
- "AI Porn Generator: Edit Images Before You Animate Them"
- "Introducing Image Editing: Take Full Control"

### FAQ (from homepage)
- What is Lovescape's AI Porn Image Generator?
- Can I Use the AI Porn Video Generator for NSFW?
- How Does AI Porn Chat Work?
- Is Content High-Quality?
- Data Safety?

---

## Site Architecture (Mode B — Single Language English)

```
love-scape-ai.net/
├── index.html          # Pure template skeleton, ZERO text, data-i18n tags
├── content.json        # ALL text content centralized
├── _redirects          # Affiliate link cloaking
├── robots.txt          # Allow all, block legal pages, sitemap ref
├── sitemap.xml         # Single URL
├── privacy.html        # noindex,nofollow
├── terms.html          # noindex,nofollow
├── affiliate-disclosure.html  # noindex,nofollow
├── favicon.svg
└── /images/            # Placeholder images (user provides real ones)
```

**NO subfolders for languages. NO hreflang. NO language selector.**

---

## content.json Structure

Create `content.json` with ALL text. Target sections:

### 1. meta
- title: "Lovescape Review 2026 | AI Porn Generator & AI Companion Platform"
- description: "In-depth Lovescape review. AI porn image & video generator, AI girlfriend/boyfriend chat, unfiltered NSFW content, privacy-first. Is it worth it? Read our full review."
- keywords: "lovescape review, ai porn generator, ai girlfriend, ai boyfriend, ai companion, nsfw ai chat, ai porn video, ai image generator adult"
- og_title, og_description, canonical: "https://love-scape-ai.net/"

### 2. nav
- brand: "Love-Scape AI"
- cta: "Try Lovescape Now →"
- links: Features, How It Works, Pricing, FAQ, Review

### 3. hero
- badge: "2026 Review"
- title: "Lovescape Review: The Most Advanced AI Porn Generator & Companion Platform"
- subtitle: "We tested Lovescape's AI image generator, video creator, unfiltered chat, and privacy features. Here's everything you need to know before signing up."
- cta_primary: "Try Lovescape Free →"
- cta_secondary: "Read Full Review"
- social_proof: ["50,000+ users", "4K image generation", "Unfiltered AI chat"]

### 4. features (6 feature cards)
Use these features with detailed descriptions (~150 words each):
- AI Porn Image Generator (photorealistic, 4K, pose control, inpainting)
- AI Porn Video Generator (motion, lip-sync, 1080p, cinematic styles)
- AI Girlfriend / Boyfriend Chat (unfiltered, voice, video, memory)
- Image Editing Before Animation (fix faces, hands, poses, backgrounds)
- Character Consistency (same face across all media)
- Privacy & Security (encryption, no-logs, discreet billing)

### 5. how_it_works (3 steps)
- Step 1: Create Your AI Character
- Step 2: Generate Images or Start Chatting
- Step 3: Edit, Animate, and Enjoy

### 6. review_content (THE MAIN CONTENT — 2,000–4,000 words)
This is the SEO meat. Write comprehensive review sections:

**H2: What Is Lovescape?**
- Overview of the platform, publisher (Warmtech Ltd), target audience
- Position in the AI companion / AI porn market

**H2: Lovescape AI Porn Image Generator Review**
- How it works (diffusion models, text prompts)
- Resolution & speed (up to 4K, 8–25 seconds)
- Pose control (OpenPose, Depth, Canny maps)
- Inpainting & remix features
- Quality assessment

**H2: Lovescape AI Porn Video Generator Review**
- How video generation works (keyframes → motion interpolation → refinement)
- Duration options (5s–2min)
- Camera styles (handheld, cinematic, POV, slow-motion)
- Audio & lip-sync capabilities
- Quality (720p–1080p, 4K coming)

**H2: AI Girlfriend & AI Boyfriend Chat**
- Unfiltered chat experience
- Voice notes & video calls
- Memory engine (remembers past conversations)
- Character customization (look, personality, voice, backstory)
- Live Cam Chat feature

**H2: Image Editing Feature**
- Edit before animating
- Fix hands, faces, poses, backgrounds
- Why this matters for video quality

**H2: Privacy & Security Assessment**
- End-to-end encryption (TLS 1.3+, AES-256)
- No-log policy for generated content
- Anonymous signup (no real names, no mandatory KYC)
- Discreet billing ("LS Digital Services")
- 2FA, penetration testing, right to deletion

**H2: Categories & Content Types**
- List available categories (AI Girlfriend, Boyfriend, Anime, Asian, Hentai, etc.)
- Realistic vs anime styles

**H2: Pros & Cons**
- Pros: Unfiltered, high quality, fast, private, editing features, memory
- Cons: Premium features gated, adult-only, video 4K not yet available

**H2: Lovescape Pricing**
- Free tier limitations
- Premium features (unlimited HD, advanced customizations)
- Note: "Pricing details vary — check Lovescape.com for current plans"

**H2: Who Is Lovescape For?**
- Users seeking AI companions
- Content creators needing AI-generated adult visuals
- People wanting private, judgment-free exploration

**H2: Final Verdict**
- Overall rating (e.g., 4.5/5)
- Summary recommendation
- CTA to try Lovescape

### 7. comparison
- Compare Lovescape vs competitors (CrushOn.AI, SpicyChat, Candy.ai)
- Table: Features, Image Quality, Video, Privacy, Price

### 8. reviews (3–5 fake user testimonials)
- "Alex, 28, USA" — "The image quality blew me away..."
- "Jordan, 24, UK" — "Finally an AI girlfriend that remembers things..."
- "Casey, 31, Canada" — "The video generator is next level..."

### 9. faq (8–10 questions)
- What is Lovescape?
- Is Lovescape free?
- Is Lovescape safe and private?
- Can I generate AI porn videos?
- How does AI girlfriend chat work?
- Is the content high quality?
- Can I edit generated images?
- Does Lovescape have an AI boyfriend option?
- What categories are available?
- How do I delete my account?

### 10. final_cta
- title: "Ready to Try Lovescape?"
- subtitle: "Join thousands of users creating custom AI companions and adult content. Start free today."
- cta: "Try Lovescape Now →"

### 11. footer
- brand, description, columns (Legal, Resources, Social)
- copyright, disclaimer about affiliate links

---

## index.html Requirements

- Pure HTML5 template, ZERO text content
- `data-i18n` attributes for all injectable elements
- Fetch `content.json` via JavaScript and inject all content
- Tailwind CSS via CDN
- Inline `<style>` for custom CSS (dark theme preferred — Lovescape uses #0F0F0F)
- Meta tags in `<head>` (placeholders that JS overwrites)
- `rel="nofollow sponsored"` on all affiliate links
- Affiliate links cloaked via `_redirects` (`/go/lovescape`)
- Images: placeholder `/images/` folder, lazy loading, WebP preferred
- Performance: preconnect to CDN, dns-prefetch affiliate domain

### Critical HTML Head Structure
```html
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Placeholder">
  <meta name="keywords" content="placeholder">
  <meta property="og:title" content="Placeholder">
  <meta property="og:description" content="Placeholder">
  <meta name="twitter:title" content="Placeholder">
  <meta name="twitter:description" content="Placeholder">
  <link rel="canonical" href="https://love-scape-ai.net/">
  <link rel="sitemap" type="application/xml" title="Sitemap" href="/sitemap.xml">
  <script src="https://cdn.tailwindcss.com"></script>
  <style>/* custom dark theme CSS */</style>
</head>
```

---

## _redirects
```
/go/lovescape  https://lovescape.com/?ref=YOUR_AFFILIATE_ID  302
```
(Replace `YOUR_AFFILIATE_ID` with actual affiliate ref when available)

---

## robots.txt
```
User-agent: *
Allow: /
Disallow: /privacy.html
Disallow: /terms.html
Disallow: /affiliate-disclosure.html

Sitemap: https://love-scape-ai.net/sitemap.xml
```

---

## SEO Requirements
- Title: 50–60 chars
- Meta description: 150–160 chars
- H1: One per page, includes primary keyword "Lovescape Review"
- H2s: Include keywords naturally ("AI Porn Generator", "AI Girlfriend Chat", etc.)
- Internal linking: Link to sections with anchor IDs
- Images: descriptive alt text, WebP format, lazy loading
- Schema: Add `Article` or `Review` structured data JSON-LD

---

## Design Notes
- **Theme:** Dark (Lovescape brand colors: #0F0F0F background, cyan/teal accents #07F0FF / #07FFB5, purple #CF7AFF)
- **Typography:** Clean sans-serif, readable sizes
- **CTAs:** High contrast, gradient buttons (cyan to teal or purple)
- **Cards:** Rounded corners, subtle borders, hover effects
- **Trust signals:** Privacy badges, user counts, rating stars

---

## Content Quality Standards
- Native English, persuasive marketing tone
- No AI-isms, no fluff, no repetitive filler
- Every paragraph adds value
- Use bullet points for readability
- Include specific details (resolution numbers, feature names)
- Write as a genuine review, not a sales pitch
- Include both pros AND cons for credibility

---

## Deliverables Checklist
- [ ] `index.html` — Pure template, zero text, data-i18n attributes
- [ ] `content.json` — ALL text content, ~3,000–5,000 words
- [ ] `_redirects` — Affiliate link cloaking
- [ ] `robots.txt` — SEO directives
- [ ] `sitemap.xml` — Single URL sitemap
- [ ] `privacy.html` — noindex, placeholder legal text
- [ ] `terms.html` — noindex, placeholder legal text
- [ ] `affiliate-disclosure.html` — noindex, FTC disclosure
- [ ] `favicon.svg` — Simple icon
- [ ] `/images/` — Placeholder image files
- [ ] All files committed and pushed to `main`

---

## Affiliate Link Note
**Affiliate link to use:** `https://lovescape.com/?ref=YOUR_AFFILIATE_ID`
- If user provides a real affiliate ref ID, update `_redirects`
- All affiliate links must have `rel="nofollow sponsored"`
- Cloak via `/go/lovescape` → 302 redirect
