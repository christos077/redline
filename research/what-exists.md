# What Already Exists: Contract-Review and Clause-Analysis Products (for Redline)

Agent 3 research, 2026-11-22. Redline is an unvalidated hypothesis.

## Method note
- Web searches used: 9 of 12 cap.
- Pages read in full: 7 of 15 cap (5 returned content; 2 returned HTTP 403: ConsumerAffairs and G2). Many other claims rest on search-result snippets only, and I mark those "snippet".
- Stopped early after reaching 8+ sourced findings.
- Prices from third-party sites are labelled as estimates. I did not verify any vendor's current pricing page except where noted.

## Comparison table

| Product | What it does | Target | Price | Top complaint |
|---|---|---|---|---|
| ToS;DR | Volunteers tag website ToS/privacy clauses good/bad; A-E grade; browser extension | Consumers (website users only) | Free (donation-funded) | Depends on volunteer curation; covers only reviewed sites; you cannot upload your own document (limitation noted in the Wikipedia article, no user complaint found) |
| ChatGPT / Claude etc. (general chatbots) | Paste or upload a contract and ask questions | Anyone | Not researched (no pricing source read) | Hallucinated or reworded clauses that read as real; lawyers warn against sole reliance |
| DoNotPay | "Robot lawyer" subscription for consumer legal tasks and documents | Consumers, small business | $36 per 2 months (consumer); $49.99/mo (small business plan), as at FTC-relevant time | FTC: claims it could replace a lawyer were unsubstantiated; paid $193,000 |
| Rocket Lawyer (Rocket Copilot Contract Review) | AI explains a contract in plain language and flags red flags; human Legal Pro on paid tier | Small business owners | Core AI review free with email registration (vendor claim); memberships roughly $34.99-$64.99/mo (snippet, sources disagree) | Trustpilot negative reviews criticise AI-generated replies to complaints (snippet); nothing found on review accuracy |
| Genie AI | Playbook-based contract review with risk scoring, drafting, templates | SMB and in-house teams; has an individual plan | Trial $0; Pro $59/mo annual or $75/mo monthly (individual) | Trustpilot 4/5 reviewer: some basic review tasks got stuck, some templates missing (snippet, single review) |
| Spellbook | AI contract review and drafting inside Word | Law firms and in-house legal teams (mid-market) | Custom quote; one third-party estimate ~$179/user/mo | G2 reviewer cons: inaccurate legal citations, formatting inconsistency, lag; aggregator notes hallucinations needing human check (snippet) |
| Harvey | Enterprise legal AI platform | Large law firms and enterprises | Not published; third-party estimates ~$1,000-$2,800+/seat/mo, ~20-seat minimum | Seat-minimum and all-or-nothing pricing pushback is the only complaint signal found (headline only, not read) |
| LeaseChat (UChicago Law AI Lab) | Lease analyzer flags red flags, Q&A with citations, tenant-rights info, letter drafter | US renters | Free | Not found. Its location-specific legal info comes from ChatGPT; no independent accuracy testing reported |
| Micro-tools for freelancers (ContractGuard, ClauseShield, ContractRev, ClauseCheck, Contract Review) | Upload a contract, get AI red flags | Freelancers, solo operators | Free tier typically 3 reviews/mo; paid roughly $5-$79/mo (vendor/Product Hunt listings) | Not found (few or no independent reviews) |

## Per-product detail

### 1. ToS;DR (Terms of Service; Didn't Read)
- What: Volunteers rate each clause in a service's terms as positive, negative, blocker or neutral; services get a grade A to E. Browser extension for Chrome, Edge, Safari, Firefox, Opera. Founded 2012, revived 2020.
- Target: Consumers deciding about popular websites. It does not analyse a document the user supplies.
- Price: Free. Funding described elsewhere as non-profit and donations (search snippet).
- Complaint: No user complaint found. Wikipedia notes grades depend on volunteer curation and coverage is limited to reviewed services.
- Sources: https://en.wikipedia.org/wiki/Terms_of_Service;_Didn%27t_Read ; https://usercentrics.com/magazine/articles/data-literacy-with-terms-of-service-didnt-read/ (snippet)

### 2. General-purpose chatbots (ChatGPT, Claude) for contract review
- What: Users paste a contract and ask for risks. I found commentary, not usage data. I found no Reddit or HN threads in my search.
- Complaints (from lawyer and vendor commentary): AI fills gaps with plausible text and a made-up clause reads like a real one (Lawpath); an LLM asked to quote a limitation-of-liability clause verbatim changed the wording (World Commerce & Contracting); a construction lawyer said not to rely solely on AI to flag issues (Construction Dive). LegalSifter's critique is commercially motivated.
- Price: Not researched.
- Sources: https://lawpath.com.au/blog/review-ai-written-contract ; https://www.constructiondive.com/news/why-chatgpt-still-needs-a-construction-lawyer/806320/ ; https://www.worldcc.com/Resources/Blogs-and-Journals/Contracting-Excellence-Journal/View/ArticleId/11623/Can-you-trust-generative-AI-contract-co-pilots-Not-quite-but-a-new-type-of-autopilot-might-change-this ; https://www.legalsifter.com/guides/chatgpt-for-contract-review/ (all snippet)

### 3. DoNotPay
- What: Self-described "world's first robot lawyer"; generates legal documents and advice.
- Target: Consumers and small businesses.
- Price: Consumer subscription $36 every two months; Small Business Protection Plan $49.99/month at relevant times.
- Complaint / regulator action: FTC alleged DoNotPay never tested whether its chatbot matched human lawyers' output, hired no lawyers, and its tech was not trained on a comprehensive legal database. Settlement $193,000 without admitting liability; it must notify 2021-2023 subscribers and cannot claim lawyer-equivalence without evidence. Final order approved 5-0 on 2025-01-16 (snippet). A separate suit alleged some generated documents were poorly or inaccurately drafted.
- Relevance: This is the clearest regulatory warning for any consumer-facing "AI lawyer" claim. Note the FTC action is about marketing claims, not contract review specifically.
- Sources: https://www.abajournal.com/news/article/robot-lawyer-website-donotpay-settles-ftc-claims-it-couldnt-deliver-on-promises ; https://www.ftc.gov/node/87474 (snippet)

### 4. Rocket Lawyer (Rocket Copilot Contract Review)
- What: AI defines key terms, flags red flags and clauses needing a closer look, explains in plain language. Human Legal Pro help with Rocket Legal+. Follow-up questions currently go to a human Legal Pro; direct Q&A in Copilot was "planned".
- Target: Small business owners (per vendor press release).
- Price: Core AI review free with email registration (vendor claim). Memberships: sources disagree; one lists Standard $34.99/mo or $199/yr, Plus $49.99/mo, Pro $64.99/mo; 7-day free trial (snippet).
- Complaint: Trustpilot reviewers criticise AI-generated replies to complaints (snippet). I found no independent evidence on review quality. Vendor says it is not a law firm and the output is general information, not legal advice.
- Sources: https://www.rocketlawyer.com/newsroom/rocket-lawyer-launches-rocket-copilot-contract-review ; https://ch.trustpilot.com/review/rocketlawyer.com (snippet)

### 5. Genie AI
- What: Playbook-based review with risk scoring, issue tracker with one-click amendments, legislation citations, multi-document review.
- Target: SMBs and teams; individual tier exists.
- Price (vendor pricing page, fetched): Trial $0 (limited tokens, no exports/PDF upload). Pro $59/mo billed annually or $75/mo monthly, 1 user, about 5 documents a month. Business $320/mo ($259/mo annual) for up to 5 users. Third-party sites quote different figures ($38/mo), so they appear stale.
- Complaint: One 4/5 Trustpilot review cites basic review tasks getting stuck and missing templates (snippet, single review). G2 4.6 from 23 reviews (snippet). Mostly positive.
- Sources: https://www.genieai.co/en-id/pricing ; https://www.getapp.com/all-software/a/genie-ai/ (snippet) ; https://www.g2.com/products/genieai (snippet)

### 6. Spellbook
- What: AI drafting and review for contracts.
- Target: Law firms and in-house legal (mid-market).
- Price: Custom quote. Third-party estimate ~$179/user/month, unverified.
- Complaint: G2 (~4.7/5, ~28 reviews): inaccurate legal citations, formatting inconsistency, lag. Aggregator notes opaque pricing and hallucinations needing human verification (snippet). G2 page itself returned 403 when I tried to read it.
- Sources: https://www.g2.com/products/spellbook/pricing ; https://www.hyperstart.com/blog/spellbook-pricing/ (snippets)

### 7. Harvey
- What: Enterprise legal AI.
- Target: Large law firms and enterprises.
- Price: Not published. Third-party estimates, which conflict: ~$1,000-$2,800+ per seat per month, ~20-50 seat minimum, 12-month or longer contracts.
- Complaint: Only a headline signal (Law360: "Law Firms Push Back On AI Vendors' All-Or-Nothing Pricing"); I did not read it.
- Sources: https://spellbook.com/learn/harvey-ai-pricing (competitor source, treat with caution) ; https://costbench.com/software/ai-legal-tools/harvey-ai/ ; https://www.law360.com/pulse/articles/2387366 (snippets)

### 8. LeaseChat (University of Chicago Law School AI Lab, launched Dec 2025)
- What: Four features: Lease Analyzer (flags red flags such as unusually high deposits), Lease Chat (plain-language Q&A citing provisions and pages), Legal Rights by city/state, Letter Drafter. Available in Spanish.
- Target: US renters. Price: Free.
- Limitations: Location-specific legal information comes from ChatGPT; the team dropped a proprietary law database after seeing no accuracy gain. No independent accuracy testing reported; the LawSites article is a demo write-up with no criticism.
- Source: https://www.lawnext.com/2025/12/university-of-chicago-law-school-ai-lab-launches-leasechat-a-free-tool-to-help-renters-understand-their-leases-and-legal-rights.html

### 9. Other tenant and freelancer tools (all snippet-level)
- Tenant: TurboTenant Lease Agreement Audit (free, but aimed at landlords); Lease Decoder (iOS app, listed free); LeaseLogic (free score, full report paywalled).
- Freelancer: ContractGuard (free 3/mo, Team $49/mo), ClauseShield (free 3/mo), Contract Review (free 3/mo; $29/$79/$199), ContractRev (free 3; $9.99; $19.99), ClauseCheck (from $5, usage-based). Several listings had few or no user reviews.
- Sources: https://support.turbotenant.com/en/articles/9437901-how-to-use-lease-agreement-audit-ai ; https://apps.apple.com/us/app/lease-decoder/id6759229285 ; https://contractguard.pages.dev/pricing ; https://www.producthunt.com/products/contract-review/reviews ; https://www.capterra.co.uk/software/1103727/ClauseCheck

## Gaps in the market (evidence-backed only)
1. Established, well-reviewed products target legal teams and firms. Spellbook and Harvey are custom or enterprise-priced (Spellbook quote-only; Harvey estimated ~20-seat minimum). Neither is an individual-consumer product.
2. The consumer/freelancer segment is served by many thin, newly launched tools with free tiers capped around 3 reviews a month and almost no independent reviews. I found no dominant, trusted freelancer-focused product.
3. Tenants have at least one free, credible-origin tool (LeaseChat) that overlaps heavily with Redline's feature set (red-flag flagging, cited Q&A, letter drafting). Redline would face a free, university-backed competitor in the lease use case.
4. The only mainstream "AI for everyone" legal brand with regulator action (DoNotPay) shows that overclaiming is a legal risk. This is evidence that trust and substantiation matter in this segment.
5. Rocket Lawyer gives SMBs a free AI contract review, so the free-baseline expectation for SMBs already exists. Its follow-up Q&A was routed to humans at the time of the release.
6. None of the products I read combined all four of Redline's features (severity-ranked clauses with exact source sentence, per-clause counter-offer drafts, document-grounded Q&A, individual pricing). I did not test any product, so this is a feature-listing observation, not a verified absence.

## What I could not find
- Any Reddit or HN threads on contract-review tools. My Reddit-targeted search returned none.
- G2 and ConsumerAffairs pages (403), so there is no direct review text for Spellbook or Rocket Lawyer.
- Pricing for LegalOn, Ironclad, Juro, Lawgeex, LegalZoom's AI features. Not searched.
- Status of Robin AI. One search returned no confirmation either way; I make no claim about whether it still operates.
- Accuracy benchmarks for any product versus a lawyer.
- Pricing for general chatbots (ChatGPT, Claude); not researched.
- Verified complaints for LeaseChat, the freelancer micro-tools, and Harvey (beyond a headline).
- Usage or adoption numbers for any consumer-focused product.
