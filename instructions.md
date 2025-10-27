# 🧠 Product Prototyping Super Prompt (v0-Ready)

```
Replace before each run:  
[TOPIC] = product domain  
[ROLE] = target user role  
[ACTION] = main goal  
[OUTCOME] = desired benefit  
```

You are an **expert Product Manager and Frontend Engineer** with deep expertise in **[TOPIC]**.  
Your task is to **transform the spec below into a complete, production-ready, Tailwind-based page** (one page per run) with a clean, modern UI and realistic mock data.  
Default stack: Anything you can run + tailwind css
If needed, you may choose an equivalent modern stack — do not ask for clarification, just decide and proceed.

---

## 🧩 Scope

We are building **three pages**, one per run:

1. **Promotional Page** — public marketing & pricing  
2. **Dashboard Page** — post-login view for paying users  
3. **Core Feature Page** — the main user workflow  

Each page must cross-link to the others (e.g. `/`, `/dashboard`, `/app/core`) and maintain a cohesive product feel.

**User Story Seed:**  
As a [ROLE], I want to [ACTION] so that [OUTCOME].

---

## 🎨 Global UX & Product Rules

- Consistent branding, tone, and structure across all pages  
- Each page must include visible links to the other two  
- Accessible: proper landmarks, labels, and color contrast  
- Responsive: mobile-first, works well from 360px to desktop  
- Include empty/edge states and loading skeletons  
- Use realistic mock data and helpful copy (no lorem ipsum)

---

## ⚙️ Tech & UI Constraints

- Tailwind CSS is required  
- Optional: shadcn/ui for components, lucide-react for icons, lightweight chart library when useful  
- Minimal dependencies — clean imports, no heavy frameworks  
- All interactive UI should have functional mock behavior  
- Output must be self-contained code only (no setup text)

---

## 🧱 Page-Specific Requirements

### 1️⃣ Promotional Page
- Hero section with headline/subhead and CTA leading to the dashboard  
- Secondary CTA leading to the pricing section  
- Pricing table with three tiers and monthly/yearly toggle  
- Social proof with logos or testimonials  
- Feature highlights, FAQ, and footer links  

### 2️⃣ Dashboard Page
- Authenticated, paid user layout  
- Navbar with product name and user menu  
- Summary cards (KPIs), activity table, and quick actions  
- Notifications or empty states  
- Onboarding tips for new users  

### 3️⃣ Core Feature Page
- Main workflow UI such as forms, tables, boards, or editors  
- Inline validation and success/error states  
- Save, apply, or preview flows with toasts  
- Contextual help and a link back to the dashboard  

---

## ✅ Quality Bar

- Modular, readable components with clear naming  
- Subtle animations and transitions  
- No dead links; every button performs a mock action  
- Deterministic output — copy, paste, run  

---

Here are the prompts I want you to generate. Please separate by lines and give me in markdown code so that I can copy paste easily, sequentially.

### 🧠 PROMPT 1 — Promotional Page (Start Here)
Using the **Product Prototyping Super Prompt (v0-Ready)** specification below, generate the **Promotional Page** of the product.  
[TOPIC] = [insert your product domain]  
[ROLE] = [insert your main user type]  
[ACTION] = [insert main user action]  
[OUTCOME] = [insert user benefit]  

This page must introduce the product, explain its value clearly, and include:  
- A hero section with main CTA leading to /dashboard  
- Pricing section (3 tiers, toggle monthly/yearly)  
- Social proof (testimonials/logos)  
- Feature highlights and FAQ  
- Footer with navigation links  

Ensure the UI is fully responsive, visually polished, and uses **Tailwind CSS**.  
Output code only — no explanations.  
Make sure to include links to `/dashboard` and `/app/core` for future pages.

---

### ⚡ PROMPT 2 — Dashboard Page (Run After Page 1)
Continue from the same product context as the Promotional Page.  
Generate the **Dashboard Page** (for logged-in, paid users) using the same design language and Tailwind setup.  

Include:  
- Navbar with brand name and user menu  
- Summary cards (KPIs), recent activity table, and quick actions  
- Notifications or empty states  
- Onboarding hints for new users  

Cross-link to `/` (Promotional Page) and `/app/core` (Core Feature Page).  
Maintain the same color scheme and layout rhythm.  
Output code only.

---

### 🚀 PROMPT 3 — Core Feature Page (Run Last)
Continue from the same product design and UX system as the previous two pages.  
Generate the **Core Feature Page**, representing the main functional workflow that fulfills the user story:  
“As a [ROLE], I want to [ACTION] so that [OUTCOME].”  

Include:  
- Main interactive UI (form, table, board, or editor)  
- Inline validation, success/error toasts  
- Save / preview flow  
- Contextual help or hints  
- Link back to `/dashboard`  

Use Tailwind CSS with the same design language.  
Output code only — ready for copy-paste into v0 or Bolt.
