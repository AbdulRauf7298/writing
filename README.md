# Complete Website Design & Functionality Plan

## Academic Writing Services Website
**Dissertation | Essay | Thesis | CV | Copywriting**

- **Platform:** WordPress  
- **Market:** UK Students & Academics  
- **Services:** 30+ Academic Writing Services  
- **Prepared:** 2025

---

## 1. Executive Summary

This document provides the complete design blueprint and functionality specification for an academic writing services website targeting UK students and academics. The platform will be built on WordPress and will offer over 30 services ranging from dissertation writing to CV preparation.

### Business Goal
Build a high-converting, SEO-optimised academic writing services website that ranks on Google UK, processes orders securely, manages writer assignments, and generates recurring student revenue through trust, quality, and transparent pricing.

### Core Objectives
- Generate inbound traffic through targeted SEO for each service page
- Convert visitors into paying customers via a seamless order and payment flow
- Build trust through reviews, writer credentials, and money-back guarantees
- Operate efficiently with a backend system for order management, writer assignment, and customer support

---

## 2. Site Architecture & Page Structure

### 2.1 Complete Sitemap

| Page Category | Pages Included | Priority |
|---|---|---|
| Core / Navigation | Home, About Us, Contact, Blog, Sitemap | High |
| Dissertation Services | Dissertation Writing, Proposal Writing, PhD Dissertation, MBA Dissertation, Masters Dissertation Help, Literature Review, Dissertation Editing, Dissertation Topics Help | High |
| Essay Services | College & Uni Essays, Cheap Essay Writing, Admission Essay Writing, Psychology Essay Help, Essay Editing Services UK, Buy Essay Online | High |
| Assignment & Coursework | Buy Assignment Online, Buy Law Assignment UK, Coursework Writing Services, Case Study Help, Case Study Writing Services UK, Research Paper Help | High |
| Specialist Writing | Thesis Writing Services, Research Proposal Help, Term Paper Writing Service, Nursing Dissertation Writing, Academic Writing Services | Medium |
| Professional Services | CV Writing Services, Copywriting Services UK | Medium |
| Legal / Trust Pages | Privacy Policy, Terms & Conditions, Refund Policy, Anti-Plagiarism Policy, Disclaimer | High |
| Account Pages | Register, Login, My Orders, My Account, Track Order | High |

### 2.2 URL Structure
Use clean, keyword-rich URLs targeting UK search terms:
- `/dissertation-writing-services/`
- `/phd-dissertation-writing/`
- `/cheap-essay-writing-uk/`
- `/cv-writing-services-uk/`
- `/blog/how-to-write-a-dissertation-methodology/`

---

## 3. Complete Website Design Plan

### 3.1 Brand Identity & Visual System

| Element | Specification | Rationale |
|---|---|---|
| Primary Colour | `#185FA5` (Royal Blue) | Trust, professionalism, academic authority |
| Secondary Colour | `#0D3F75` (Dark Navy) | Headings, depth, contrast |
| Accent Colour | `#F59E0B` (Amber) | CTAs, badges, urgency elements |
| Success Colour | `#1A7A4A` (Green) | Guarantees, checkmarks, positive cues |
| Background | `#FFFFFF` / `#F5F7FA` | Clean, readable, professional |
| Body Font | Inter or Source Sans Pro | Screen-optimised, modern, readable |
| Heading Font | Poppins (Bold) | Strong, academic feel, mobile-friendly |
| Font Sizes | H1: 42px, H2: 32px, H3: 24px, Body: 16px | Clear visual hierarchy |
| Border Radius | 8px cards, 50px buttons | Modern and approachable |
| Logo Style | Text wordmark + graduation cap icon | Simple, scalable, recognisable |

### 3.2 Homepage Design — Section by Section

1. **Top Navigation Bar (Sticky):** Logo, menu (Services/Pricing/Reviews/Blog/About/Contact), Live Chat, Login/My Account, Order Now CTA, announcement bar, mobile hamburger drawer.
2. **Hero Section:** Dark navy gradient/image, H1 keyword headline, trust subheading, mini order form (service/level/word count/deadline), trust badges.
3. **Services Mega Grid:** Count badge, responsive cards (4/2/1), icon + service + description + link, “View All Services”.
4. **How It Works:** 4 steps (Fill Form → Payment → Writer Assigned → Receive Work), icons and descriptions.
5. **Stats Bar:** Animated counters (students helped, writers, on-time %, rating).
6. **Why Choose Us:** 6 feature boxes (PhD Writers, Plagiarism Free, etc.).
7. **Featured Services Pricing Preview:** Tabs (Dissertation/Essay/Thesis/CV) with 3-tier pricing.
8. **Testimonials Carousel:** 8–12 verified reviews + Trustpilot widget.
9. **Guarantee Section:** 5 guarantees with icon/title/explanation.
10. **Blog Preview:** Latest 3 posts with thumbnails/tags/excerpts.
11. **Footer:** 4 columns, legal links, disclaimer, payment badges.

### 3.3 Service Landing Page Template
Each 30+ service page includes:
- Hero with H1 + mini order form
- What We Offer bullets
- Why Choose Us features
- 4-step process
- Pricing table (3 tiers)
- Sample work download
- Writer profiles
- FAQ accordion (8–10 questions)
- Service-specific testimonials
- Related services internal links
- Final CTA block

### 3.4 Responsive Breakpoints
- **Desktop (1200px+):** full layout, mega menu, 4-column grids
- **Tablet (768–1199px):** 2-column grids, collapsed nav
- **Mobile (320–767px):** 1-column stack, simplified form, sticky bottom CTA

---

## 4. Complete WordPress Functionality Plan

### 4.1 Theme Stack
- Theme: **Astra Pro** or **Kadence Pro**
- Builder: **Elementor Pro** (or Bricks)
- **Child theme required** for update-safe customization

### 4.2 Core Plugin Stack

| Plugin | Purpose | Free/Paid | Priority |
|---|---|---|---|
| WooCommerce | Orders, checkout, service products | Free | Essential |
| Stripe for WooCommerce | Card payments | Free | Essential |
| PayPal Payments | PayPal checkout | Free | Essential |
| Gravity Forms | Multi-step order + calculator | Paid | Essential |
| Rank Math SEO Pro | SEO, schema, sitemap | Free/Paid | Essential |
| Elementor Pro | Page building | Paid | Essential |
| WP Rocket | Caching/performance | Paid | Essential |
| Smush Pro / ShortPixel | Image optimisation | Free/Paid | Essential |
| Tidio Live Chat | Chat + chatbot | Free/Paid | High |
| WP Customer Reviews | Verified reviews | Free | High |
| OptinMonster | Popups/lead capture | Paid | High |
| MailPoet / FluentCRM | Email automation | Free/Paid | High |
| Wordfence Security | Firewall/malware/login security | Free/Paid | High |
| UpdraftPlus | Backups | Free/Paid | High |
| WooCommerce Subscriptions | Recurring plans | Paid | Medium |
| AffiliateWP | Referrals | Paid | Medium |
| Click to Chat | WhatsApp CTA | Free | Medium |
| Countdown Timer Ultimate | Urgency timers | Free | Medium |
| TablePress | Comparison/pricing tables | Free | Medium |
| Yoast Duplicate Post | Clone service templates | Free | Medium |
| WPML or Polylang | Multilingual support | Paid | Low |

### 4.3 Order Management System

#### 4.3.1 End-to-End Flow
1. Customer submits service quote/order form
2. Form captures service/level/subject/word count/deadline/format/instructions/uploads
3. Live calculator updates total
4. Customer checks out in WooCommerce (guest or account)
5. Payment through Stripe/PayPal (SSL)
6. Confirmation emails sent to customer/admin
7. Admin assigns writer
8. Writer uploads draft in private portal
9. Admin QA + plagiarism check + release
10. Customer downloads from account
11. Revision requests accepted within 14 days
12. Review request sent 48 hours post-delivery

#### 4.3.2 Form Fields
- Service Type (30+)
- Academic Level (High School, Undergraduate, Masters, PhD)
- Subject/Discipline (50+)
- Word Count/Pages (250–20,000)
- Deadline (min 6 hours)
- Paper Format (Harvard/APA/MLA/Oxford/Chicago/Other)
- Instructions (required, min 50 chars)
- File Upload (PDF/DOCX/JPG, max 20MB)
- Additional Comments (optional)
- Coupon Code (WooCommerce validation)
- Calculated Price (real-time)

### 4.4 Pricing Engine
Dynamic pricing by **academic level + urgency + word count**.

| Academic Level | Standard (7+ days) | Express (3–6 days) | Urgent (24–72 hrs) |
|---|---|---|---|
| Undergraduate | From £9.99/page | From £14.99/page | From £19.99/page |
| Masters | From £12.99/page | From £17.99/page | From £24.99/page |
| PhD / Doctoral | From £16.99/page | From £22.99/page | From £29.99/page |
| MBA | From £14.99/page | From £19.99/page | From £26.99/page |

### 4.5 User Account System
WooCommerce My Account includes dashboard, order statuses, order details (with deadline countdown), secure messaging, saved papers, billing history, referral tracking, and profile settings.

### 4.6 Admin Backend Dashboard
Order filters, writer management, revenue dashboard, coupon manager, review moderation, email automation controls, SEO monitoring, support tickets, plagiarism reports, and affiliate administration.

### 4.7 SEO Strategy & Content Plan

#### 4.7.1 On-Page SEO
- Unique H1 per service keyword
- Meta title ≤ 60 chars with UK + year
- Meta description ≤ 155 chars with CTA
- FAQ + breadcrumb schema (Rank Math)
- LocalBusiness schema on Home/Contact
- 5 related internal links per service page
- Keyword-focused image alt text
- LCP target under 2.5s

#### 4.7.2 Blog Publishing Plan

| Content Type | Example Topics | Frequency |
|---|---|---|
| How-To Guides | Dissertation introduction UK, MBA dissertation structure | 3/week |
| Topic Lists | Psychology topics 2025, MBA ideas | 2/week |
| Service Explainers | Literature review/dissertation length questions | 2/week |
| University Guides | Harvard/APA referencing UK | 1/week |
| Comparison Posts | Dissertation vs thesis UK | 1/week |

### 4.8 Trust & Conversion Features
- Trustpilot + Google Reviews badges
- Live order counter
- Writer profiles and anonymised sample papers
- Exit-intent first-order discount popup
- Mobile sticky “Order Now” bar
- Urgency countdown timers
- Live price calculator
- 24/7 chat + WhatsApp button
- Coupon banner
- Trust badges below CTAs

### 4.9 Payment & Security
Stripe + PayPal, SSL, PCI-safe hosted fields, WooCommerce refunds, GBP currency, PDF invoices, Stripe Radar fraud checks, Wordfence + 2FA, GDPR privacy + CookieYes consent.

### 4.10 Email Marketing & Automation
Triggered lifecycle emails: order confirmation, writer assignment, progress update, delivery, revision acknowledgement, completion + discount, review request, win-back campaign, weekly newsletter, abandoned quote reminders.

### 4.11 Performance & Hosting
SiteGround/WP Engine/Cloudways (UK-capable), Cloudflare CDN, WP Rocket caching, WP-Optimize cleanup, WebP image compression, Core Web Vitals targets (LCP <2.5s, FID <100ms, CLS <0.1), uptime monitoring, staging workflow.

---

## 5. Website Launch Plan

### 5.1 Development Timeline

| Phase | Tasks | Duration | Deliverable |
|---|---|---|---|
| 1 Setup | Domain, hosting, WP install, SSL, theme/plugins | Week 1 | Working WP site |
| 2 Design | Homepage, typography/colors, header/footer, responsive QA | Week 2–3 | Designed homepage |
| 3 Service Pages | Build 30+ landing pages from template | Week 4–5 | Service pages live |
| 4 Functionality | WooCommerce, Gravity Forms, calculator, payment flow | Week 6–7 | End-to-end orders |
| 5 Content & SEO | Optimised content, Rank Math, schema, sitemap | Week 8–9 | SEO-ready site |
| 6 Testing | Browser/mobile/checkout/speed/GDPR QA | Week 10 | QA complete |
| 7 Launch | Go-live, submit sitemaps, analytics | Week 11 | Live website |
| 8 Post-Launch | Monitor rankings, promotions, review collection | Week 12+ | Ongoing growth |

### 5.2 Post-Launch Marketing
- Submit sitemap to GSC + Bing
- Connect GA4 + Search Console
- Launch high-intent Google Ads
- Social launch (Facebook/Instagram/TikTok)
- Build list via popup offers
- Outreach to UK student communities
- Setup Google Business Profile
- Build backlinks through relevant partners

### 5.3 KPIs

| KPI | Month 3 | Month 6 | Tool |
|---|---|---|---|
| Monthly Organic Visitors | 2,000 | 10,000+ | GA4 |
| Conversion Rate | 2.5% | 4%+ | WooCommerce + GA4 |
| Average Order Value | £150 | £200+ | WooCommerce Reports |
| Monthly Revenue | £3,000 | £20,000+ | WooCommerce |
| Keyword Ranking | Page 3 | Page 1 | Rank Math / Ahrefs |
| Review Score | 4.5+ | 4.7+ | Trustpilot |
| Email List Size | 500 | 3,000+ | MailPoet / FluentCRM |
| Repeat Customer Rate | 15% | 30%+ | WooCommerce |

---

## 6. Legal & Compliance Requirements

### Important Notice
All services must clearly state that work is provided **for academic reference and study purposes only**.

### 6.1 Required Legal Pages
- Privacy Policy (GDPR)
- Terms & Conditions
- Refund & Cancellation Policy
- Anti-Plagiarism Policy
- Academic Integrity Disclaimer
- Cookie Consent via CookieYes

### 6.2 UK Recommendations
- Register with HMRC (sole trader or limited company)
- Maintain PCI-DSS compliant processing (Stripe/PayPal)
- Store customer data in UK/EEA where appropriate
- Provide clear business contact details/address
- Avoid misleading claims

---

## 7. Budget Estimate (Annual)

| Item | Cost Estimate | Notes |
|---|---|---|
| Domain (.co.uk) | £10–£15 | Namecheap / 123-reg |
| Managed Hosting | £150–£400 | WP Engine / SiteGround |
| Astra Pro / Kadence Pro | £49 | Single site |
| Elementor Pro | £99 | Single site |
| Gravity Forms Elite | £259 | Calculator + multi-step forms |
| WP Rocket | £49 | Caching |
| Rank Math Pro | £59 | SEO |
| Tidio | £0–£20/mo | Live chat |
| OptinMonster | £108 | Popups |
| MailPoet Premium | £0–£100 | Depends on list size |
| Wordfence Premium | £99 | Security |
| UpdraftPlus Premium | £70 | Backups |
| AffiliateWP | £149 | Optional referral program |
| Smush Pro / ShortPixel | £60–£90 | Images |
| **Estimated Total** | **~£1,200–£1,800/yr** | Excludes ads/content production |

---

## Summary
This plan defines the full website design and operational framework to launch and scale a high-converting WordPress academic writing services business in the UK market. Start with essential pages/plugins and expand into advanced features (subscriptions, affiliates, multilingual) once baseline SEO and trust signals are producing steady order volume.
