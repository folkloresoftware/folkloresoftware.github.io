# Site Revamp Plan

## Purpose

This document captures the recommended direction for evolving the `rlziii.com` and `folkloresoftware.com` redesigns from mostly-single-page sites into a clearer hybrid multi-page system.

The goal is not to add pages for their own sake. The goal is to make each site easier to read, easier to navigate, easier to share, and easier for prospective clients to discover through search.

Current implementation scope: the next pass is for `folkloresoftware.com` only. The `rlziii.com` recommendations in this document are planning context for a separate future pass in that repo.

## Recommendation

Use a hybrid structure:

- Keep each homepage as a strong guided overview.
- Move deeper, intent-specific content into dedicated pages.
- Make `rlziii.com` the personal credibility hub.
- Make `folkloresoftware.com` the primary consulting and contracting sales site.
- Mention App Ready only where larger-team capacity matters.

This is especially important for Folklore Software because it needs to communicate several related but distinct offers: contract engineering, consulting, app modernization, architecture review, workshops, internal training, backend/web/AI support, and larger project delivery through App Ready.

## Reference Pattern

The useful reference pattern is the relationship between an individual developer site and an associated consultancy site.

- [Tim Condon](https://www.timc.dev/) functions as the individual/developer hub. It has separate navigation for About Me, Blog, Speaking and Podcasts, and Services and Training.
- [Broken Hands](https://www.brokenhands.io/) functions as the consulting/company site. It separates About Us, Training Courses, Services, Consultancy, and Contact.

The relationship is similar to:

- `rlziii.com`: Richard's personal engineering home, credibility surface, writing, speaking, resume, and project archive.
- `folkloresoftware.com`: Folklore Software LLC's consulting and contracting site, focused on client conversion.

The lesson is not that these sites should be copied visually. The lesson is that the personal site and consultancy site can support each other while serving different visitor intents.

## Why Move Toward Multi-Page

Multi-page structure helps when visitors arrive with different questions:

- Who is Richard?
- Can I hire him?
- What services does Folklore Software offer?
- Does he do workshops or internal teaching?
- Has he built software like my project?
- Can he support backend, web, or AI work too?
- What if my project needs more than one engineer?
- Where are the talks, writing, resume, and project archive?

Separate pages make those paths easier to follow.

### Readability

A single long page can work well as an introduction, but it gets harder to scan as the offer becomes more nuanced. Dedicated pages let each topic breathe without forcing every visitor through every section.

### Navigation

Clear top-level routes help visitors self-select:

- About
- Projects or Case Studies
- Speaking
- Blog
- Services
- Training
- Contact

This is especially useful for people who already know what they want.

### SEO

Dedicated pages can target search intent more precisely than homepage sections.

Examples:

- `/services` can target iOS consulting, Swift consulting, app modernization, architecture review, backend/API support, and AI product development.
- `/training` can target internal Swift training, SwiftUI workshops, The Composable Architecture (TCA) training, and team coaching.
- `/case-studies` can target evidence-based consulting searches and give each project more context.
- `/speaking` can target talks, conference appearances, and teaching credibility.
- `/blog` can build long-term search surface around specific technical topics.

The important caution: do not create thin pages. A page should exist only when it can answer a real visitor question better than a homepage section can.

## Why Keep a Strong Homepage

There are still good reasons to keep a longer homepage:

- It gives first-time visitors a guided story.
- It keeps the site easy to maintain.
- It reduces decision fatigue.
- It helps visitors quickly understand the whole offering.
- It avoids thin pages that do not add much value.
- It keeps the tone personal and direct.

The homepage should act as a well-structured overview, not as the only place where every detail lives.

## Site Roles

### rlziii.com

Primary role: build trust in Richard as a senior engineer.

This site should answer:

- Who is Richard?
- What is he especially good at?
- What has he shipped?
- Where are his talks, writing, resume, and project archive?
- How do I hire him or learn more about consulting?

Recommended positioning:

> Senior iOS engineer and software consultant with deep Apple-platform experience, practical full-stack range, and availability for contract development, consulting, workshops, and technical leadership.

The site should stay personal and credible. It should not become the main services catalog.

### folkloresoftware.com

Primary role: convert prospective clients.

This site should answer:

- What problems can Folklore Software help with?
- What services are available?
- What kinds of projects are a good fit?
- Why trust Folklore Software?
- What does an engagement look like?
- How does someone start a conversation?
- What happens if the project needs more than one engineer?

Folklore should be more sales-oriented than `rlziii.com`, but still grounded in engineering credibility and evidence.

### App Ready

Primary role: larger-team delivery path.

App Ready should not compete with Folklore on the personal or Folklore sites. It should be described as the path for projects that need more than one engineer or broader delivery capacity.

Suggested short phrasing:

> For larger projects that need more than one engineer, I also work through App Ready, a small product engineering partnership for broader mobile, web, backend, and AI delivery.

## Recommended rlziii.com Structure

`rlziii.com` can stay close to the current structure, but with clearer dedicated pages over time.

### `/`

Personal homepage and overview.

Recommended sections:

- Hero and availability
- Focus areas
- Recent Projects, limited to three highlights
- Speaking and writing preview
- Blog preview
- About summary
- Contact
- Short Folklore Software CTA
- Small App Ready mention only near contact or consulting context

### `/about`

Confirmed page.

Add a dedicated `/about` page for clarity. The homepage can still include an About summary, but the dedicated page should give more room to explain Richard's background, working style, and credibility.

Potential content:

- Professional story
- Apple-platform experience since 2014
- Doximity leadership and production experience
- Consulting and product-building background
- Teaching, workshops, and technical communication
- Working style and values

### `/projects`

Already useful as the broader project archive.

Purpose:

- Keep the homepage focused on three Recent Projects.
- Preserve older and more playful work.
- Give visitors a richer sense of range.

### `/speaking`

Confirmed page.

Update `presentations.html` to `/speaking`. The wording "speaking" is preferred for the URL and navigation, while "presentations" can still be used naturally in page copy where it reads better.

Keep `/presentations` as a redirect or backward-compatible page if practical, since existing links may point there.

### `/blog`

Keep as a real page, but publish at least one post before treating it as a strong navigation destination.

Good first post categories:

- Swift Concurrency adoption
- The Composable Architecture (TCA)
- App modernization
- AI-enabled product work
- Lessons from maintaining production iOS apps
- Internal workshops and engineering teaching

### `/consulting`

Confirmed page.

Add a short `/consulting` bridge page explaining:

- Richard is available for consulting and contract work through Folklore Software.
- Larger projects can be routed through App Ready.
- Best contact path is `contact@folkloresoftware.com`.

This page should not duplicate the full Folklore services site. Its job is to make the relationship between Richard, Folklore Software, and App Ready clear.

## Recommended Folklore Software Structure

Folklore Software should move more strongly toward a multi-page consulting-site structure.

### `/`

Homepage and conversion overview.

Recommended sections:

- Hero
- What Folklore Software helps with
- Services preview
- Recent Projects preview
- Workshops/training preview
- About Richard/Folklore Software LLC
- Hidden testimonials section, ready to enable later when real quotes are available
- Contact CTA

The homepage should be noticeably shorter than the current single-page site. It should summarize, not explain everything, because the dedicated pages should make the site easier to digest and navigate.

### `/services`

Primary service catalog.

Confirmed service positioning:

Folklore Software should lead with Apple-platform and iOS engineering as the specialty. The services page can show full-stack range, but it should not read like a generic "I do everything" list. The framing should be:

> Deep iOS and Apple-platform engineering, with practical full-stack support across backend services, web apps, AI-enabled features, and developer tooling.

Confirmed service sections:

- iOS app development
- SwiftUI/UIKit modernization
- Architecture review
- App rescue and technical recovery
- Backend/API development, especially services that support mobile products
- Web app development where it supports product delivery or client needs
- AI-enabled product features and internal tooling
- Developer tooling and internal workflows
- Technical advising and planning

Each service should explain:

- What problem it solves
- When a client should consider it
- What a typical engagement might look like
- What outcomes the client can expect

### `/training`

Confirmed page.

Use `/training` as the dedicated page for internal teaching, workshops, and temporary team-building support.

Confirmed training topics:

- Swift
- SwiftUI
- UIKit architecture
- The Composable Architecture (TCA)
- Swift Concurrency
- App modernization
- AI-enabled engineering workflows
- Architecture review and maintainability

This page matters because some teams may not need a contractor to build features. They may need someone to teach, unblock, or level up the existing team.

Training should be flexible rather than a fixed course catalog. Folklore Software can work with a team or company's needs to create a custom workshop, training plan, pairing structure, or review session that fits the situation.

Confirmed training formats:

- Short workshops
- Multi-session internal training
- Architecture review sessions
- Pairing and coaching
- Custom team training

### `/projects`

Confirmed page.

Use `/projects` for client-relevant proof, including case studies where enough public-safe detail is available.

Recommended approach:

- Keep exactly three Recent Projects on the homepage.
- Use this page for deeper project context.
- Keep all project detail on one `/projects/` page in this pass.
- Full case-study pages are a future option only if there is enough public-safe detail and a later decision to split them out.

Confirmed projects:

- Circls Hangout
- Mobile Safe Zones
- Lloyd's Glass Services

These three projects can be mentioned publicly by name.

Be careful not to imply that full-time work or personal projects were Folklore client projects unless the relationship is clearly explained.

### `/about`

Folklore-specific about page.

Content should focus on:

- Folklore Software LLC
- Richard's senior engineering background
- Reliability and communication
- Practical technical judgment
- Workshop and consulting style
- Why the company exists

### `/contact`

Dedicated conversion page.

Include:

- Primary email: `contact@folkloresoftware.com`
- Suggested details to include in an inquiry
- Mention that larger projects can be routed through App Ready when appropriate

For now, use plain email rather than a scheduling link or contact form.

### Testimonials

Keep testimonials ready to use, but hidden until real public quotes, names, and images are available.

Testimonials should live on the homepage when enabled, not on a separate testimonials page.

### App Ready section

Confirmed direction.

Folklore does not need a full App Ready page immediately. Keep App Ready as a short paragraph near the bottom of `/services`.

App Ready does not need to appear on the homepage in this pass.

The mention should stay similar in weight to the current version: useful and clear, but secondary to Folklore Software's own consulting offer. Do not describe App Ready as "two-person" because that may make it feel too small. Either avoid size language altogether or describe it more generally as a product engineering partnership.

Recommended phrasing:

> For larger projects that need broader delivery capacity, Folklore Software can also route work through App Ready, a product engineering partnership that can support mobile, web, backend, AI, and trusted specialist needs.

Link to `appready.dev` from this paragraph, but keep the main call to action focused on contacting Folklore Software.

Potential future reason to add a full App Ready page:

- Larger-team inquiries are common.
- App Ready has distinct case studies.
- There is a need to explain subcontracting or broader delivery capacity in more detail.

## Suggested Navigation

### rlziii.com

Recommended top nav:

- About
- Projects
- Speaking
- Blog
- Resume
- Consulting

Keep the personal site compact.

### folkloresoftware.com

Recommended top nav:

- Services
- Training
- Projects
- About
- Contact

Keep the primary CTA visible:

- Start a project conversation
- Contact Folklore Software

Use clean directory-style URLs:

- `/services/`
- `/training/`
- `/projects/`
- `/about/`
- `/contact/`

Use shared Jekyll structure such as `_layouts/default.html` and `_includes/` for repeated page chrome, navigation, footer, analytics, and shared metadata behavior.

## SEO Notes

Primary SEO targets for `rlziii.com`:

- Senior iOS engineer
- iOS software consultant
- Swift consultant
- SwiftUI engineer
- iOS architecture
- Swift speaker
- Swift workshops

Primary SEO targets for `folkloresoftware.com`:

- iOS consultant
- Swift consultant
- SwiftUI consultant
- contract iOS developer
- app modernization consultant
- mobile app consultant
- iOS architecture review
- Swift workshops
- iOS training
- Swift training
- internal engineering workshops
- The Composable Architecture (TCA) consulting
- backend API development for mobile apps
- AI product development consultant

Recommended SEO practices:

- Give each page a unique title and description.
- Use descriptive headings that match search intent.
- Avoid creating thin pages.
- Add case studies when public-safe details are available.
- Add testimonials if they can be used publicly.
- Add internal links between related pages.
- Keep `rlziii.com` and `folkloresoftware.com` clearly connected, but do not make them duplicate each other.

## Implementation Phases

### Phase 1: Document and Decide

- Confirm the recommended sitemap.
- Confirm decisions in this document before implementation.
- Treat remaining nonessential additions as future improvements, not launch blockers.

### Folklore Implementation Defaults

Use these defaults when implementing the Folklore Software revamp unless a later decision overrides them:

- Use shared Jekyll structure:
  - `_layouts/default.html` for common document structure, SEO tag rendering, stylesheet loading, and page chrome.
  - `_includes/header.html` for the site header and navigation.
  - `_includes/footer.html` for the footer and Cloudflare Web Analytics snippet.
  - Use small includes for repeated cards only when they reduce meaningful duplication without making the site harder to edit.
- Keep the Cloudflare Web Analytics snippet on every public page through the shared footer/body include.
- Preserve the current custom `ProfessionalService` JSON-LD on the homepage unless a page-specific schema is clearly useful.
- Use page-specific front matter titles and descriptions for SEO.
- Add simple `sitemap.xml` and `robots.txt` files for crawler and Search Console discovery.
- Keep the homepage concise and route deeper details into `/services/`, `/training/`, `/projects/`, `/about/`, and `/contact/`.
- Keep hidden testimonials in the homepage source, out of the navigation, and out of visible page flow until real testimonials are available.
- Keep App Ready off the homepage in this pass. Mention App Ready only near the bottom of `/services/` and, if useful, briefly on `/contact/` as a routing option for larger work.
- Use email-only contact paths throughout the site.
- Preserve existing copy where it still works. Add or expand copy only where a new page needs enough substance to stand on its own.
- Avoid thin pages. Each new page should answer a distinct visitor question and include enough useful content to justify its URL.
- Do not add pricing, minimum engagement size, scheduling links, contact forms, new testimonials, or new project claims in this pass.
- Do not add a Folklore blog in this pass.
- Do not add Richard's portrait to Folklore in this pass.
- Keep the current Folklore logo, App Ready logo, project images, and placeholder testimonial assets.
- Keep the existing Cloudflare Web Analytics token as-is.
- Keep the current email address as the primary CTA:
  `contact@folkloresoftware.com`

No remaining blocking questions are known before implementation.

### Phase 2: rlziii.com

- Keep current homepage mostly intact.
- Add `/about`.
- Add `/consulting` as a short bridge page to Folklore Software and App Ready.
- Keep `/projects` and `/blog`.
- Move `presentations.html` to `/speaking`, preserving `/presentations` as a redirect or backward-compatible route if practical.

### Phase 3: Folklore Software

- Move from a mostly-single-page site to a stronger multi-page structure.
- Start with `/`, `/services`, `/training`, `/projects`, `/about`, and `/contact`.
- Include App Ready as a short larger-team paragraph near the bottom of `/services`.
- Use email as the primary contact method for now.
- Use Circls Hangout, Mobile Safe Zones, and Lloyd's Glass Services as the three public project examples.
- Keep `/projects` as one projects page for now; do not create individual case-study pages in this pass.
- Emphasize iOS and Apple-platform engineering first, while presenting backend, web, AI, and tooling as practical full-stack support.
- Do not create a Folklore blog; keep writing on `rlziii.com`.

### Phase 4: App Ready

- Revisit App Ready after Folklore is coherent.
- Position it clearly as the larger-team or broader delivery option.
- Avoid making it compete directly with Folklore Software.

## Future Improvements

These are useful additions, but they should not block the current revamp:

- Add testimonials, references, client quotes, or colleague quotes if any become available for public use.
- Revisit pricing guidance, minimum engagement size, or "select engagements" language later. Do not include explicit pricing in the next pass.
- Consider a scheduling link later if email-only creates friction. For now, keep contact email-based.
- Replace placeholder or generated project images with stronger public-safe screenshots or case-study visuals when available.

## Confirmed Decisions

Use these decisions when implementing the next pass:

- Keep `rlziii.com` as a personal hub with a strong homepage and clearer supporting pages.
- Add `/about` to `rlziii.com`.
- Add `/consulting` to `rlziii.com`.
- Move `presentations.html` to `/speaking`, preserving `/presentations` as a redirect or backward-compatible route if practical.
- Move Folklore Software toward a clearer multi-page consulting site.
- Folklore pages to build: `/`, `/services/`, `/training/`, `/projects/`, `/about/`, and `/contact/`.
- Use clean directory-style URLs for the Folklore pages.
- Use shared Jekyll layouts/includes for repeated site chrome, navigation, footer, analytics, and metadata behavior.
- Make the Folklore homepage noticeably shorter than the current single-page site.
- Folklore `/services` should emphasize iOS and Apple-platform development first, with backend, web, AI, and tooling presented as supporting full-stack range.
- Folklore `/projects` should use Circls Hangout, Mobile Safe Zones, and Lloyd's Glass Services on one projects page.
- Do not create individual project/case-study pages in the next pass.
- Circls Hangout, Mobile Safe Zones, and Lloyd's Glass Services can be mentioned publicly by name.
- Folklore `/training` should cover workshops and internal teaching.
- Folklore `/training` should support short workshops, multi-session internal training, architecture review sessions, pairing/coaching, and custom team training.
- Folklore contact should use email for now.
- Folklore should not have its own blog for now; writing should live on `rlziii.com`.
- Keep App Ready secondary, used only for larger-team context.
- Put the App Ready mention near the bottom of Folklore's `/services` page as a short paragraph.
- Do not include App Ready on the Folklore homepage in the next pass.
- Do not describe App Ready as "two-person"; describe it as a product engineering partnership or avoid size language.
- Keep the Folklore logo, keep the App Ready logo minimal, do not add Richard's portrait to Folklore, and keep the current project images for now.
- Folklore and `rlziii.com` should share a family resemblance, but Folklore should feel like a distinct company brand.
- Folklore should mention hourly contracting, project-based consulting, and fractional senior engineering.
- Keep writing primarily on `rlziii.com`.
- Use Folklore for client conversion.
- Do not split a page unless the new page has enough useful content to stand on its own.
- Keep testimonials hidden and ready to enable later; when enabled, testimonials should appear on the homepage rather than a separate testimonials page.
- Draft new page copy from the current site and this plan, preserving existing copy where it still works and adding new copy only where useful.
